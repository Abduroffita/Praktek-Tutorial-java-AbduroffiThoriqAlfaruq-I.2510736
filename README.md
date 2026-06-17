# Praktek-Tutorial-java-AbduroffiThoriqAlfaruq-I.2510736

**Deskripsi Proyek**
Proyek ini adalah aplikasi desktop "Form Siswa" berbasis Java yang dirancang untuk mengelola pendataan siswa. Aplikasi ini mengimplementasikan fungsi dasar CRUD yang memungkinkan pengguna untuk memasukkan, menampilkan, memperbarui, dan menghapus riwayat data siswa yang terhubung ke database.

## Fitur Aplikasi
Antarmuka Form Siswa dilengkapi dengan form pengisian dan tombol aksi berikut:
- Input Data: Mendukung pengisian Nomor Induk Siswa (NIS), Nama, Jurusan (Dropdown), Jenis Kelamin (Dropdown), dan Alamat (Text Area).
- Simpan: Menyimpan data siswa baru yang dimasukkan ke dalam database.
- Update: Memperbarui atau mengedit informasi data siswa yang sudah ada.
- Hapus: Menghapus entri data siswa yang dipilih.
- Reset: Membersihkan seluruh kolom input untuk mempermudah pengisian data baru.
- Tabel Data: Menampilkan rekapitulasi daftar siswa yang sudah berhasil disimpan secara langsung.

---

## Teknologi yang Digunakan
 
- Bahasa Pemrograman: Java
- GUI Framework: Java Swing
- IDE: Apache NetBeans IDE
- Build Tool: Maven
- Database Integration: Menggunakan koneksi JDBC.

---

## Struktur Proyek

- FormSiswa.java: Berisi logika antarmuka pengguna (GUI) dan event handler untuk tombol-tombol aksi.
- koneksi.java: Mengatur konfigurasi untuk menyambungkan aplikasi Java ke server database.

- pom.xml: File konfigurasi Maven untuk mengelola dependencies proyek.

---

## Penggunaan Layout Manual 
Pada baris kode yang terlihat di belakang form (lblJk.setBounds(20, 185, 80, 25);), terlihat bahwa kamu menggunakan posisi absolut (Absolute Layout). Ini berarti komponen diatur berdasarkan koordinat piksel secara spesifik.

---

## Koneksi Database Aktif
Adanya file koneksi.java pada tab di sebelah FormSiswa.java mengonfirmasi bahwa data yang tampil di tabel (seperti data siswa bernama "Ifforudba" dan "i ketut mandra...") kemungkinan besar ditarik (di-fetch) langsung dari tabel database sungguhan.

---

## Proses Build Berhasil
Di bagian Output paling bawah, terdapat pesan Nothing to compile - all classes are up to date. Ini menandakan Maven telah berhasil mengecek dan melakukan kompilasi program tanpa adanya pesan error syntax, sehingga form GUI dapat di-Run dengan mulus.

## Screenshots
<img width="1917" height="1140" alt="image" src="https://github.com/user-attachments/assets/d56151bf-4bd4-4e25-a3be-0d02aeeeaeb2" />
