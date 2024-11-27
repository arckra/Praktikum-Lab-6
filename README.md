# Praktikum-Lab-6

**SOAL**

**Tugas Praktikum**

Buat program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:
- Fungsi **tambah()** untuk menambah data
- Fungsi **tapilkan()** untuk menampilkan data
- Fungsi **hapus(nama)** untuk menghapus data berdasarkannama
- Fungsi **ubah(nama)** untuk mengubah data berdasarkannama
- Buat flowchart dan penjelasan programnya pada README.md. 
- Commit dan push repository ke github.

**FLOWCHART**
![Flowchart praktikum7-warna](https://github.com/user-attachments/assets/d44329c2-ddb9-48c2-a66d-9bee50bd605a)

**JAWABAN**

**1. Struktur Data:**
- Data mahasiswa disimpan dalam bentuk list bernama mahasiswa, dengan setiap entri berupa dictionary berisi nama dan nilai.

**2. Fungsi:**
- **tambah(nama, nilai)**: Menambahkan data mahasiswa baru ke list mahasiswa. Program mencetak pesan konfirmasi setelah data berhasil ditambahkan.
- **tampilkan()**: Menampilkan semua data mahasiswa. Jika list kosong, program mencetak pesan bahwa tidak ada data.
- **hapus(nama)**: Menghapus data mahasiswa berdasarkan nama. Data mahasiswa yang tidak cocok tetap dipertahankan.
- **ubah(nama, nilai_baru)**: Memperbarui nilai mahasiswa berdasarkan nama. Jika nama tidak ditemukan, program mencetak pesan bahwa data tidak ditemukan.
- **menu()**: Menyediakan antarmuka bagi pengguna untuk berinteraksi dengan berbagai pilihan menu.

**3. Alur Program (Menu):**
- Program terus berjalan dalam loop, menampilkan menu utama, dan menerima input pengguna.
- Berdasarkan input, program akan memanggil fungsi yang sesuai:
- Tambah data (tambah)
- Tampilkan data (tampilkan)
- Hapus data (hapus)
- Ubah data (ubah)
- Keluar program (mengakhiri loop).

**4. Contoh Interaksi:**
- Pengguna memilih opsi 1, memasukkan nama dan nilai mahasiswa untuk menambah data.
- Pengguna memilih opsi 2 untuk melihat daftar mahasiswa.
- Pengguna memilih opsi 3 untuk menghapus data mahasiswa tertentu.
- Pengguna memilih opsi 4 untuk memperbarui nilai mahasiswa.
- Pengguna memilih opsi 5 untuk keluar dari program.
