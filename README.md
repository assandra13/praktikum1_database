# PRAKTIKUM 1

1. Buat sebuah database dengan nama latihan2!

![img](folder/1.png)

2. Buat sebuah tabel dengan nama biodata (nama, alamat) didalam
database latihan1!

![img](folder/2.png)
![img](folder/3.png)

3. Tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom
terakhir!

![img](folder/4.png)

4. Tambahkan kolom id (int 11) di awal (sebagai kolom pertama)!

![img](folder/5.png)

5. Sisipkan sebuah kolom dengan nama phone (varchar 15) setelah
kolom alamat!

![img](folder/6.png)

6. Ubah tipe data kolom id menjadi char(11)!

![img](folder/7.png)

7. Ubah nama kolom phone menjadi hp (varchar 20)!

![img](folder/8.png)

8. Tambahkan kolom email setelah kolom hp

![img](folder/9.png)

9. Hapus kolom keterangan dari tabel!

![img](folder/10.png)

10. Ganti nama tabel menjadi data_mahasiswa!

![img](folder/11.png)

11. Ganti nama field id menjadi nim!

![img](folder/12.png)

12. Jadikan nim sebagai PRIMARY KEY!

![img](folder/13.png)

13. Jadikan kolom email sebagai UNIQUE KEY

![img](folder/14.png)


* ![img](folder/15.png)
int(11) adalah tipe data integer dan memiliki panjang 11 karakter

* ![img](folder/16.png)
Jika kolom "NULL" memiliki nilai "YES", artinya kolom tersebut diizinkan untuk berisi nilai "NULL". Ini berarti bahwa kolom tersebut tidak harus diisi dengan nilai tertentu saat melakukan operasi INSERT atau UPDATE pada tabel.

Jika kolom "NULL" memiliki nilai "NO", artinya kolom tersebut tidak diizinkan untuk berisi nilai "NULL". Ini berarti bahwa kolom tersebut harus diisi dengan nilai tertentu saat melakukan operasi INSERT atau UPDATE pada tabel. Jika kita mencoba melakukan operasi INSERT atau UPDATE tanpa menyediakan nilai untuk kolom yang tidak diizinkan "NULL", maka MySQL akan menghasilkan kesalahan dan operasi tersebut akan gagal.