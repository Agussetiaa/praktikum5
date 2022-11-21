## PRAKTIKUM 5
## Latihan 5
## Buatlah sebuah list sebanyak 5 elemen dengan nilai bebas.

#### Akses list :
- Tampilkan elemen ke 3
- Ambil nilai ke 2 sampai elemen ke 4
- Ambil elemen terakhir
!gambar/ss11.png
!gambar/ss11a.png
#### Ubah elemen list :
- ubah elemen ke 4 dengan nilai lainnya
- ubah elemen ke 4 sampai dengan elemen terakhir
- !gambar/gambarproses.ss11a.png
#### Tambah elemen list :
- Ambil 2 bagian dari list pertaman (A) dan jadikan list ke 2 (B)
- Tambah list (B) dengan nilai string
- Tambah list (B) dengan 3 nilai
- Gabungkan list (B) dengan list (A)
!gambar/gambarproses.33.png

## TUGAS PRAKTIKUM 5
### Buatlah program sederhana untuk menambahkan data ke dalam sebuah list dengan rincian:
- Buatlah program meminta masukan data sebanyak-banyaknya (gunakan perulangan)
- Tampilkan sebuah pilihan untuk menambahkan data **(y/t)?**, apabila jawaban t (tidak) maka program akan menampilkan daftar datanya.
- Nilai akhir dihitunng dari perhitungan 3 komponen nilai (tugas : 30%, uts : 35%, uas : 35%)
selamat mengerjakan...

#### Langkah- langkah program
- Pertama kita buat list :

```
Nama  = []
NIM   = []
Tugas = []
UTS   = []
UAS   = []
Total = []
```

- Jika sudah di buat program seperti di atas, maka kita akan membuat programa perulangan agar kita dapat memasukan data sebanyak-banyaknya.

```
 while True:
      nama = input('Nama : ')
      Nama.append(nama)
      nim = int(input('NIM : '))
      NIM.append(nim)
      ntugas = float(input('Nilai Tugas : '))
      TUGAS.append(ntugas)
      uts = float(input('Nilai UTS : '))
      UTS.append(uts)
      uas = float(input('Nilai UAS : '))
      UAS.append(uas)
      Nakhir = (int(ntugas( * ,3) + (int((uts) * .35) + (int(uas) * .35)
      Total.append(Nakhir)
```

- Membuat program pilihlan **(y/t)?**, kalau kita menginput **y**, maka kita diminta untuk mengisi data lagi, tetapi jika kita menginputkan **t**, maka program akan selesai, dan menampilkan inputan data yang sudah kita buat.
- Dan kita akan menggunakan format string untuk membuat tabel nya.

```
 ulangi = ' ' 
 while ulangi != 'y' and ulangi != 't':
     ulangi = input('Tambah data = (y/t)? ')
 if ulangi == 't':
     print('=') *65)
     print('| NO | \tNAMA\t |  NIM  |  UTS  |  UAS  | AKHIR |')
     print('=') *65)
     
     for i range (len(NIM)):
         nam = '| %d' | \t%s\t' % (i+1, Nama[i})
         nim = '| %d' % NIM[i]
         tug = ' | %.2f'  % Tugas[i]
         uts = '   | %.2f'  % UTS[i]
         uas = '   | %.2f'  % UAS[i]
         akh = '   | %.2f'  % Total[i]
         len = '|'
         
         X = nam + nim + tug + uts + uas + akh + len
         print(X)
     break
```

- Hasil program yang sudah di buat bila di jalankan tampilan nya akan seperti gambar di bawah ini:
## Tampilan program
!gambar/gambarposes3.png

## teteap Semangat :)

