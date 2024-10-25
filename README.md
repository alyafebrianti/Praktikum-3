# Program Mencari Bilangan Terbesar
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.
## Deskripsi Program
Program ini dibuat menggunakan bahasa Python dengan fitur:

- Menggunakan while True untuk perulangan tak terbatas
- Menggunakan break statement untuk menghentikan program
- Membandingkan setiap input dengan nilai maksimum yang tersimpan
- Menampilkan bilangan terbesar yang ditemukan
 ## Flowchart Program
 ![Flowchart](img/FLowchart.png)
 ## Flowchart 1
 ![Flowchart](img/Flowchart1.png)

 ## Kode Programan 
```python
max = 0
bilangan = int(input("masukan bilangan :"))
while bilangan != 0 :
    if bilangan > max :
        max = bilangan
    bilangan = int(input("masukan bilangan :"))

print (f"bilangan terbesar= {max}")
```
## Kode Programan 1
```python
a = int(input ("masukan angka: "))
b = int(input ("masukan angka: "))
c = int(input ("masukan angka: "))


if a > b:
    if a > c:
        terbesar = a
    else:
        terbesar = c
else:
    if b > c:
        terbesar = b
    else:
        terbesar = c 

print (f"Bilangan Terbesar adalah {terbesar}")
```

## Contoh Output
````markdown
masukan bilangan :200
masukan bilangan :500
masukan bilangan :8999
masukan bilangan :1324
masukan bilangan :0
bilangan terbesar= 8999
````

## Contoh Output 1
````mardown
masukan bilangan :199908
masukan bilangan :8998
masukan bilangan :6765
masukan bilangan :99998
masukan bilangan :200
masukan bilangan :1000
masukan bilangan :0
bilangan terbesar= 199908
````

## Cara Kerja Program
variable max di isi dengan nilai 0, setelah itu terdapat variable inputan dengan nama bilangan, jika kondisi bilangan tidak sama dengan 0 maka cari bilangan lebih dari max dan variable max di set dengan bilangan tersebut. Jika bilangan lebih kecil dari max maka bilangan input kembali sehingga akan menghasilkan bilangan terbesar dari operasi tersebut.

