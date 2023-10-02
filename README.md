# Lab2Web
# Lab2Web
## Langkah-langkah Praktikum

### Membuat CSS Dasar
### 1. Buatlah dokumen HTML serperti berikut

![Gambar 1](image/1.png)
<p>
<p>

#### Selanjutnya run program dan akan lansung menuju ke browser untuk melihat hasilnya
![Gambar 2](image/2.png)
<p>
<p>

### 2.  Mendeklarasikan CSS Internal
#### Kemudian tambahkan deklarasi css internal seperti di gambar berikut
<p>
<p>

![Gambar 3](image/3.png)
<p>
<p>

#### Selanjutnya simpan perubahan, dan lakukan run lagi untuk melihat hasilnya

![Gambar 4](image/4.png)


### 3. Menambahkan Inline CSS
#### Kemudian tambahkan deklarasi inline CSS pada tag `<p>` seperti berikut. <p>
`<p style="text-align: center; color: #ccd8e4;">`
<p> 

#### Simpan kembali dan refresh kembali browser untuk melihat perubahannya
<p>

![Gambar 5](image/5.png)
<p>
<p>

### 4. Membuat CSS Eksternal
#### Buat file baru terlebih dahulu dengan nama `style_.css` kemudian bautlah deklarasi CSS seperti berikut
<p>
<p>

![Gambar 6](image/6.png)
<p>
<p>

Kemudian tambahkan tag `<link>` untuk menuju file css yang sudah dibuat pada bagian `<head>`
<p>

`<head>`

`<!-- menyisipkan css eksternal --> <link rel="stylesheet" href="style_eksternal.css" type="text/css">`

`<head>`
 
### 5. Menambahkan CSS Selector
#### Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. buka kembali file `style_eksternal.css` dan tambahkan command seperti yang ada pada gambar berikut
<p>
<p>

![Gambar 7](image/7.png)
<p>
<p>

#### Kemudian simpan kembali dan run untuk melihat hasil perubahannya
![Gambar 8](image/8.png)

#### Pertanyaan 
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

#### Jawaban
