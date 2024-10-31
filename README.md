# AplikasiCekCuacaSederhana
 
## Identitas
Nama: Ayu Atut Khofifah

NPM: 2210010553

## Penjelasan Program

### 1. Deskripsi Program
Program aplikasi ini berfungsi untuk menampilkan informasi cuaca secara real-time dengan integrasi API cuaca eksternal, misalnya OpenWeatherMap. Program akan mengambil data cuaca dari API berdasarkan lokasi yang dipilih, kemudian menampilkan kondisi cuaca dalam bentuk teks dan gambar yang mencerminkan keadaan cuaca, seperti cerah, berawan, atau hujan.

### 2. Komponen GUI
Program ini dibangun menggunakan Java Swing dengan beberapa komponen utama:
   - **JFrame**: Jendela utama aplikasi.
   - **JPanel**: Panel yang digunakan untuk mengatur layout komponen.
   - **JLabel**: Komponen untuk menampilkan teks dan gambar cuaca.
   - **JTextField**: Bidang teks untuk memasukkan nama kota atau lokasi.
   - **JButton**: Tombol untuk mengecek cuaca.
   - **JComboBox**: Dropdown untuk memilih lokasi yang sering dicek.

### 3. Logika Program
Program ini mengimplementasikan logika pengambilan data cuaca dari API eksternal dan menampilkan data tersebut dalam antarmuka pengguna. Setelah lokasi dipilih atau dimasukkan, program mengirim permintaan ke API untuk mendapatkan informasi cuaca, dan kemudian menampilkan ikon cuaca yang sesuai.

### 4. Events
Program ini menggunakan dua event utama:
   - **ActionListener** pada tombol "Cek Cuaca" untuk mengambil data cuaca saat tombol ditekan.
   - **ItemListener** pada JComboBox untuk mendeteksi saat pengguna memilih lokasi tertentu dan menampilkan cuaca secara otomatis.

### 5. Variasi atau Fitur Tambahan
Program juga dilengkapi dengan beberapa fitur tambahan:
   - **Daftar Favorit**: Menyimpan kota-kota yang sering dicek dalam daftar favorit sehingga bisa diakses dengan cepat dari JComboBox.
   - **Ekspor Data Cuaca**: Menyediakan tombol untuk menyimpan data cuaca yang ditampilkan dalam bentuk CSV atau teks, sehingga dapat diakses kembali.
   - **JTable untuk Tabel Cuaca**: Fitur ini memungkinkan pengguna memuat data cuaca yang tersimpan dan menampilkannya dalam bentuk tabel.

Dengan fitur-fitur ini, aplikasi cek cuaca sederhana ini memberikan kemudahan bagi pengguna untuk mengakses informasi cuaca di berbagai lokasi dengan cepat dan efisien.

## Keunggulan Program

### 1. **Akses Data Cuaca Langsung**
   - Program ini bisa ambil data cuaca secara real-time dari API, jadi info cuaca yang ditampilkan selalu update sesuai lokasi yang dipilih pengguna.

### 2. **Antarmuka yang Mudah Dipakai**
   - Program pakai Java Swing untuk tampilannya, bikin pengguna gampang paham dan pakainya simpel. Ada opsi masukkan kota manual atau pilih dari daftar favorit yang sering dicek.

### 3. **Pilih Lokasi Favorit dengan Cepat**
   - Fitur daftar favorit bikin pengguna bisa nyimpan kota-kota yang sering dicek, jadi nggak perlu ketik ulang. Tinggal pilih aja dari daftar, langsung keluar cuacanya.

### 4. **Tampilan yang Jelas dan Menarik**
   - Data cuaca nggak cuma ditampilkan dalam bentuk teks, tapi juga dilengkapi gambar ikon cuaca (misal cerah, hujan, atau berawan), jadi lebih gampang dimengerti.

### 5. **Bisa Simpan Data Cuaca**
   - Data cuaca yang udah dicek bisa disimpan dalam bentuk file CSV atau teks. Jadi, kalau suatu waktu butuh lihat data lama, tinggal buka aja filenya.

### 6. **Lihat Riwayat Cuaca di Tabel**
   - Program ini punya fitur buat lihat data cuaca yang udah disimpan dalam bentuk tabel (JTable), cocok buat lihat riwayat atau perbandingan data cuaca.

### 7. **Interaktif dan Cepat Respon**
   - Dengan ActionListener buat tombol dan ItemListener buat pilihan lokasi, program ini langsung respon waktu pengguna pilih kota atau tekan tombol cek cuaca, jadi update-nya cepat dan nggak ribet.

Dengan keunggulan-keunggulan ini, program kamu nggak cuma buat cek cuaca, tapi juga memudahkan pengguna buat akses dan simpan data cuaca dengan praktis.

## Ini dia Screenshot Programnya

**1.** ![ss an AplikasiCekCuaca](https://github.com/user-attachments/assets/99333942-dc70-41f3-99a7-667e2bc593d3)


**2.** ![ss an AplikasiCekCuaca2](https://github.com/user-attachments/assets/e2cf4041-a2e6-4c9a-afa1-892902d1b868)


**3.** ![ss an AplikasiCekCuaca3](https://github.com/user-attachments/assets/e434b0b6-2f0e-410e-a951-1dd2039ada6f)


**4.** ![ss an AplikasiCekCuaca4](https://github.com/user-attachments/assets/f3d21bb9-9cfa-48d0-b048-c1fdc9be0ab5)



