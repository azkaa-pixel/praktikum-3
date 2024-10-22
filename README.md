# Praktikum3-input data,variable,dan operator

Nama:ghefira azka fardani 

Kelas:TI.24.A5

NIM: 312410521

Mata kuliah: Bahasa Pemrograman 

## Cari bilangan terbesar dari bilangan yang di inputkan 
program ini menentukan bilangan terbesar dari serangkaian yang di inputkan hingga input 0, program ini menggunakan loop `while` dan kondisi `if` untuk memperbarui nilai terbesar  yang di temukan 
![foto](https://github.com/azkaa-pixel/praktikum-3/blob/18ccd4bb598023252666accab2c85ee399dce81e/flowchart.jpg)
## Kode program 

```Python
MAX = int('0')

while True:
    x = int(input("Inputkan Bilangan x : "))
    if x == 0:
        break
    if x > MAX:
        MAX = x
print("Bilangan terbesar adalah :", MAX)

```
## Flowchart 
```phython
MAX = int('0')
```
Variabel MAX diinisialisasi dengan 0. Ini adalah nilai awal untuk menyimpan bilangan terbesar yang ditemukan.
```phython
while True:
```
Program masuk ke dalam loop tak terbatas yang akan terus meminta input dari pengguna.
```phython
x = int(input("Inputkan Bilangan x : "))
```
Pengguna diminta untuk memasukkan sebuah bilangan yang akan disimpan dalam variabel x.
```phython
if x == 0:
    break
```
if x == 0:
    break
```phython
if x > MAX:
    MAX = x
```
Jika nilai x yang dimasukkan lebih besar dari nilai MAX yang saat ini, maka MAX akan diperbarui dengan nilai x.
```phython
print("Bilangan terbesar adalah :", MAX)
```
Setelah loop berhenti (ketika pengguna memasukkan 0), program mencetak bilangan terbesar yang telah ditemukan.


## Hasil kodingan 
![foto](https://github.com/azkaa-pixel/praktikum-3/blob/d2936cf8f3eadd6986c98f25909c1180f192e2ae/hasil%20%20codingan%20.jpg)

