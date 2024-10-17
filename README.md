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








