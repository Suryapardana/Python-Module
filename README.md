# Pengenalan Python
![python-logo](https://user-images.githubusercontent.com/47344288/72213664-3fe11880-3525-11ea-8d36-93bf35c0dfdf.png)

Python adalah bahasa pemrograman interpretatif multiguna. Tidak seperti bahasa lain yang susah untuk dibaca dan dipahami,
python lebih menekankan pada keterbacaan kode agar lebih mudah untuk memahami sintaks. Hal ini membuat Python sangat mudah dipelajari baik untuk pemula maupun untuk yang sudah menguasai bahasa pemrograman lain.

Bahasa ini muncul pertama kali pada tahun 1991, dirancang oleh seorang bernama Guido van
Rossum. Sampai saat ini Python masih dikembangkan oleh Python Software Foundation. Bahasa
Python mendukung hampir semua sistem operasi, bahkan untuk sistem operasi Linux, hampir
semua distronya sudah menyertakan Python di dalamnya.
Dengan kode yang simpel dan mudah diimplementasikan, seorang programmer dapat lebih
mengutamakan pengembangan aplikasi yang dibuat, bukan malah sibuk mencari syntax error.

print("Follow github suryapardana")

Hanya dengan menuliskan kode print seperti yang diatas, anda sudah bisa mencetak apapun yang
anda inginkan di dalam tanda kurung (). Dibagian akhir kode pun, anda tidak harus
mengakhirnya dengan tanda semicolon ;

# Instalasi Python
Sebelum Anda menggunakan Python, Anda harus menginstalnya terlebih dahulu di sistem operasi komputer Anda. Saat ini Python memiliki 2 versi yang berbeda, yaitu Python versi 3.4.3 dan Python versi 2.7.10. Disini kita akan belajar bahasa pemrograman Python menggunakan versi terbaru 3.4.3

Cara menginstal python sangat mudah, ikuti panduan dibawah ini. Dibawah adalah panduan cara instal python di platform Linux, Windows dan Mac OS.

## 1.1 Linux
```
- Buka browser, kunjungi http://www.python.org/downloads/source/
- Download versi terbaru Python berbentuk file zip untuk Unix/Linux
- Ekstrak file zip yang baru saja di download
- Edit file Modules/Setup jika Anda ingin kostumisasi Python
- Jalankan ./configure script
- make
- make install
```
Langkah ini akan menginstal Python di lokasi standar /usr/local/bin dan library di /usr/local/lib/pythonXX dimana XX adalah versi terbaru Python yang anda gunakan.

 ## 1.2 Windows
```
- Buka browser, kunjungi http://www.python.org/downloads/windows/
- ATAU, klik direct link https://www.python.org/ftp/python/3.4.3/python-3.4.3.msi
- Buka (klik 2x) file installer python yang baru saja di download
- Ikuti langkah instalasi sampai selesai
```

##  1.3 Mac OS
```
- Buka browser, kunjungi http://www.python.org/download/mac/
- Download versi terbaru Python untuk Macintosh
- Buka file yang baru saja di download
- Ikuti langkah instalasi sampai selesa
```
# Integrated Daveloper Environment
IDE adalah sebuah software aplikasi yang memberikan Anda fasilitas bermanfaat ketik membuat program. Biasanya sebuah IDE terdiri dari source code editor build automation tool dan debugger.
Untuk menulis sebuah program, bisa menggunakan text editor atau IDE nya. Bagi yang sudah mahir, menulis program dengan text editor bukanlah menjadi masalah. Tetapi untuk pemula, akan lebih mudah menggunakan IDE. IDE untuk Python sangatlah banyak, tersedia bermacam-macam IDE dengan kelebihan dan kekurangan masing-masing.

Beberapa IDE untuk Python yang cukup populer adalah :

- Komodo
- LiClipse
- NetBeans
- PyCharm
- Kdevelop
- PyDev
- Wing IDE
- dan masih banyak lainnya

 (http://wiki.python.org/moin/IntegratedDevelopmentEnvironments).

# Menjalankan Python
Untuk menjalankan Python ada banyak cara yang bisa dilakukan. Anda bisa menggunakan sheel, terminal atau menggunakan IDE (Integrated Development Environment). Di bawah ini adalah langkah-langkah menjalankan Python dengan cara yang paling mudah.

## 2.1 Linux
- Buka terminal (Ctrl + Alt + T)
- Ketik python maka Anda akan masuk ke sheel Python. 
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit()

atau 

- Gunakan teks editor, misalnya gedit.
- Buat file baru, dan ketikan script python Anda, contoh: print("Selamat datang di Python").
- Save As dengan ekstensi .py (contoh: cetak.py).
- Jalankan file dengan menggunakan Terminal.
- Buka terminal (Ctrl + Alt + T).
- Masuk ke direktori dimana file Python Anda disimpan (contoh: cd /Users/admin/Desktop/).
- Jalankan script Python dengan menggunakan python diikuti dengan nama file (contoh: python cetak.py).
- Script Python Anda akan dieksekusi/dijalankan.

 ## 2.2 Windows

- Buka Python sheel, Anda bisa mencarinya di tombol Start.
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit()

## 2.3 Macintosh

- Buka terminal.
- Ketik python maka Anda akan masuk ke sheel Python. 
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit() atau 
- Gunakan teks editor.
- Buat file baru, dan ketikan script python Anda, contoh: print("Selamat datang di Python").
- Save As dengan ekstensi .py (contoh: cetak.py).
- Jalankan file dengan menggunakan Terminal.
- Buka terminal (Ctrl + Alt + T).
- Masuk ke direktori dimana file Python Anda disimpan (contoh: cd /Users/admin/Desktop/).
- Jalankan script Python dengan menggunakan python diikuti dengan nama file (contoh: python cetak.py).
- Script Python Anda akan dieksekusi/dijalankan.

# Syntax Dasar Python
Dibawah ini adalah contoh fungsi Python yang digunakan untuk mencetak. Di Python untuk mencetak cukup gunakan fungsi print(), dimana sesuatu yang akan dicetak harus diletakkan diantara kurung buka dan kurung tutup, bahkan di Python versi 2.x Anda tidak harus menggunakan tanda kurung kurawal, cukup pisahkan dengan spasi.
Jika ingin mencetak tipe data String langsung, Anda harus memasukanya ke dalam tanda kutip terlebih dahulu.

print("Hello World")

Saat anda menjalankan script diatas, Anda akan melihat output berupa text Hello World

# Komentar Python

Komentar (comment) adalah kode di dalam script Python yang tidak dieksekusi atau tidak dijalankan mesin. Komentar hanya digunakan untuk menandai atau memberikan keterangan tertulis pada script.
Komentar biasa digunakan untuk membiarkan orang lain memahami apa yang dilakukan script. atau untuk mengingatkan kepada programmer sendiri jika suatu saat kembali mengedit script tersebut.
Untuk menggunakan komentar anda cukup menulis tanda pagar #, diikuti dengan komentar Anda.
Dibawah ini adalah contoh penggunaan komentar pada Python.
```
#Ini adalah komentar

#Tulisan ini tidak akan dieksekusi

#komentar dengan tanda pagar hanya bisa digunakan

#untuk

#satu

#baris

print("Hello World") #ini juga komentar

#print("Welcome")

#komentar bisa berisi spesial karakter !@#$%^&*(

#mencetak nama

print("Budi")

#mencetak angka/integer

print(123)
```

Saat anda menjalankan script diatas, Anda akan melihat output berupa Hello World, Budi dan 123, karena tulisan/komentar yang ditulis tidak dieksekusi.

# Python Case Sensitive
Python bersifat case sensitif, ini artinya huruf besar dan huruf kecil memiliki perbedaan.
Sebagai contoh jika Anda menggunakan fungsi print dengan huruf kecil print() akan
berhasil. Lain hal jika anda menggunakan huruf kapital Print() atau PRINT(), akan
muncul pesan error.
Aturan ini berlaku untuk nama variabel ataupun fungsi-fungsi lainya

# Tipe Data

Tipe data adalah suatu media atau memori pada komputer yang digunakan untuk menampung informasi.

Python sendiri mempunyai tipe data yang cukup unik bila kita bandingkan dengan bahasa pemrograman yang lain.

Berikut adalah tipe data dari bahasa pemrograman Python :

| Tipe Data     | Contoh                    | Penjelasan                                                                        |
| ------------- |-------------------------- | --------------------------------------------------------------------------------- |
| Boolean       |	`True` atau `False`	    | Menyatakan benar `True` yang bernilai `1`, atau salah `False` yang bernilai `0`   |
| String        |	`"Ayo belajar Python"`  | Menyatakan karakter/kalimat bisa berupa huruf angka, dll (diapit tanda `"` atau `'`)|
| Integer       |	`25` atau `1209`        | Menyatakan bilangan bulat                                                         |
| Float         |	`3.14` atau `0.99`      | Menyatakan bilangan yang mempunyai koma                                           |
| Hexadecimal   |	`9a` atau `1d3`	        | Menyatakan bilangan dalam format heksa (bilangan berbasis 16)                     |
| Complex       |	`1 + 5j  `              | Menyatakan pasangan angka real dan imajiner                                       |
| List          |	`['xyz', 786, 2.23]`    | Data untaian yang menyimpan berbagai tipe data dan isinya bisa diubah-ubah        |
| Tuple         |	`('xyz', 768, 2.23)`    | Data untaian yang menyimpan berbagai tipe data tapi isinya tidak bisa diubah      |
| Dictionary    |	`{'nama': 'adi','id':2}`| Data untaian yang menyimpan berbagai tipe data berupa pasangan penunjuk dan nilai |

Untuk mencoba berbagai macam tipe data, silahkan coba script Python dibawah ini.
```
{% highlight python %}
#tipe data Boolean
print(True)

#tipe data String
print("Ayo belajar Python")
print('Belajar Python Sangat Mudah')

#tipe data Integer
print(20)

#tipe data Float
print(3.14)

#tipe data Hexadecimal
print(9a)

#tipe data Complex
print(5j)

#tipe data List
print([1,2,3,4,5])
print(["satu", "dua", "tiga"])

#tipe data Tuple
print((1,2,3,4,5))
print(("satu", "dua", "tiga"))

#tipe data Dictionary
print({"nama":"Budi", 'umur':20})
#tipe data Dictionary dimasukan ke dalam variabel biodata
biodata = {"nama":"Andi", 'umur':21} #proses inisialisasi variabel biodata
print(biodata) #proses pencetakan variabel biodata yang berisi tipe data Dictionary
type(biodata) #fungsi untuk mengecek jenis tipe data. akan tampil <class 'dict'> yang berarti dict adalah tipe data dictionary
{% endhighlight %}
```

---

<div class="row navigation-tutorial">
    <div class="col-md-6 prev-tutorial">
        <a href="/tutorial/komentar-python"><i class="fas fa-arrow-circle-left"></i>Komentar Python</a>
    </div>
    <div class="col-md-6 next-tutorial">
        <a href="/tutorial/variabel-python" class="hoverable">Variabel Python<i class="fas fa-arrow-circle-right"></i></a>
    </div>
</div>

