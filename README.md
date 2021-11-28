# Tugas-pemograman
# adam
# tugas program
# program sederhana
# Program Python Nilai Data Mahasiswa, Tugas, UTS, UAS
# latihan
Buat sebuah list sebanyak 5 elemen dengan nilai bebas
![image](https://user-images.githubusercontent.com/92682351/143780308-df0b09b6-3ecd-493b-a6c3-6b5a74b0e35b.png)
![image](https://user-images.githubusercontent.com/92682351/143780323-199bdcc5-7b19-4205-8e0a-a9eda347f283.png)
# Tugas Praktikum
Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut:
![image](https://user-images.githubusercontent.com/92682351/143780444-0e05b115-cc13-4c67-ae6a-aa9ab2de7cd0.png)
Latihan 1: Membuat Program dengan List
Untuk memantapkan pemahaman, silahkan coba latihan berikut.

Buat sebuah list untuk menyimpan kenalanmu
Isi list sebanyak 5
Tampilkan isi list indeks nomer 3
Tampilkan semua teman dengan perulangan
Tampilkan panjang list
Mari kita coba…

# Buat list untuk menampung nama-nama teman
my_friends = ["Anggun", "Dian", "Agung", "Adi", "Adam"]

# Tampilkan isi list my_friends dengan nomer indeks 3
print "Isi my_friends indeks ke-3 adalah: {}".format(my_friends[3])

# Tampilkan semua daftar teman
print "Semua teman: ada {} orang".format(len(my_friends))
for friend in my_friends:
    print friend
Pada kode di atas, kita menggunakan fungsi len() untuk mengambil panjang list.

Hasil outputnya:

Isi my_friends indeks ke-3 adalah: Adi
Semua teman: ada 5 orang
Anggun
Dian
Agung
Adi
Adam
Mengganti Nilai List
List bersifat mutable, artinya isinya bisa kita ubah-ubah.

Contoh:

# list mula-mula
buah = ["jeruk", "apel", "mangga", "duren"]
# mengubah nilai index ke-2
buah[2] = "kelapa"
Maka "mangga" akan diganti dengan "kelapa".

["jeruk", "apel", "kelapa", "duren"]
Menambahkan Item List
Tedapat Tiga metode (method) atau fungsi yang bisa digunakan untuk menambahkan isi atau item ke List:

prepend(item) menambahkan item dari depan;
append(item) menambahkan item dari belakang.
insert(index, item) menambahkan item dari indeks tertentu
Prepend dan Append
Contoh:

#list mula-mula
buah = ["jeruk", "apel", "mangga", "duren"]
# Tambahkan manggis
buah.append("manggis")
Hasilnya "manggis" akan ditambahkan setelah item terakhir.

["jeruk", "apel", "mangga", "duren", "manggis"]
Metode yang kedua menggunakan prepend().

Metode prepend() akan menambahkan item dari depan atau awal list.

Contoh:

#list mula-mula
buah = ["jeruk", "apel", "mangga", "duren"]
buah.prepend("anggur")
Maka "anggur" akan ditambahkan pada awal list.

["anggur","jeruk", "apel", "mangga", "duren"]
Selain prepend() dan append() kita juga bisa mengginakan method insert() untuk menambahkan item pada indeks tertentu.

Menambahkan item dengan method insert
Contoh:

#list mula-mula
buah = ["jeruk", "apel", "mangga", "duren"]
buah.insert(2, "duren")
Latihan 2: Membuat Program dengan List
Sekarang mari kita coba membuat program dengan memanfaatkan method prepend() dan append().

Silahkan langsung di ketik dan dicoba.

# Membuat list kosong untuk menampung hobi
hobi = []
stop = False
i = 0

# Mengisi hobi
while(not stop):
    hobi_baru = raw_input("Inputkan hobi yang ke-{}: ".format(i))
    hobi.append(hobi_baru)

    # Increment i
    i += 1
    
    tanya = raw_input("Mau isi lagi? (y/t): ")
    if(tanya == "t"): 
        stop = True


# Cetak Semua Hobi
print "=" * 10 
print "Kamu memiliki {} hobi".format(len(hobi))
for hb in hobi:
    print "- {}".format(hb)
Coba eksekusi dan inputkan sebuah nilai.

petanikode@imajinasi ~ $ python hobi.py 
Inputkan hobi yang ke-0: Membaca
Mau isi lagi? (y/t): y
Inputkan hobi yang ke-1: Menulis
Mau isi lagi? (y/t): y
Inputkan hobi yang ke-2: Main Game
Mau isi lagi? (y/t): y
Inputkan hobi yang ke-3: Ngoding
Mau isi lagi? (y/t): t
==========
Kamu memiliki 4 hobi
- Membaca
- Menulis
- Main Game
- Ngoding

sampai sini tugas ini, kurang lebihnya mohon dimaafkan wassalamualaikum warohmatullahi wabarokatuh
