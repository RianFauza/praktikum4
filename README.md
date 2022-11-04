## latihan 1

pertama-tama kita buat input terlebih dahulu contohnya seperti dibawah ini:
```
x = int(input('masukan bilangan pertama : '))

y = int(input('masukan bilangan kedua : '))
```
lalu kita enter, masukan if untuk menjalani program yang sebelumnya dan tambahkan x > y : lalu print('Bilangan terbesar = ', x)

lalu tambahkan else untuk menambah aksi untuk menentukan bahwa x lebih besar dari y 

 else :
 
      print('Bilangan terbesar = ', y)
      
dan saat running kita diminta untuk memasukan bilangan pertama lalu bilangan kedua,      
lalu hasil runing nya seperti gambar berikut:

![gambar](gambarlab4/rid1.png)

## latihan 2

mula-mula kita buat input terlebih dahulu contohnya seperti dibawah ini:
```
a = int(input('bilangan ke-1 = '))

b = int(input('bilangan ke-2 = '))

c = int(input('bilangan ke-3 = '))
```
lalu tambahkan 
```
if a < b:

    if b < c:
    
        print('urutan bilangan : ', a, b, c)
        
    else:
    
        print('urutan bilangan : ', c, a, b)
        
else:

    if a < c:
    
        print('urutan bilangan : ', b, a, c)
        
    else:
    
        if b < c:
        
            print('urutan bilangan : ', b, c, a)
            
         else:
         
            print('urutan bilangan : ', c
```            
dan saat runing kita sebut bilangan yang inin kita ururkan 
lalu hasil runing nya seperti gambar berikut:

![gambar](gambarlab4/rid2.png)

## latihan 3

mula-mula kita buat koddinagnnya dulu seperti berikut:
```
for i in range(0, 10):

    for j in range(0, 10):
    
        product = i+j
        
        print(f"{product:>3}", end='')
    print()

x = input("masukan angka :")

if x > y:

    print(x, "y")
```    
print("ini diluar pernyataan if")

maka runingannya akan seperti gambar berikut:

![gambar](gambarlab4/rid3.png)

## latihan 4

mula-mula kita buat koddinagnnya dulu seperti berikut:
```
import random

n = int(input("masukan nilai N : "))

for i in range(n):

    a = random.uniform(0.0, 0.5)
    
    print("data ke :", i+1, "=> ", a)
    
    print('sahrul ridwamsyah')
```    
setelah runing akan diminta masukan nilai n, disini saya memasukan nilai n-nya 12
dan hasil runningannya akan seperti gambar berikut:

![gambar](gambarlab4/rid4.png)

## latihan 5

![gambar](gambarlab4/rid5.png)

jadi masukan x, y, z sebagai inputan untuk memasukan bilangan
lalu tambahkan if menandakan bahwa x lebih besar dari z lalu tambahkan titik dua 
jadi seperti ini
If  x > z:
lakukan juga pada x dan y lalu print dan ketik masukan bilangan terbesar,
lalu selanjutnya tambahkan elif, elif sama dengan else yaitu untuk menambah aksi untuk menentukan bahwa x lebih besar dari z dan y lebih besar dari z,
setelah menjalani codingan sperti penjelasan dan gambar di atas lalu runing

![gambar](gambarlab4/rid6.png)

setelah runing masukan bilangan dari yangterbesar hingga terkecil hingga hasil akhirnya menunnjukan bilangan terbesar dari tiga bialangan yg di sebut

## latihan 6

![gambar](gambarlab4/rid7.png)

pertama-tama kita print dan masukan nama kita 
lalu masukan n, =, dan 1, lalu enter dan masukan a, =, dan 0. jadi keliahatnnya seprti ini:
```
n=1
a=0
```
fungsi nya adalah untuk menentukan nilai terbesar, lalu enter dan tambahkan while n, !, =, 0, dan :. setelah itu enter, nah pas saat enter pastikan tidak sejajar dengan while, setelah itu tambahkan if n, >, a, dan : enter lalu tambahkan a = n, kemudian enter tambahkan n dan = lalu input ketik masukan bilanagan gunakan (, :, dan " sebagai syntax nya, lalu lanjut enter dan tambahkan if, n, ==, 0, dan : enter dan masukan break tidak sejajar dengan if, enter masukan prinan sperti sbmnya bedanya tambahkan a. jadi keliatannya seperti ini:
```
while n !=0:

    if n > a:
        a = n
    n = int(input("masukan Bialangan: "))
    
    if n == 0:
        break
    print("Nilai terbesarnya adalah:", a)
```
fungsinya adalah memasukan niali terbesar.

![gambar](gambarlab4/rid8.png)

setelah runnuing dari hasil kodingan di atas lalu masukan bilangan terbesar lalu enter dam asukan nilai yang lebih kecila kemudian enter lagi dan akan menentukan nilai terbesarnya.

## latihan 7

![gambar](gambarlab4/rid9.png)

gunanya menambahkan kodingan sperti diatas adalah untuk menghitung laba dari bulan kesatu hingga ke 8

![gambar](gambarlab4/rid10.png)
