# Latihan-String
## Program akan meminta kita untuk memasukkan jumlah karakter, karakter terakhir, karakter index ke-2 sampai index ke-4, teks tanpa spasi, teks dalam huruf besar, teks dalam huruf kecil :
![output latihan string 1](https://github.com/user-attachments/assets/2971d6df-23a9-47e9-8253-99fd2ef3fe83)
## Penjelasan Code
```Python
txt = 'Hello World'

# Hitung jumlah karakternya
jumlah_karakter = len(txt)
print("Jumlah karakter:", jumlah_karakter)

# Ambil karakter terakhir
karakter_terakhir = txt[-1]
print("Karakter terakhir:", karakter_terakhir)

# Ambil karakter index ke-2 sampai index ke-4 (llo)
substring = txt[2:5]
print("Karakter index ke-2 sampai index ke-4:", substring)

# Hilangkan spasi pada teks tersebut (HelloWorld)
tanpa_spasi = txt.replace(" ", "")
print("Teks tanpa spasi:", tanpa_spasi)

# Ubah teks menjadi huruf besar
huruf_besar = txt.upper()
print("Teks dalam huruf besar:", huruf_besar)

# Ubah teks menjadi huruf kecil
huruf_kecil = txt.lower()
print("Teks dalam huruf kecil:", huruf_kecil)

# Ganti karakter H dengan karakter J
ganti_h = txt.replace("H", "J")
print("Teks setelah mengganti H dengan J:", ganti_h)
```
Penjelasan Latihan 1 : Fungsi upper() mengubah seluruh teks menjadi huruf besar. Output dari kode ini adalah "HELLO WORLD". Fungsi lower() mengubah seluruh teks menjadi huruf kecil. Outputnya adalah "hello world". Fungsi replace("H", "J") menggantikan semua kemunculan huruf H dalam teks dengan huruf J. Jadi, "Hello World" menjadi "Jello World". Fungsi len() digunakan untuk menghitung jumlah karakter dalam string txt. Hasilnya adalah jumlah semua karakter yang ada dalam teks, termasuk spasi. Output dari kode ini adalah 11, karena "Hello World" memiliki 11 karakter (termasuk spasi). Menggunakan indeks negatif -1 untuk mengakses karakter terakhir dari string. Indeks negatif dimulai dari posisi akhir string, jadi -1 adalah karakter terakhir, yang dalam kasus ini adalah d.Sintaks txt[2:5] digunakan untuk mengambil substring dari indeks ke-2 hingga ke-4. Ingat, indeks dalam Python dimulai dari 0. Jadi, karakter pada indeks 2 adalah l, indeks 3 adalah l, dan indeks 4 adalah o. Hasilnya adalah string "llo".Fungsi replace(" ", "") menggantikan semua spasi (" ") dengan string kosong (""), yang artinya menghapus semua spasi dalam teks. Hasilnya adalah "HelloWorld". Secara keseluruhan, kode ini menunjukkan bagaimana cara mengolah string di Python, seperti menghitung panjang string, mengakses karakter tertentu, memanipulasi teks, dan mengganti karakter tertentu.
## Program akan meminta kita untuk memasukkan Hello, nama saya john, dan umur saya adalah 24 tahun:
