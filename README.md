 ヽ(✿ﾟ▽ﾟ)ノ MeRhAbA kOdLaMa 

:] kod1:

name=input("İsminizi girriniz:")
for i in range(7,0,-1):
    print(name[i-1])
 
 :) kod2:
 
x=input("name:")
for i in reversed(x):
    print(i,end="")
    
    
:D kod3:

a=8
b=5
a=int(input("please enter your a :"))
b=int(input("please enter your b :"))
average=(a+b)/2
print("average=", average)

('◡') kod4:

while True:
    sayi1=input("Sayı girin:")
    if not sayi1:
        break
    try:
        y=1/float(sayi1)
    except ValueError as el:
        print("Geçersiz sayı"+e1)
        continue
    except ZeroDivisionError as e2:
        print("Sıfıra bölme"+e2)
        continue
    print(y)
    
 (✿◠‿◠) kod5:

try :
    x=float(input("sayı gir"))
    işlem=x**1000
    print(işlem)
except OverflowError as e:
     print("işlem çok büyük",e)
except ZeroDivisionError as e1:
   print("sıfıra bölme",e1)
   
(✿◕‿◕✿) kod6:

a=0
b=[]#boş liste tanımladık
sayı=0#değişkrn olarak
while a<10:
    a=a+1# sayaç a yı arttırdım
    try:
        sayı=int(input("Lütfen sayı giriniz:"))
    except ValueError:
        print("Hatalı giriş.")
        sayı=0
    if sayı>0:
        b.append(sayı)
    elif sayı<0:
        break
print(b)

 （。＾▽＾) kod7:

a=0
while a<10:
    a=a+1
    try:
        sayı=int(input("Sayı giriniz:"))
        print(sayı)
    except ValueError:
        print("Hatalı giriş.")
    finally:
        print("Bitti.")
     
(⌐■_■) kod8:

fo=open("dosya.txt","r+")
print(fo.read())
fo.close()

（*＾-＾*) kod9:

Dizi=["elma","armut","portakal","mandalina"]
cikti=Dizi[1:3]
print(cikti)

（￣︶￣）↗ kod10:

Dizi=["elma","armut","portakal","mandalina"]
cikti=Dizi[:3]
print(cikti)

q(≧▽≦q) kod11:

Dizi=["elma","armut","portakal","mandalina"]
cikti=Dizi[2]
print(cikti)

(～￣▽￣)～ kod12:

dizi=["a","b","c","d","e","f","g","h"]
cikti=dizi[5:]
print(cikti)

O(∩_∩)O kod13:

dizi=["a","b","c","d","e","f","g","h"]
cikti=dizi[len(dizi)-1]
print(cikti)

(❁´◡`❁) kod14:

dizi=["a","b","c","d","e","f","g","h"]
cikti=dizi[0]
print(cikti)

φ(゜▽゜*)♪ kod15:

dizi=["a","b","c","d","e","f","g","h"]
cikti=dizi[len(dizi)-2]
print(cikti)

(*^_^*) kod16:

dizi=["a","b","c","d","e","f","g","h"]
cikti=dizi[len(dizi)-1:0:-4]
print(cikti)

o(*￣▽￣*)ブ kod17:

dizi1=["a","b","c","d"]
cikti=dizi1+["e"]
print(cikti)

（￣︶￣）↗ kod18:

dizi1=["a","b","c","d"]
cikti=dizi1+["z"]
print(cikti)

╰(*°▽°*)╯ kod19:

dizi1=["a","b","c","d"]
cikti=dizi1+["z"]
cikti[4]="x"
print(cikti)

(☆▽☆) kod20:

dizi=["a","b","c","d","e"]
dizi[1:4]=["x","y","z"]
cikti=dizi
print(cikti)

( *︾▽︾) kod20: 

dizi1=["a","b"]
dizi1=dizi1*10
print(dizi)

*^____^* kod21:

dizi=["a","b"]
dizi.append("c")
dizi.append("c")
print(dizi)

`(*>﹏<*)′ kod22:

kume={1,2,3,4}
kume.add(4)
kume.add(4)
print(kume)

ヾ(≧ ▽ ≦)ゝ kod23:

dizi=["a","b","a","b","a","c"]
say=dizi.count("a")
print(say)

(o゜▽゜)o☆ kod24:

dizi=["a","b","c"]
dizi.insert(1,"x")
print(dizi)

(。・∀・)ノ kod25:

a=" Habitat - Python! "
print(a.strip())

(＠＾０＾) kod25:

a="Ankara,Kayseri,Nevşehir,Kırşehir İç Anadolu Bölgesindedir."
print(a.split(";"))

( ﾟдﾟ)つ kod25:

a="Ankara,Kayseri,Nevşehir,Kırşehir İç Anadolu Bölgesindedir."
print(a.split("a"))

（＾∀＾●）ﾉｼ kod26:

a="Habitat ile Python")
print(a.upper())

