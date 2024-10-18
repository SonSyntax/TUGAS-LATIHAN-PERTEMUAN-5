# TUGAS-LATIHAN-PERTEMUAN-5
  ## BIODATA
  <p>NAMA : MOHAMAD SONY HIDAYATULLAH</p>
  <p>KELAS : TI 24 A 4</p>
  <p>NIM : 312410290</p>
  <p>MATKUL : BAHASA PEMROGRAMAN</p>

## TUGAS LATIHAN 
![ssTugaslatihan](https://github.com/user-attachments/assets/73d90a5f-3d61-4756-a812-177fc694c4a7)

#### PRAKTIKUM 3
## LATIHAN 1
![sslatihan1p3](https://github.com/user-attachments/assets/c55fed7a-d5c7-4d5a-8cd4-f6f93ef8ed8a)
<p>Pembahasan Mengenai :</p>
<p># Penggunaan End</p>
<p># Penggunaan Separator</p>
<p># String Format</p>

## PENGGUNAAN END
![sspenggunaanendlatihan1p3](https://github.com/user-attachments/assets/2bf9fa7a-756c-49eb-95ad-c3b2f0d11b36)
```Python
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
````
Parameter `end` dalam fungsi `Print()` di python digunakan untuk menambahkan string `(" ")` apapun diakhir dan mengeluarkan pernyataan Print
```Python
print()
````
Secara Default, fungsi `print()` akan mengakhiri dengan baris baru, dan akan secara otomatis menambahkan karakter baris baru di akhir Outputnya
<P>ini hasil program tersebut :</p>

![sshasilpenggunaanlatihan1p3](https://github.com/user-attachments/assets/e1269cc5-7a35-46e1-9769-510bf9a35d4d)

<p>dan ini hasil tanpa menggunakan fungsi `print()` di tengah pada kode program di atas :</p>

![hasilbaru](https://github.com/user-attachments/assets/a2775246-1374-4d7d-a64c-d67a4592309b)

## PENGGUNAAN SEPARATOR
![PenggunaanSeparator](https://github.com/user-attachments/assets/2ff0ca65-d1c7-45b0-8ab9-74c2e3bca8f3)

```Python
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
````
Pada python penggunaan Separator dapat menggunakan Fungsi `split()` atau `sep` yang seperti dalam kode program diatas
<p>Separator ini menentukan pembatas yang digunakan untuk memisahkan string, separator dapat berupa karakter tunggal atau beberapa karakter.Jika tidak ditentukan, maka python akan menggunakan spasi sebagai pemisah.</p>
<p>Berikut Hasil Kode Program diatas : </p>

![hasilbaru2](https://github.com/user-attachments/assets/10aeb6fc-4f8d-4007-89c3-6c97aa7a7f73)

```Python
w, x, y, z = 10, 15, 20, 25
````
Variable yang seperti ini menentukan parameter, jadi variable ini tidak bisa memasukan variable huruf melainkan variable angka yang sudah ditentukan w = 10, x = 15,
y = 20, z = 25
```Python
print(w, x, y, z)
````
fungsi ini hanya mencetak saja yang menggunakan fungsi `print()`, tetapi di karenakan mencetak parameter, koma tersebut dihilangkan 
```python
print(w, x, y, z, sep=',')
````
karna pemisahnya dihilangkan kita memakainya fungsi `sep=','` untuk membuat pemisah yaitu `(,)` koma di kode program ini
<p>dan kode program seterusnyapun begitu menggunakan fungsi `sep` atau `split()` dan kita memasukan pemisahnya didalam string akan memunculkan cetakkan yang sesuai keinginan anda dalam memisahkan sesuatu parameter</p>

## STRING FORMAT
![stringformat](https://github.com/user-attachments/assets/1b64d016-ee87-425d-baec-da0ff9932b64)

```Python
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10)) 
````
String Format adalah proses memasukkan variable atau string kustom ke dalam teks yang sudah ditentukan, dan dapat digunakan untuk berbagai keperluan, seperti memasukkan judul dalam grafik, menampilkan pesan atau kesalahan, atau meneruskan kesalahan ke suatu fungsi.

```python
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
````
Nilai pertama dalam setiap pasangan adalah angka dari 0 hingga 10, kode program ini dihitung dengan menggunakan operasi pangkat atau fungsinya `(**)` untuk menaikkan 10 ke pangkat yang sesuai dengan angka pertama, yang bisa di bahasa manusiakan variable 0 = 10 pangkat 0, variable 1 10 pangkat 1 dan seterusnya hingga variable 10 yaitu 10 pangkat 10, dan di cetak dengan fungsi `print()`

```Python
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````
Kode inimencetak 11 baris dengan format `{0:3}` `{1:16}` yang di gunakan untuk mengatur format string
<p>Pada string pertama, angka `0` di format untuk memeliki lebar 3 karakter atau yang bisa disebut 3 kali spasi dengan perataan kanan.</p>
<p>angka 1 diformat untuk memiliki lebar 16 Karakter atau 16 kali spasi dengan perataan kanan, dan masing-masing mencetak nilai seperti format di atas dengan fungsi `print()`</p>

## KODE PROGRAM 
### 3 INPUT BILANGAN
```Python
a = int(input("masukan angka pertama: "))
b = int(input("masukan angka kedua: "))
c = int(input("masukan angka ketiga: "))

if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
elif b > a and b > c:
    print(f"angka lebih besar adalah {b}")
else:
    print(f"angka lebih besar adalah {c}")
````
Program ini akan menginputkan 3 bilangan dari yang a sampai dengan c.
```Python
if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
````
 Karna Jika {a} lebih besar dari {b} dan {a} lebih besar dari {c}, output yang keluar adalah {a}
 ```Python
elif b > a and b > c:
    print(f"angka lebih besar adalah {b}")
````
dan jika {b} lebih besar dari {a} dan {b} lebih besar dari {c} maka output yang keluar adalah {b}
```Python
else:
    print(f"angka lebih besar adalah {c}")
````
Jika inputan yang diatas lebih kecil dari {c} maka output {c} yang akan keluar
<p>Ini adala hasil program tersebut :</p>

![input3bil](https://github.com/user-attachments/assets/b663a7b1-cbfc-47f9-b02e-2f6e661c1fb3)

<p>dengan eksekusi program :</p>

![ssfullekseusi3bil](https://github.com/user-attachments/assets/41cdbffe-aaff-40b6-a77a-8ba5a4dbc412)

<p>dan flowchart sebagai berikut : </p>

![flow3bil](https://github.com/user-attachments/assets/e78cf387-c05a-484a-a6e8-3c1cd627ee54)

### MENENTUKAN BILANGAN TERBESAR DARI N DAN BERIKAN ANGKA 0
```Python
max = 0

while True:   
    N = int(input("masukan angka: "))

    if N == 0:
        print(f"{max}")
        break
    if N > max:
        max = N
````
