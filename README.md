# labspy02-labspy03

Nama = YUDI FERMANA

Nim = 312210321

Kelas = TI.22.A3

labspy02

Praktikum 2

Program sederhana dengan input tiga buah bilangan lalu tampilkan bilangan terbesarnya

A. Algoritma program untuk menanmpilkan bilangan terbesar dari tiga buah bilangan

1.Mulai

2.Input bil1,bil2,bil3 sebagai integer.

3.Baca bil1.

4.Baca bil2.

5.Baca bil3.

6.Jika bil1 > bil2 dan bil1 > bil3 maka kerjakan langkah 8, selain itu

7.Jika bil2 > bil1 dan bil2 > bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10.

8.Print “Bilangan Terbesar Bilangan Pertama”.

9.Print “Bilangan Terbesar Bilangan Kedua”.

10.Print “Bilangan Terbesar Bilangan Ketiga”.

11.Selesai

B. Flowchart program

![Untitled Diagram drawio (1)](https://user-images.githubusercontent.com/115516653/200246331-b1ed171b-0d43-4f1c-8e4f-fddb6c05695f.png)

D. Hasil

![praktikum2 py](https://user-images.githubusercontent.com/115516653/200246899-c9893935-17d7-402f-86b2-9e6681f70035.png)

labspy03

Latihan 1

Program Sederhana Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5

A. Algoritma Program Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5

Masukan Jumlah N perulangan

Proses perulangan sesuai jumlah perulangan yang dinputkan

Tampilkan perulangan dengan nilai di bawah 0.5

Selesai

B. Flowchart Program

![unlitid 2](https://user-images.githubusercontent.com/115516653/200247113-52d63198-eb10-4420-b0fd-6dfca7226589.png)

C. Program Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5

> Penjelasan Alur Program

1.print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5') Untuk Menampilkan atau Mencetak kalimat Tampilkan N Bilangan Acak yang Lebih Kecil Dari 0.5

2.jumlah=int(input("Masukan Jumlah N : ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat

3.import random*

4.for i in range ( jumlah ) : Untuk Pengulangan dengan range jumlah

5.print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5))) Untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5

D. Hasil

![LATIHAN-1 PY](https://user-images.githubusercontent.com/115516653/200247492-e8267fc8-4624-44aa-9ed1-b78f3c961c84.png)

Latihan 2

Program Sederhana Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan

A. Algoritma Program Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan

1.mulai

2.input bilangan N

3.Jika max < a maka akan lanjut pengulangan 4.Jika a==0 maka akan berhenti proses pengulangan

4.Dan mencetak hasil nilai maxium dari N yang di isikan

5.Selesai

Setelah anda menegetahui Algoritma Dalam sebuah Program Maka Langkah Berikutnya Kita Membuat Flowchartnya. Berikut ini Flowchart Program

B. Flowchart Program

![unlitid3](https://user-images.githubusercontent.com/115516653/200248754-e4ff8426-c1d2-441b-be68-601e3c61d3a0.png)

C. Program Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan

> Penjelasan Alur Program

print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan') Untuk menampilkan kalimat Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan

1.max= 0 kode max disini untuk menentukan nilai max nya dalah 0

2.while true: Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya

3.a=int(input("Masukan Bilangan :")) a untuk menginput tipe data interger ( bilangan bulat )

4.if max < a max=a jika max kurang dari a maka max = a

5.if a==0: break jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi

6.print("Bilangan Tebesar Adalah :", max) Menampilkan *Bilangan Tebesar Adalah : Nilai maxiumnya

D. Hasil

![lat2 py](https://user-images.githubusercontent.com/115516653/200249822-116229fb-7c24-4556-bec3-040c0b5ba536.png)

Program 1

Program Sederhana Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

A. Algoritma Program Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

1.Mulai

2.Input modal misalkan x = 20.000.000 ( deklarasikan )

3.Input presentase untung a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x

4.For i in range (len (t)) pengulangan

5.Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i])

6.Menghitung jumlah laba keseluruhan u= (a+b+c+d+e+f+g+h)

7.Print (“total laba adalah:”)

8.selesai

B. Flowchart Program1

![plowchat program1](https://user-images.githubusercontent.com/115516653/200250534-f8212ec7-3597-459b-8998-c2107babddad.png)

C. Program Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

> Penjelasan Alur Program

1.print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan') Untuk Menampilkan kalimat Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

2.x=20000000 Dengan pemisalan atau dideklarasikan x adalah 20000000

3.print (" Modal Awal:",x) Menampilkan kalimat Modal Awal : dan data yang berisi di x yaitu 20000000

4.a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 20000000

5.t=[a,b,c,d,e,f,g,h] untuk menentukan syarat t= yang berisi a,b,c,d,e,f,g,h

6.For i in range (len (t)) Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i]) untuk perulangan data dengan isi data yaitu tdengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data t

7.u= (a+b+c+d+e+f+g+h) Print (“total laba adalah:”) u berisi data penjumlahan data angka yang ada didalam kode a,b,c,d,e,f,g,h yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan

D. Hasil

![program 1 py](https://user-images.githubusercontent.com/115516653/200250762-9d704532-feca-4f22-9e7d-124ddf3ab51c.png)

sekian dari saya kurang lebihnya mohon di maafkan ,TRIMAKASIH
