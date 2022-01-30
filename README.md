# merhaba_kodlama


"""İSİMİ SATIR ATLAYA ATLAYA KELİME OLARAK TERSDEN YAZAN KOD"""

name=input("İsminizi girriniz:")
for i in range(7,0,-1):
    print(name[i-1])
 
 
"""İSİMİ TERSDEN YAZAN KOD"""

x=input("name:")
for i in reversed(x):
    print(i,end="")
    
    
"""iki sayının toplamının oranını bulan kod"""

a=8
b=5
a=int(input("please enter your a :"))
b=int(input("please enter your b :"))
average=(a+b)/2
print("average=", average)

