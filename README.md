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

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;900&display=swap');
:root{
    --red-color:red;
    --white-color:white;
    --border-: 0.1rem solid red;
    --border: 0.1rem solid white;

}
html{
    overflow-x: hidden;
    scroll-padding-top: 9 rem;
    scroll-behavior: smooth;
}
*{
    font-family:'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
    text-decoration: none;
    text-transform: capitalize;
    transition: 0.2s ease;
}
/*birini bölümün başlangıcı*/
section{
    padding: 7rem 7%;
}
.header{
    min-height: 100vh;
    background: url(image/TacirlerBlueRed.png) no-repeat;
    background-size: 100%;
    background-position: top;
}
.header1{
    display: flex;
    justify-content: space-between;
    padding: 0 5%;
    align-items: center;
    padding: 0.5rem;
}
.header1 h5{
    color:red;
    font-size: 1rem;
    font-weight: 100;
    padding: 1rem 5%;
}
.header1 span{
    color: white;
}
.header2{
    display: flex;
    justify-content: space-between;
    padding: 0 5%;
    align-items: center;
}
.header2 .navbar a{
    margin: 0 1rem;
    font-size: 1rem;
    color: var(--white-color);
    border-bottom: 0.1rem solid var(--red-color);

}
.header2 .navbar .active,
.header2 .navbar a:hover {
    border-color: var(--white-color);
    padding-bottom: 0.5rem;
}
.header .btn{
    color: white;
    font-size: 1.4rem;
    border: 0.1rem solid var(--red-color);
    padding: 0.5rem;
}
.logo img{
    height: 2rem;
    padding-right: 1rem;
    padding-top: 3%; 
}
.logo1 img{
    height: 3rem;
}
.logo2 img{
    height: 5.5rem;
    /*css box shadow generator*/
    background-color: rgba(255, 255, 255, 0.384);
    border-radius: 100px;
    box-shadow: 0px 0px 0px 7px rgba(255, 255, 255, 0.200);
}
.home{
    color: white;
    align-items: center;
}
.home .content{
    max-width: 60rem;
}
.home .content h1{
    font-size: 6rem;
    font-weight: 600;
    color: rgba(240, 248, 255, 0.411);
}
.home .content h2{
    font-size: 6rem;
    font-weight: 600;
}
.home .content h3{
    font-size: 2rem;
    font-weight: 500;
}
.home .content p{
    font-size: 1.4rem;
    font-weight: 300;
    padding: 2rem 0;
}
.home .content h4{
    font-size: 1.4rem;
    padding: 2rem 0;
    color: aliceblue;
}
/*birinci bölümün bitişi*/
/*ikinci bölümün başlangıcı*/
.box-container{
    background: url(image/Group241.png) no-repeat;
    background-size: auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(10rem, 1fr));
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FİRMA WEB SİTE</title>
    <link rel="stylesheet" href="styles 0555.css">