(╯▽╰ ) kod27:

a="HABİTAT VE PYTHON"
print(a.lower())

(¬‿¬) kod28:

a="Muz sevilen bir meyvedir."
print(a.replace("Muz","Çilek"))

( •̀ .̫ •́ )✧ kod29:

txt="Sevdiğim havalar yağmurlu havalardır"
x="mur" in txt
print(x)

♪(´▽｀) kod30:

txt="Sevdiğim havalar yağmurlu havalardır"
x="mur" not in txt
print(x)

\(￣︶￣*\)) kod31:

metin="Bugünlerde 'Outlinera' kitabını okuyorum"
print(metin)

（。＾▽＾）kod32:

metin="""Bugünlerde "Outlinera" kitabını okuyorum"""
print(metin)

b(￣▽￣)d kod33:

metin= "\"Bu sıralar \"Outliners\" okuyorum. \""
print(metin)

◑﹏◐ kod34:

listem=[0,1,2,3,4,5,6,7,8,9]
for i in listem:

    if i%2==0:

        ciftliste.append(i)
    else:
        tekliste.append(i)
print("tek sayılar:",tekliste)
print("cift sayılar:",ciftliste)

(ಥ _ ಥ) kod35:

for sayi in range(1,21):   

    if sayi<10:

       sayi+=1 

       print(sayi)

(⓿_⓿) kod36:

for sayi in range(1,21):  
 

    if sayi>10 and sayi<21:
       sayi+=1 
       print(sayi)
       
༼ つ ◕_◕ ༽つ kod37:

numbers=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]

print(numbers[0:10])

print(numbers[-11:])

( ͡• ͜ʖ ͡• ) kod38:

sayilar=list(range(1,21))

print(sayilar)

print(sayilar [0:10])

print(sayilar [10:21]

＞﹏＜ kod39:

hafta_ici=["Pazartesi","Salı","Çarşamba","Perşembe","Cuma"]

hafta_sonu=["Cumartesi","Pazar"]

hafta_ici.append(hafta_sonu)
#hafta_ici.extend(hafta_sonu)
print(hafta_ici)

(´。＿。｀) kod40:

y=[]

for i in range(10):

    x=input("enter a no")

    if int(x)<0:

        print("it isn't acceptable")

    else:

        y.append(x)

print("The entered numbers are:",y,"and they are:",len(y))

y.sort()

print("Ordered numbers:",y)

(⊙ˍ⊙) kod41:

myList=[]
while True :
    sayi=int(input("Sayı gir: "))
    if sayi<0 or len(myList)>=10
        break
    else:
        myList.append(sayi)
myList.sort()
print("Liste:",myList, "eleman sayısı :",len(myList))

（*゜ー゜*）kod42:

t=[]
c=[]
a=0
while a<10:
    b=int(input("sayı gir: "))
    if b%2==0
       ciftSayilar.append(b)
    else:
       tekSayilar.append(b)
    a=a+1
print(c)
print(t)

o((⊙﹏⊙))o. kod43:

cift=[]

tek=[]

a=0

while a<10:

   sayi=int(input("sayi gir"))

   if sayi%2==0:

       cift.append(sayi)

    else:

       tek.append(sayi)

    a=a+1

print(cift)

print(tek)

-BiTtİ-
