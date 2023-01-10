# Phyton_IleriProglamlama- 

'''#javadaki geriye değer döndürmeyen fonksiyon.

def faktoryel(a):
    carpim = 1
    for i in range(1,a+1):
        carpim = carpim*1
    print(carpim)
    return carpim

sayi = int(input("bir sayı giriniz: "))
faktoryel(sayi)
'''  

''''import random as rnd

liste1 = []
for i in range(0,10):
    sayi=rnd.randint(0,100)
    liste1.append(sayi)

def ortalama_ustu_bul(liste1):
    toplam=sum(liste1)
    eleman_sayisi=len(liste1)
    ortalama=toplam/eleman_sayisi
    liste2=[]

    for i in range(0,eleman_sayisi):
        if liste1[i] > ortalama:
    liste2.append((liste1[i]))

        return liste2
print(ortalama_ustu_bul(liste1))
print(liste1)
'''  
'''
liste = ["geeksforgeeks", "geeky", "computers", "algoritmalar"]
aranan = str(input("bir ifade giriniz"))

def metin_ara(liste,a):
    liste1= [x for x in liste if aranan in x]
    return liste1

print(len(metin_ara(liste,aranan)))
print(metin_ara(liste,aranan))
'''
cumle = "belirli bir düzende otomatik listeler oluşturmak için liste üreteçleri kullanılır"
karakter_sayisi = int(input("karakter sayısı giriniz: "))

'''
def bul(cumle,a):

  liste=cumle.split(" ")
    print(liste)
    for i in liste:
        if len(i)>7:
            print(i)

bul(cumle,karakter_sayisi)
'''
 1-100 arası Çift Sayıları Listeleyen Python Örneği
 
 for i in range(1,101): 
 if i%2==0: 
 print(i) 
 
'''
1-100 Arası 3′ e ve 5′ e tam bölünen sayıları bulan Python Örneği

 for i in range(1,101): 
 if i%3==0 or i%5==0: 
 print(i)
 ''' 
