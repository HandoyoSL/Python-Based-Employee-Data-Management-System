# CAPSTONE-MODUL-1-PURWADHIKA
Program ini mengelola data karyawan dengan fungsi CRUD (tambah, baca, ubah, hapus), pencarian berdasarkan nama/divisi, dan validasi input. Riwayat data yang dihapus juga tersimpan. Sederhana, namun fungsional untuk kebutuhan manajemen data karyawan dasar.

# Manajemen Data Karyawan

Sistem ini bertujuan untuk mengelola data karyawan dalam perusahaan. Dengan fitur-fitur seperti menambah, mengedit, menghapus, dan memulihkan data karyawan.

## Fitur Utama

1. **Tambah Data Karyawan**
   - Menambahkan data karyawan baru ke dalam sistem.

2. **Lihat Data Karyawan**
   - Menampilkan semua data karyawan yang ada.

3. **Cari Data Karyawan**
   - Mencari data karyawan berdasarkan nama dan divisi.

4. **Hapus Data Karyawan**
   - Menghapus data karyawan dari sistem.

5. **Lihat History Data yang Dihapus**
   - Menampilkan riwayat data karyawan yang telah dihapus.

6. **Edit Data Karyawan**
   - Memperbarui informasi karyawan yang ada.

7. **Ekspor Data Karyawan**
   - Mengekspor data karyawan ke dalam format CSV.

8. **Restore Data Karyawan**
   - Memulihkan data karyawan yang telah dihapus.

9. **Validasi Data Karyawan**
   - Memastikan bahwa data yang dimasukkan oleh pengguna sesuai dengan format dan kriteria yang telah ditetapkan, mengurangi kemungkinan kesalahan input.

## Struktur Data Karyawan

Data karyawan disimpan dalam format list of dictionaries. Setiap karyawan memiliki atribut sebagai berikut:

- `kode_karyawan`: Kode unik untuk setiap karyawan.
- `nama_lengkap`: Nama lengkap karyawan.
- `nomor_ktp`: Nomor KTP karyawan.
- `jabatan`: Jabatan karyawan di perusahaan.
- `departemen`: Departemen tempat karyawan bekerja.
- `tgl_mulai_kerja`: Tanggal mulai bekerja.
- `gaji_pokok`: Gaji pokok karyawan.
- `status_pekerjaan`: Status pekerjaan karyawan.
- `pendidikan_terakhir`: Pendidikan terakhir yang ditempuh.
- `nomor_telepon`: Nomor telepon karyawan.
- `alamat`: Alamat tempat tinggal karyawan.
- `email`: Alamat email karyawan.
- `status_pernikahan`: Status pernikahan karyawan.
- `jumlah_anak`: Jumlah anak karyawan.
- `bpjs_kesehatan`: Status BPJS kesehatan karyawan.
- `bpjs_ketenagakerjaan`: Status BPJS ketenagakerjaan karyawan.

## Fungsi-fungsi

### 1. `create_data(data_karyawan)`

Fungsi untuk menambahkan data karyawan baru.

### 2. `read_data(data_karyawan)`

Fungsi untuk menampilkan data karyawan.

### 3. `search_data(data_karyawan)`

Fungsi untuk mencari data karyawan berdasarkan nama dan divisi.

### 4. `delete_data(data_karyawan)`

Fungsi untuk menghapus data karyawan.

### 5. `lihat_history_delete_data(history_delete)`

Fungsi untuk melihat riwayat data yang dihapus.

### 6. `edit_data(data_karyawan)`

Fungsi untuk mengedit informasi karyawan.

### 7. `export_to_csv(data_karyawan, filename="data_karyawan.csv")`

Fungsi untuk mengekspor data karyawan ke dalam file CSV.

### 8. `restore_data(data_karyawan)`

Fungsi untuk mengembalikan data karyawan yang dihapus.

### 9. `generate_new_code(data_karyawan, kode_karyawan)`

Fungsi untuk menghasilkan kode karyawan baru jika diperlukan.

### 10. `validasi_data(data_karyawan)`

Fungsi untuk memvalidasi input data karyawan baru, memastikan semua informasi yang dimasukkan sesuai dengan format yang diharapkan.

## Cara Menggunakan

1. Jalankan program dengan menjalankan file utama.
2. Ikuti petunjuk yang muncul untuk memilih menu yang diinginkan.
3. Masukkan data sesuai permintaan.

## Contoh Penggunaan

1. **Menambah Data Karyawan**
   - Pilih menu 1 dan ikuti instruksi untuk memasukkan data karyawan baru seperti nama, kode karyawan, jabatan, dan lainnya.

2. **Melihat Data Karyawan**
   - Pilih menu 2 untuk menampilkan semua data karyawan yang ada dalam sistem.

3. **Mencari Data Karyawan**
   - Pilih menu 3, masukkan nama dan divisi yang ingin dicari untuk menemukan data spesifik.

4. **Menghapus Data Karyawan**
   - Pilih menu 4 dan masukkan kode serta nama lengkap karyawan yang ingin dihapus dari sistem.

5. **Lihat History Data yang Dihapus**
   - Pilih menu 5 untuk menampilkan riwayat data karyawan yang telah dihapus.

6. **Edit Data Karyawan**
   - Pilih menu 6 untuk memperbarui informasi karyawan yang ada dengan memasukkan kode karyawan dan data baru.

7. **Mengekspor Data Karyawan**
   - Pilih menu 7 untuk mengekspor data karyawan ke dalam file CSV, yang bisa dibuka dengan aplikasi spreadsheet.

8. **Restore Data Karyawan**
   - Pilih menu 8 dan masukkan kode karyawan yang ingin dipulihkan dari riwayat penghapusan.

9. **Keluar dari Program**
   - Pilih menu 9 untuk keluar dari program dan menghentikan eksekusi.