</head>
<body>
    <!--Birici bölümün başlangıcı-->
    <header class="header">
        <header class="header1">
            <h5>TR <span>EN</span></h5>
            <a href="#" class="logo">
                <img src="C:\Users\PC\Desktop\image\facebook1.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\instagram1.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\twitterq.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\youtube1.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\linkedin1.png" alt="logo">
            </a>
        </header>
        <header class="header2">
            <a href="#" class="logo1">
                <img src="C:\Users\PC\Desktop\image\logo.png" alt="logo">
            </a>
            <nav class="navbar">
                <a href="#">Anasayfa</a>
                <a href="#">Kurumsal</a>
                <a href="#">Hizmetlerimiz</a>
                <a href="#">Acenteler</a>
                <a href="#">Haberler</a>
                <a href="#">İletişim</a>
            </nav>
             <a href="#" class="logo2">
                <img src="C:\Users\PC\Desktop\image\button.png" alt="logo">
            </a>
        </header>
        <section class="home">
            <div class="content">
                <h1>01</h1>
                <h2>GÜVEN <br> TAŞIYORUZ!</h2>
                <h3>PROFESYONEL ORGANİZASYON İLKEMİZ İLE</h3>
                <p>Profesyonel hizmet anlayışımız ile sektörde lider konumuna gelmeyi hedefleyen <br> vizyonumuzda sizlere soluksuz hizmet sağlıyoruz. Güveniniz için Teşekkürler!</P>
            </div>
        <a href="#" class="btn">KURUMSAL  >></a>
        </section>
    </header>
    <!--Birinci bölüm bitişi-->
    <!--İkinci bölümün başlangıcı-->
    <section>
        <div class="box-container">
            <div class="box">
                <div class="box-head">
                    <img src="C:\Users\PC\Desktop\image\hizmet1.png" alt="HİZMETLERİMİZ">
                </div>
            </div>
            <div class="box">
                <div class="box-head">
                    <img src="C:\Users\PC\Desktop\image\hizmet2.png" alt="HİZMETLERİMİZ">
                </div>
            </div>
            <div class="box">
                <div class="box-head">
                    <img src="C:\Users\PC\Desktop\image\hizmet3.png" alt="HİZMETLERİMİZ">
                </div>
            </div>
        </div>
    </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FİRMA WEB SİTE</title>
    <link rel="stylesheet" href="styles 0555.css">
</head>
<body>
    <!--Birici bölümün başlangıcı-->
    <header class="header">
        <header class="header1">
            <h5>TR <span> EN </span> </h5>
            <a href="#" class="logo">
                <img src="C:\Users\PC\Desktop\image\facebook1.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\instagram1.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\twitterq.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\youtube1.png" alt="logo">
                <img src="C:\Users\PC\Desktop\image\linkedin1.png" alt="logo">
            </a>
        </header>
        <header class="header2">
            <a href="#" class="logo1">
                <img src="C:\Users\PC\Desktop\image\logo.png" alt="logo">
            </a>
            <nav class="navbar">
                <a href="#">Anasayfa</a>
                <a href="#">Kurumsal</a>
                <a href="#">Hizmetlerimiz</a>
                <a href="#">Acenteler</a>
                <a href="#">Haberler</a>
                <a href="#">İletişim</a>
            </nav>
             <a href="#" class="logo2">
                <img src="C:\Users\PC\Desktop\image\button.png" alt="logo">
            </a>
        </header>
        <section class="home">
            <div class="content">
                <h1>01</h1>
                <h2>GÜVEN <br> TAŞIYORUZ!</h2>
                <h3>PROFESYONEL ORGANİZASYON İLKEMİZ İLE</h3>
                <p>Profesyonel hizmet anlayışımız ile sektörde lider konumuna gelmeyi hedefleyen <br> vizyonumuzda sizlere soluksuz hizmet sağlıyoruz. Güveniniz için Teşekkürler!</P>
            </div>
        <a href="#" class="btn">KURUMSAL  >></a>
        </section>
    </header>
    <!--Birinci bölüm bitişi-->
    <!--İkinci bölümün başlangıcı-->
        <div class="box-container">
            <section>
                <div class="box">
                    <div class="box-head">
                        <img src="C:\Users\PC\Desktop\image\hizmet1.png" alt="HİZMETLERİMİZ">
                    </div>
                </div>
                <div class="box">
                    <div class="box-head">
                        <img src="C:\Users\PC\Desktop\image\hizmet2.png" alt="HİZMETLERİMİZ">
                    </div>
                </div>
                <div class="box">
                    <div class="box-head">
                        <img src="C:\Users\PC\Desktop\image\hizmet3.png" alt="HİZMETLERİMİZ">
                    </div>
                </div>
            </section> 
            <div> 
            <h3>NELER YAPIYORUZ</h3>
            <h1>HİZMETLERİMİZ</h1>
            <h6>Tacirler Nakliyat ve Taahhüt ve Tic. Ltd. Ştd. Türkiye standartlarında yürüttüğü<br> Nakliyathizmet sektöründe Taşımacılıkts üztün hizmet anlayışı ve güven ilkesi ile</h6>
            </div>  
            <a href="#" class="btn">HİZMETLERİMİZ</a>
            <a href="#" class="btn"><<</a>
            <a href="#" class="btn1"><span>>></span></a>
        </div>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;900&display=swap');
