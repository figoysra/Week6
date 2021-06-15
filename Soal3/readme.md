# Algoritma dan Soal Flowchart Soal 1

```
Mengubah Kata

Diberikan sebuah kata Surabaya, ubah huruf “a” pada kata tersebut menjadi huruf “o”,
Sehingga output nya menjadi Suroboyo
```
**Flowchart**

![](./soal%20ketiga.jpg)

**Algoritma**

1. Mulai 
2. Inputkan teks "Surabaya"
3. Masukan teks tsb ke variabel input, buat variable temp dan juga buat variable ouput
4. Hitung banyaknya karakter di teks tsb dan masukan ke variable x
5. Cek nilai variable x apakah lebih besar dari 0
6. Jika **True** (nilai variable x lebih besar dari 0), cek apakah karakter tersebut merupakan karakter huruf ***a***
7. Jika Karakter tsb ***bukan (false)*** karakter huruf a Tampilkan karakter berdasarkan urutan nilai dari variable x dan masukan ke variable temp
8. Setelah itu kurangi 1 nilai variable x dan ulangi step ke 5
9. Jika Karakter tsb ***merupakan (true)*** karakter huruf a tampilkan nilai variable temp, rubah karakter a menjadi o, variable output dan masukan ke variable output
10. Reset (kosongkan) nilai variable temp
11. Setelah itu kurangi 1 nilai variable x dan ulangi step ke 5
12. Jika **False** (nilai variable x lebih kecil dari 0), Tampilkan variable output
13. Selesai