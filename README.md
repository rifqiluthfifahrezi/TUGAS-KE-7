Tugas-ke-7 Nama : Rifqi Luthfi Fahrezi

NIM : 312210685

Kelas : TI.22.A1

DAFTAR ISI No Description Link 1 Lab 2 : Struktur Kondisi Click Here 2 Lab 3 : Perulangan Click Here 3 Labpy02 Click Here 4 Labpy03 Click Here 5 Author : Yoga Pratama Click Here KONDISI DAN PERULANGAN Lab 2 Struktur Kondisi Latihan 1 • Buat program sederhana dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if!

Langkah - langkah

Buat programnya terlebih dahulu seperti gambar di bawah ini Lat 1 kondisi

menentukan bilangan
print('Menentukan bilangan terbesar dari 2 bilangan') a = int(input("Masukkan nilai A:")) b = int(input("Masukkan nilai B:")) if a > b: print("A =", a, "yang terbesar") elif b > a: print("B=", b, "yang terbesar") Hasil Run Run lat 1 kondisi

Latihan 2 • Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

Langkah - langkah

Buat programnya terlebih dahulu seperti gambar di bawah ini Lat 2 kondisi

print("Mengurutkan bilangan dari yang terkecil ke yang terbesar") print("Masukan 3 bilangan yang akan diurutkan:") a = int(input("masukkan bilangan 1 = ")) b = int(input("masukkan bilangan 2 = ")) c = int(input("masukkan bilangan 3 = "))

if a < b and a < c: if b < c: print(a, b, c) else: print(a, c, b) elif b < a and b < c: if a < c: print(b, a, c) else: print(b, c, a) else: if a < b: print(c, a, b) else: print(c, b, a) Hasil Run Run Lat 2 kondisi

Lab 3 Perulangan Latihan 1 • Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:

tugas

Langkah - langkah

Buat programnya terlebih dahulu seperti gambar di bawah ini Lat 1 perulangan

for i in range(0,10): print() print(i, end="\t") for j in range(1,10): print(i+j,end="\t") Hasil Run Run lat 1 perulangan

Latihan 2 • Tampilkan n bilangan acak yang lebih kecil dari 0.5.

• nilai n diisi pada saat runtime

• anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

Langkah - langkah

Buatlah programnya terlebih dahulu seperti gambar dibawah ini Lat 2 perulangan

from random import random

n = int(input("Masukan Beberapa perulangan : ")) while n == n: break for i in range(n): bil = random() % 0.5 print("Perulangan ke : ", bil) Hasil Run Run lat 2 perulangan

MODUL PRAKTIKUM 2 DAN 3 Labpy02 dan Labpy03 Labpy02 • Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement if.

Langkah - langkah

Buatlah flowchart dari mencari angka terbesar dari 3 bilangan seperti gambar dibawah ini Flowchart program mencari angka terbesar

Buatlah program codenya seperti gambar dibawah ini Mencari angka terbesar dari 3 bilangan

a, b, c = ( int(input('Masukkan nilai a: ')), int(input('Masukkan nilai b: ')), int(input('Masukkan nilai c: ')) ) if a > b and a > c: print('A yang terbesar') elif b > a and b > c: print('B yang terbesar') else: print('C yang terbesar') Hasil dari Run Run Mencari angka terbesar dari 3 bilangan

Labpy03 Latihan 1 Flowchart dari latihan 1

Floawchart lat 1 labpy03

Algoritma dari latihan 1 Menampilkan n bilangan acak yang lebih kecil dari 0,5, nilai n diisi pada saat runtime.

1.Memasukan/ import fungsi RANDOM terlebih dahulu

2.Deklarasi integer , masukkan jumlah n :

3.Memasukan deskripsi kombinasi for untuk menyelesaikannya.

4.Memasukan nilai jumlah (n) : 5

5.Mencetak data ke 1 sampai 5 dengan hasil nilai kurang dari 0,5.

6.Selesai

Langkah - langkah

Buat program caodenya seperti gambar dibawah ini Lat 1 labpy03

print("bilangan acak yang lebih kecil dari o.5") import random

n = int(input("masukan nilai:")) a = 0 for c in range(n): a += 1 b = random.uniform(.0, .5) print("data ke:", a, "==>", b)

print("selesai") Hasil Run Run lat 1 labpy03

Latihan 2 Flowchart dari latihan 2

Flowchart lat 2 labpy03

Algoritma latihan 2 Membuat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan.Masukkan angka 0 untuk berhenti

1.Mulai

2.Mencetak "latihan 2"

3.Mencetak "menampilkan bilangan, berhenti ketika bilangan 0, menampilkan bilangan terbesar"

4.integer max = 0

5.Menggunakan fungsi perulangan while true, hingga menampilkan perulangan sampai batas tertentu.

6.Memasukan bilangan integer pada "a"

7.Menggunakan fungsi if jika max kurang dari nilai a, maka max sama dengan a

8.Mengunakan fungsi if jika nilai a adalah 0 maka fungsi break artinya perulangan berhenti jika menulis nilai 0.

9.Mencetak nilai paling terbesarv setelah break, sehingga menampilkan nilai terbesar diantara bilangan tersebut dalam perulangan.

10.Selesai

Langkah - langkah

Buatlah program code seperti gambar dibawah ini Lat 2 labpy03

print("menampilkan bilangan, berhenti ketika bilangan 0, dan menampilkan bilangan terbesar")

max = 0 while True: angka = int(input("masukan bilangan : ")) if max < angka: max = angka if angka == 0: break print("bilangan terbesarnya adalah = ", max) print("======selesai======") Hasil Run Run lat 2 labpy03

Program 1 Flowchart dari program 1

Flowchart Program 1

Algoritma dari program 1 1.Mulai

2.Mencetak latihan1

3.Mencetak "Program menghitung laba dengan modal awal 100 juta"

4.Membuat Note

5.Mencetak Bulan pertama dan kedua = 0%

6.Mencetak bulan ke 3 = 1%

7.Mencetak bulan ke 5 = 5%

8.Mencetak bulan ke 8 = 2%

9.integer a = 100.000.000( modal awal)

10.Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan bulan 1 sampai bulan 8.

11.Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai 8

12.bulan pertama dan kedua laba adalah 0

13.bulan ke 3 dan ke 4 mendapat laba 1% sehingga modal di kali 1% = keuntungan

14.bulan ke 5 mendapatkan laba 5%, sehingga modal dikali 5% = keuntungan

15.Bulan ke 8 mmendapatkan laba 2% sehingga keuntungan menurun dari bulan sebelumnya, modal dikali 2% = keuntungan.

16.Menghitung jumlah total laba dengan menjumlah keuntungan dari bulan ke 1 sampai bulan 8, hasilnya adalah total keuntungan yang didapat.

17.Selesai

Langkah - langkah

Buatlah program codenya seperti gambar dibawah ini Program 1

x = 100000000 sum = 0 y = 0 lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2] print("modal awal seorang pengusaha :', x") for i in lb: sum = sum + i y += 1 print("#laba bulan ke - ", y, "sebesar :", i)

print("  TOTAL LABA YANG DIDAPAT ADALAH :", sum)
Hasil Run Run Program 1

Sekian penjelasan dari saya Terima Kasih

Author Rifqi Luthfi Fahrezi
