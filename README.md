# praktikum3-input data,variable,dan operator

nama:ghefira azka fardani 

kelas:TI.24.A5

NIM:

mata kuliah 

## cari bilangan terbesar dari bilangan yang di inputkan 
program ini menentukan bilangan terbesar dari serangkaian yang di inputkan hingga input 0, program ini menggunakan loop `while` dan kondisi `if` untuk memperbarui nilai terbesar  yang di temukan 
![foto](https://github.com/azkaa-pixel/praktikum-3/blob/fe45bc5b407f83829fd02cd7a80cf235a53cf292/hasil%20%20codingan%20.jpg)
## kode program 

```Python
MAX = int('0')

while True:
    x = int(input("Inputkan Bilangan x : "))
    if x == 0:
        break
    if x > MAX:
        MAX = x
print("Bilangan terbesar adalah :", MAX)


## penjelasan kode program
```phython
Inisialisasi Variabel MAX:

python
Copy code
MAX = int('0')
Variabel MAX diinisialisasi dengan 0. Ini adalah nilai awal untuk menyimpan bilangan terbesar yang ditemukan.
