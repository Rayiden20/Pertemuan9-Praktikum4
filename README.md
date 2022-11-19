# Pertemuan9-Praktikum4 #

Repositiry ini dibuat untuk memenuhi tugas Pertemuan 9 - Bahasa Pemrograman (Module Praktikum 4)

Nama : Rayiden Arfah

NIM : 312210127

Dosen : Agung Nugroho, M.Kom

Matkul : Bahasa Pemrograman

Kelas : TI.22.B1

Pada halaman ini (Tugas Pertemuan-9-Module Praktikum 4) Dosen memberi tugas sebagai berikut :
Ada dua bahan praktik dimodule 4 kali ini yaitu :

- Soal Latihan yang ada pada module praktikum 4
 
![WhatsApp Image 2022-11-17 at 23 06 33](https://user-images.githubusercontent.com/115732267/202497971-746d2e8d-5806-486e-9a1d-ae7ebcac512e.jpeg)

- Berikut ini saya menulis syntax sekaligus menuliskan langkah-langkahnya sebagai berikut
 
 ```python
 # membuat list
print("Buat sebuah list sebanyak 5 elemen dengan nilai bebas")
list = [1, 2, 3, 4, 5]
print(list)

# mengakses list
print("Menampilkan elemen 3")
print(list[2])

print("ambil nilai elemen 2 sampai ke 4")
print(list[1:4])

print("ambil elemen terakhir")
print(list[-1])

# mengubah elemen list
print("ubah elemen 4 dengan nilai lainnya")
list[4]=10
print(list[3])

print("ubah elemen 4 sampai dengan elemen terakhir")
list[4:5]=[20,11]
print(list)

# Tambah elemen list
print("Ambil 2 bagian dari list pertama(A) dan jadikan list ke 2(B)")
list_pertama=list[3:5]
print(list_pertama)

print("tambah list B dengan nilai string")
list_pertama.append("guest")
print(list_pertama)

print("Tambah list B dengan 3 nilai")
list_pertama.append(["guest",7,8])
print(list_pertama)

print("Menggabungkan list B dengan list A")
gabung=list_pertama+list
print(gabung)
```
![1](https://user-images.githubusercontent.com/115732267/202510048-bca6a03b-a448-47f9-a172-7347a816a37f.png)

![2](https://user-images.githubusercontent.com/115732267/202510130-eb59b532-6afc-4993-a781-f6152eb21f4c.png)


- Berikut hasil run syntax untuk memenuhi latihan module 4 diatas :

![3](https://user-images.githubusercontent.com/115732267/202510666-16fc20da-c55e-404b-8ad6-2f370ebb70e8.png)

- Soal Tugas praktikum module 4

![image](https://user-images.githubusercontent.com/115732267/202511040-1e005be2-5f99-468b-9f0a-18d891f4948a.png)

- Pada soal tugas ini saya akan menulis dan menjelaskan syntax yang saya buat sebagai berikut

```python
print("===================================================================")
print("Nama         :   Rayiden Arfah")
print("NIM          :   312210127")
print("Kelas        :   TI.22.B1")
print("Mata Kuliah  :   Bahasa Pemrograman")
print("===================================================================")
print("Tugas Praktikum module 4")

# Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut: • Progam meminta
# memasukkan data sebanyak-banyaknya (gunakan perulangan) • Tampilkan pertanyaan untuk menambah data (y/t?),
# apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya. • Nilai Akhir diambil dari perhitungan 3
# komponen nilai (tugas: 30%, uts: 35%, uas: 35%) • Buat flowchart dan penjelasan programnya pada README.md. • Commit
# dan push repository ke github.

from prettytable import PrettyTable

baris = []
stop = False

# masukan nilai
while (not stop):
    nama = input("Masukan Nama : ")
    nim = input("Masukan NIM : ")
    tugas = input("Masukan Nilai Tugas : ")
    uts = input("Masukan Nilai UTS : ")
    uas = input("Masukan Nilai UAS : ")
    nilai_akhir = 0.3 * float(tugas) + 0.35 * float(uts) + 0.35 * float(uas)
    baris.append([nama, nim, tugas, uts, uas, nilai_akhir])

    tanya = input("Tambah data? (y/n) : ")
    if (tanya == "n"):
        stop = True

# cetak nilai
print("===================================================================")

x = PrettyTable()
no = 0

for isi in baris:
    no += 1
    x.field_names = ["No", "Nama", "Nim", "Tugas", "UTS", "UAS", "Nilai Akhir"]
    x.add_row([no, isi[0], isi[1], isi[2], isi[3], isi[4], isi[5]])
print(x)
```

![5](https://user-images.githubusercontent.com/115732267/202841251-3ec2cada-754a-4183-906c-8a3036f23f02.png)

![6](https://user-images.githubusercontent.com/115732267/202841324-0210df24-2746-46e3-838d-ba2f22362463.png)

Berikut hasil run syntax yang saya buat untuk memenuhi praktikum module 4 :

![4](https://user-images.githubusercontent.com/115732267/202841353-476cea4f-b3c5-4266-8bfc-be70a152f735.png)

- Flowchart program diatas adalah sebagai berikut :

![image](https://user-images.githubusercontent.com/115732267/202841403-e558030e-0e69-4559-a32a-1ae46314ff4c.png)

# Berikut langkah-langkah "Tugas Pertemuan 9 Module 4" yang bisa saya jelaskan/jabarkan

# Thanks You

# Rayiden Arfah





















