![kode readmi 2 2](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/b767f0b2-e975-4f15-8841-6318b6e2d1d5)
# yumajulianaG1F022003
## 1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:
#![kode readmi 1 2](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/e4823816-3995-4c09-b134-6a679fa3c6a1)

### penjelasan kode 

your_name = "yuma juliana":kode ini digunakan untuk membuat variabel your_name dan diisi dengan nilai "yuma juliana".
for i in range(1, 101): kode ini digunakan untuk membuat  loop for yang digunakan untuk menjalankan iterasi dari angka 1 sampai seratus 100.
if i % 10 == 0: kode ini digunakan untuk memeriksa atau pengecekan apalah nilai i merupakan kelipatan dari 10 
Jika ya, print(your_name * 3): maka akan secara otomatis mencetak Mencetak nilai dari variabel your_name yang dilakukan sebnayak tiga kali 
Jika tidak, else: print(i, end=' '): Mencetak nilai i dengan spasi di antaranya pada baris yang sama.

## output dari kode di atas 
#![luaran readmi 1 2](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/93a827bd-d4ca-4c08-84f3-7da39737adab)

### 2. Buatlah program bebas, dengan menerapkan if else pada:
 ### a. For Loops
 ![kode readmi 2 1](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/ff28f11d-6595-47fe-908a-063726a554d8)

### penjelasan kode 

Definisi Fungsi cek_bilangan_prima(start, end): kode ini digunakan untuk menerima dua prameter yaitu star dan end yang akan menunjukkan rentang angka yang di periksa 
Perulangan Pertama: for angka in range(start, end + 1): kode ini digunakan untuk dimana loop ini akan mengiterasi dengan melalui nilai angka didalam rentang dari start sampai end 

Pengecekan Awal: if angka > 1:kode ini digunakan untuk memeriksa atau pengecekan yang dilakukan untuk memastikan apakah angka yang kurang dari satu atau sama dengan satu bukan bilangan prima  
Perulangan Kedua: for i in range(2, angka): kode ini digunakan untuk loop ini akan melakukan pengecekan atau memeriksa apakah angka bisa di bagi oleh angka lain diantara angaka 1 dan 2 jika iya maka angka bukan merupakan bilangan prima 

Pengecekan Pembagi: if (angka % i) == 0: kode ini digunakan untuk memastikan jika angka dapat dibagi oleh satu angka lain maka program akan secara otomatis akan mencetak bahwa angka itu bukanlah angka prima dan keluar dari loop menggunakan break 

Bagian else Pada Perulangan Kedua: jika loop kedua selesai tanpa menemukan angka pembagi maka program akan mencetak angka tersebut aadalah bilangan prima 
Bagian else Pada Perulangan Pertama: jika angka kurang dari satau atau sama dengan satu maka program akan mencetak angka tersebut bukan bilangan prima 

Jika angka kurang dari atau sama dengan 1, program mencetak bahwa angka tersebut "bukan bilangan prima".
 cek_bilangan_prima(1, 10):
Fungsi dipanggil dengan rentang dari 1 hingga 10  Hasilnya adalah pengecekan setiap angka dalam rentang tersebut, dan program mencetak apakah angka tersebut adalah bilangan prima atau bukan.

 ### output kode di atas 
![luaran readmi 2 1](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/42d41da5-3b93-49be-a1b5-903c67c733bb)

### b.  While Loo
![kode readmi 2 2](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/aaf39404-372d-4342-913c-35b81cfee3ac)

### penjelasana kode 

Definisi Fungsi hitung_genap_ganjil(): 
terdapat variabel  batas_bawah dan batas_atas dan telah di tetapkan masing-masing batasbawhnya 1 dan batas atasnya 6.
terdapat Variabel counter ke 1. Variabel ini digunakan untuk menghitung jumlah iterasi. Perulangan While: while counter <= 5:: ini merupakan loop yang terus berjalan selama nilai counter kurang dari satu 
Setiap iterasi dari loop ini akan menghasilkan angka acak (angka) antara batas_bawah yaitu angka satu dan batas_atas yaitu angka 6 menggunakan fungsi random.randint().
Pengecekan Bilangan Genap/Ganjil: if angka % 2 == 0:: kode ini gunakan untuk melakukan pengecekan untuk memeriksa angka genap dan angka ganjil 
Jika angka adalah bilangan genap, program mencetak bahwa itu adalah bilangan genap dan meningkatkan nilai jumlah_genap.

Bagian else pada Pengecekan Bilangan Genap/Ganjil:
Jika angka adalah bilangan ganjil, program mencetak bahwa itu adalah bilangan ganjil dan meningkatkan nilai jumlah_ganjil.
Counter dan Cetak Jumlah: pada variabel ini counter ditambah 1 setiap iterasi guna untuk menghitung jumlah iterasinya dan setelah 5 iterasi maka program akan mencetak secara otomatis berapa jumlah bilangan genap yang ada dan berapa jumlah bilangan gajilnya.
Variabel counter ditambah satu setiap iterasi untuk menghitung jumlah iterasi.
 hitung_genap_ganjil():
Fungsi dipanggil untuk mengeksekusi  dalamnya dan mencetak hasilnya. Pada setiap eksekusi, angka-angka acak kemudian dicetak apakah itu bilangan genap atau ganjil.

### output dari kode di atas 
![luaran readmi 2 2](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/616d411f-76c0-4cb5-bcce-bea7aadec064)

### 3.Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for
![kode readmi 3](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/6aa799e8-5adb-4864-b9d4-ab13a16acac0)

### penjelasan kode 
 
nama_hari = ["Senin", "Selasa", "Rabu", "Kamis", "Jumat"] kode ini digunakan untuk membuat variabel nama_hari yang merupakan list dengan elemen-elemen berupa string ("Senin", "Selasa", "Rabu", "Kamis", "Jumat").

for hari in nama_hari: adalah sebuah pernyataan loop for yang digunakan melakukan perulangan melalui setiap elemen dalam list nama_hari.
print("Hari:", hari) kode ini digunakan untuk mencetak setiap elemen dari list nama_hari dengan menambahkan awalan "Hari:".
### output dari kode di atas 
![luaran readmi 3](https://github.com/yumajuliana/yumajulianaG1F022003./assets/150018196/f6d4c998-af5c-42e0-97e2-60ded989a5bd)

