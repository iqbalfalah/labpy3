***labpy3***

# latihan
``` python
import random
n=str(input("masukan nilai N: "))
for x in range (1,6):
 print("data ke:",x,"=>",random.uniform(0.0,0.5))
print('selesai')
```

# penjelasan algoritma
- [x] masukan nilai N =5
- [x] gunakan for range (untuk mengulang data dari 1-5)
- [x] cetak data dan memasukan (random.uniform kurang dari 0.5)
- [x] jika selesai RUN/jalankan programnya.

# output:

![image](https://user-images.githubusercontent.com/46512186/52991826-f8e7c180-3440-11e9-96fd-5ad34e40e260.png)


# latihan2
 ```python
max=0
while True:
	a=int(input("masukan bilangan:"))
	if a ==0:
		break
	if a>max:
		max=a
print("bilangan terbesar:",max)
```

# penjelasan algoritma
- [x]  Fungsi max di pemrograman python Fungsi max() adalah fungsi bulid-in untuk mencari nilai tertinggi. Fungsi ini dapat diberikan  sebuah parameter berupa angka.
- [x]  Perulangan while Perulangan while disebut uncounted loop (perulangan yang tak terhitung), yaitu perulangan yang dilakukan     berdasarkan kondisi tertentu selama nilai kondisi bernilai TRUE.
- [x]  Break, pernyataan break digunakan untuk menghentikan proses perulangan pada kondisi tertentu.

# output :

![image](https://user-images.githubusercontent.com/46512186/52992068-cdb1a200-3441-11e9-8f51-767236e39f8a.png)


# program1
```python
a = 100000000

for x in range(1,9):
    if(x>=1 and x<=2):
        b =a*0
        print("Laba Bulan ke-",x," :",b)
    if(x>=3 and x<=4):
        c=a*0.1
        print("Laba Bulan ke-",x," :",c)
    if(x>=5 and x<=7):
        d=a*0.5
        print("Laba Bulan ke-",x," :",d)
    if(x==8):
        e=a*0.2
        print("Laba Bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total) 
```

# penjelasan algoritma
- [x] Perulangan for Perulangan for disebut juga sebagai counted loop (perulangan yang terhitung), yaitu perintah yang dieksekusi secara berulang berdasarkan jumlah perulangan tertentu.
- [x] Menggunakan kondisional if Seperti halnya bahasa pemrograman yang lain, bahasa python juga mempunyai percabangan berupa if yaitu bila suatu kondisi tertentu tercapa maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu.

# output :
