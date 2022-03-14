# Lab1Web
###### Nama : Fara Deviana
###### NIM : 312010407
###### Kelas : TI.A.2

## TugasPertamaWebProgramming



Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lab2_css_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
5. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/

Langkah-langkah Praktikum
1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut


![](images/1%20MembuatHTMLdoc.png)



Selanjutnya buka pada brwoser untuk melihat hasilnya.

![](images/1%20first.jpg)

2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.


![](images/2%20%20DeclareCSSinternal.png)

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat
hasilnya.

Modul Praktikum Pemrograman Web

![](images/2%20second.jpg)


3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti berikut.

![](images/3%20MenambahPInlinecss.png)

Simpan kembali dan refresh kembali browser untuk melihat perubahannya.

![](images/3%20thirdnew.jpg)


4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.

![](images/4%20MenambahCSSExternal.png)

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>

![](images/5%20MenambahLink.png)

Selanjutnya refresh kembali browser untuk melihat perubahannya.
  
![](images/4%20fournew.jpg)


5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css, tambahkan kode berikut.
![](images/6%20MenambahCSSSelector.png)

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

![](images/5%20fiveneww.jpg)



Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf">

Jawaban

1.Pengantian pada font-size, font-color, font family, size dan lain lain terdapat pada gambar dibawah ini.
![](images/soal%201.png)
2.ID Selector
dideklarasikan dengan menambahkan tanda # sebelum nama id yang akan digunakan.
Kemudian pada tag HTML ditambahkan atribut id dengan value nama id tanpa menggunakan #.
Satu elemen HTML hanya dapat diberikan satu id.
Penggunaan #intro dengan menggunakan id
contoh pada id HTML id="intro"
dan pemakaian pada css #intro yang terkadang mempunyai inherent/anak pada css. 

Elemen Selector
dideklarasikan berdasarkan tag HTML.
Contoh : h1, nav, title, paragraph.

3.deklarasi utama yang akan ditampilkan ialah : inline, internal, dan eksternal.
dan untuk internal dan eksternal yang akan ditampilkan itu tergantung pada dimana yang terakhir diletakan pada html, jika penggunaan internal di atas eksternal maka link eksternal yang akan ditampilkan karena html akan memproses internal lalu eksternal yang mengakibatkan yang paling akhir yang akan di tampilkan/proses.
![](images/soal%203.png)

4.“id” bersifat unik dalam satu halaman dan hanya dapat diterapkan ke paling banyak satu elemen, sedangkan pemilih “kelas” dapat diterapkan ke beberapa elemen.
penggunaan id lebih di utamakan daripada class, karena id bersifat unik.
contoh : <id="class" class="myclass">
pada css : 
#main{
color : red;}

.myclass{
color : blue;}

maka yang akan ditampilkan adalah red yaitu id.
