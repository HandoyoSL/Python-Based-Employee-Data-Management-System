# CAPSTONE-MODUL-1-PURWADHIKA
Program ini mengelola data karyawan dengan fungsi CRUD (tambah, baca, ubah, hapus), pencarian berdasarkan nama/divisi, dan validasi input. Riwayat data yang dihapus juga tersimpan. Sederhana, namun fungsional untuk kebutuhan manajemen data karyawan dasar.

# Sistem Manajemen Data Karyawan

Program Python sederhana untuk mengelola data karyawan.

## Struktur Data

Data karyawan disimpan dalam format `list of dictionaries`. Setiap *dictionary* mewakili seorang karyawan dengan *key* berikut:

*   `kode_karyawan`
*   `nama_lengkap`
*   `nomor_ktp`
*   `jabatan`
*   `departemen`
*   `tgl_mulai_kerja`
*   `gaji_pokok`
*   `status_pekerjaan`
*   `pendidikan_terakhir`
*   `nomor_telepon`
*   `alamat`
*   `email`
*   `status_pernikahan`
*   `anak`
*   `bpjs_kesehatan`
*   `bpjs_ketenagakerjaan`

## Fungsi-fungsi

Berikut adalah fungsi-fungsi utama dalam program ini:

*   **`create_data(data_karyawan)`**: Menambahkan data karyawan baru.
*   **`read_data(data_karyawan)`**: Menampilkan data karyawan.
*   **`search_data(data_karyawan)`**: Mencari data karyawan berdasarkan nama dan divisi.
*   **`edit_data(data_karyawan)`**: Mengedit data karyawan.
*   **`delete_data(data_karyawan, history_delete)`**: Menghapus data karyawan.
*   **`lihat_history_delete_data(history_delete)`**: Melihat history data yang dihapus.

## Contoh Penggunaan