:root{
    --red-color:red;
    --white-color:white;
    --border-: 0.1rem solid red;
    --border: 0.1rem solid white;

}
html{
    overflow-x: hidden;
    scroll-padding-top: 9 rem;
    scroll-behavior: smooth;
}
*{
    font-family:'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
    text-decoration: none;
    text-transform: capitalize;
    transition: 0.2s ease;
}
/*birini bölümün başlangıcı*/
section{
    padding: 7rem 7%;
}
.header{
    min-height: 100vh;
    background: url(image/TacirlerBlueRed.png) no-repeat;
    background-size: 100%;
    background-position: top;
}
.header1{
    display: flex;
    justify-content: space-between;
    padding: 0 5%;
    align-items: center;
    padding: 0.5rem;
    margin-bottom: 1rem;
    border-bottom: 0.1rem solid rgba(255, 255, 255, 0.459);
}
.header1 h5{
    color:red;
    font-size: 1rem;
    font-weight: 100;
    padding: 1rem 5%;
}
.header1 span{
    color: white;
    margin: 0 1rem;
}
.header2{
    display: flex;
    justify-content: space-between;
    padding: 0 5%;
    align-items: center;
}
.header2 .navbar a{
    margin: 0 1rem;
    font-size: 1rem;
    color: var(--white-color);
    border-bottom: 0.1rem solid var(--red-color);

}
.header2 .navbar .active,
.header2 .navbar a:hover {
    border-color: var(--white-color);
    padding-bottom: 0.5rem;
}
.header .btn{
    color: white;
    font-size: 1.4rem;
    border: 0.1rem solid var(--red-color);
    padding: 0.5rem;
}
.logo img{
    height: 2rem;
    padding-right: 1rem;
    padding-top: 3%; 
}
.logo1 img{
    height: 3rem;
}
.logo2 img{
    height: 5.5rem;
    /*css box shadow generator*/
    background-color: rgba(255, 255, 255, 0.384);
    border-radius: 100px;
    box-shadow: 0px 0px 0px 7px rgba(255, 255, 255, 0.200);
}
.home{
    color: white;
    align-items: center;
}
.home .content{
    max-width: 60rem;
}
.home .content h1{
    font-size: 6rem;
    font-weight: 600;
    color: rgba(240, 248, 255, 0.411);
}
.home .content h2{
    font-size: 6rem;
    font-weight: 600;
}
.home .content h3{
    font-size: 2rem;
    font-weight: 500;
}
.home .content p{
    font-size: 1.4rem;
    font-weight: 300;
    padding: 2rem 0;
}
.home .content h4{
    font-size: 1.4rem;
    padding: 2rem 0;
    color: aliceblue;
}
/*birinci bölümün bitişi*/
/*ikinci bölümün başlangıcı*/
.box-container{         
    height: 600px;     
    background-image: url("image/Group241.png");     
    background-size: bottom;
    position: relative;
    bottom: 37px; 
}
.box-container .box{
    width: 351px;
    height: 191px;
    float: left;
    display: block;

}
.box-container h3{
    color: white;
    font-size: 0.8rem;
    font-weight: 500;
    letter-spacing: 5px;
}
.box-container h1{
    color: white;
}
.box-container h6{
    color: white;
    font-size: 0.8rem;
    font-weight: 500;
    line-height: 2;
}
.box-container a .btn{
    color: red;
}
