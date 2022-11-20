## PRAKTIKUM 5
## Latihan 5
## Buatlah sebuah list sebanyak 5 elemen dengan nilai bebas.

#### Akses list :
- Tampilkan elemen ke 3
- Ambil nilai ke 2 sampai elemen ke 4
- Ambil elemen terakhir
!gambar/gambarproses.1.png
#### Ubah elemen list :
- ubah elemen ke 4 dengan nilai lainnya
- ubah elemen ke 4 sampai dengan elemen terakhir
- !gambar/gambarproses.22png
#### Tambah elemen list :
- Ambil 2 bagian dari list pertaman (A) dan jadikan list ke 2 (B)
- Tambah list (B) dengan nilai string
- Tambah list (B) dengan 3 nilai
- Gabungkan list (B) dengan list (A)
!gambar/gambarproses.33.png

## TUGAS PRAKTIKUM 5
### Buatlah program sederhana untuk menambahkan data ke dalam sebuah list dengan rincian:
- Buatlah program meminta masukan data sebanyak-banyaknya (gunakan perulangan)
- Tampilkan sebuah pilihan untuk menambahkan data *(y/t)?*, apabila jawaban t (tidak) maka program akan menampilkan daftar datanya.
- Nilai akhir dihitunng dari perhitungan 3 komponen nilai (tugas : 30%, uts : 35%, uas : 35%)
selamat mengerjakan...

#### Langkah- langkah program
- Pertama kita buat list :
``
NAMA  = []
NIM   = []
TUGAS = []
UTS   = []
UAS   = []
TOTAL = []
``
- Jika sudah di buat program seperti di atas, maka kita akan membuat programa perulangan agar kita dapat memasukan data sebanyak-banyaknya.
``
while True :
     nama = input('Nama : ')
     NAMA.append(nama)
     nim = int(input('NIM : '))
     NIM.append(nim)
     ntugas = float(input('TUGAS : '))
     TUGAS.append(ntugas)
     uts = float(input('UTS : '))
     UTS.append(uts)
     uas = float(input('UAS : '))
     UAS.append(uas)
     nakhir = (int(ntugas( * ,3) + (int((uts) * .35) + (int(uas) * .35)
     Total.append(nakhir)
``
- 
     
