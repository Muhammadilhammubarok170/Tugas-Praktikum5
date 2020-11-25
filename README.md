# Tugas-Praktikum5
Buat program sederhana yang menampilkan daftar nilai mahasiswa, dengan tampikan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)

Langkah - Langkah:

-Pertama kita membuat dictionary kosong data = {}

-Lalu gunakan perulangan while. dengan inptan menu(Lihat, Tambah, Ubah, Hapus, Cari, Keluar)

-Dan gunakan kondisi if, else dan elif untuk mengeksekusi perintah.

-Ketik "k" untuk keluar. Gunakan fungsi if, jika hasil true program akan berhenti.

-Ketik "l" untuk melihat hasil inputan. Gunakan looping for for x in data.items(): lalu masukan printah print data.

-Ketik "t" untuk menambahkan data. inputkan data: Nama, NIM, Nilai Tugas, Nilai UTS, NIlai UAS. Nilai akhir di hitung dengan rumus akhir = (0.30 * tugas) + (0.35 * uts) + (0.35 * uas)


![screen 1](/gambar/screen1.png)


-Ketik "u" untuk mengubah data. Masukan data nama yang ingin di ubah, jika data benar akan kembali ke data
 perubahan, jika salah akan tercetak print("Data {0} Tidak tersedia ".format(nama)) dan muncul kembali
 menu pemilihan untuk input data.
 
 
 ![screen 2](/gambar/screen2.png)


-Ketik "h" untuk menghapus data. Dengan menginputkan data nama yang ingin di hapus menggunakan kondisi
 if, jika hasilnya benar data akan di hapus.
 
 
 ![screen 3](/gambar/screen3.png)

-Ketik "c" untuk mencari data. dengan menginputkan data nama yang ingin di cari, jika datanya benar otomatis 
 data akan tercetak yang dicari.
 
 
 ![screen 4](/gambar/screen4.png)


-Kondisi terakhir gunakan kondisi else dan print(" === Pilih Sesuai Menu Yang Tersedia === ") maksudnya
 jika menu yang anda inputkan salah anda akan dialihkan ke menu yang tersedia.
