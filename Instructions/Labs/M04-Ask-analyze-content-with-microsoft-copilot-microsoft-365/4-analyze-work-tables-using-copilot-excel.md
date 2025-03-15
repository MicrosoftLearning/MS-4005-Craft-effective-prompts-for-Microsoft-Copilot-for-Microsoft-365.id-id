# Menganalisis dan bekerja dengan tabel menggunakan Microsoft 365 Copilot di Excel

Jika Anda tidak yakin cara menulis rumus untuk kolom baru, Microsoft 365 Copilot dapat dengan cepat menambahkan kolom baru dengan rumus berdasarkan data Anda.

1. Dengan data Anda diformat sebagai tabel, pilih tombol **Copilot** di pita.

1. Pilih **Tambahkan kolom rumus** atau **Perlihatkan saran untuk kolom rumus**. Anda juga dapat menjelaskan kolom apa yang ingin Anda tambahkan dengan mengetikkannya dengan kata-kata Anda sendiri.

1. Copilot menyediakan saran rumus dengan penjelasan tentang cara kerja setiap rumus. Lihat penjelasan dengan memilih **Jelaskan rumus**.

1. Pilih Sisipkan kolom untuk menambahkan kolom rumus ke tabel Anda.

> [!IMPORTANT]
> Seperti halnya konten yang dihasilkan AI, penting untuk meninjau, mengedit, dan memverifikasi segala hal yang dibuat oleh Copilot untuk Anda.

## Mari kita mulai membuat kerajinan tangan

Pertama, unduh **_[Kampanye pemasaran Pabrikam Q1.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** dan simpan file tersebut ke **Folder OneDrive** jika Anda belum melakukannya.

Buka spreadsheet di Excel, lalu buka panel **Copilot** dengan memilih ikon Copilot pada tab **Beranda** di pita. Masukkan petunjuk di bawah ini dan ikuti petunjuknya.

> [!NOTE]
> Perintah awal:
>
> _Sarankan kolom rumus._

Dalam perintah sederhana ini, Anda mulai dengan **Tujuan**: dasar: _untuk membuat kolom dengan rumus yang baru._ Namun, informasi yang detail tidak disediakan untuk menentukan apa yang harus dihitung rumus.  

| Elemen | Contoh |
| :------ | :------- |
| **Perintah dasar:** Mulai dengan **Tujuan** | **_Sarankan kolom rumus._** |
| **Perintah yang baik:** Tambahkan **Konteks** | Menambahkan **Konteks** membantu Copilot memahami apa yang harus dihitung rumus. _"... untuk kolom J untuk menentukan rasio keterlibatan setiap kampanye."_ |
| **Perintah yang lebih baik:** Tentukan **Sumber** | **Sumber** untuk perintah ini adalah kolom tertentu yang diperlukan untuk perhitungan. _"... menggunakan nilai dari 'Pengguna yang Terlibat' dan 'Total Pengguna Yang Ditargetkan'."_ |
| **Perintah terbaik:** Berikan **Ekspektasi** yang jelas | Menambahkan **Ekspektasi** membantu Copilot menyusun rumus dengan benar. _"Pastikan rumus membagi 'Pengguna yang Terlibat' dengan 'Total Pengguna Yang Ditargetkan' dan memformat hasilnya sebagai persentase."_ |

> [!NOTE]  
> **Perintah yang dibuat**:  
>
> _Sarankan rumus untuk kolom J untuk menghitung rasio keterlibatan setiap kampanye. Gunakan nilai dari 'Pengguna yang Terlibat' dan 'Total Pengguna Yang Ditargetkan'. Pastikan rumus membagi 'Pengguna yang Terlibat' dengan 'Total Pengguna Yang Ditargetkan' dan memformat hasilnya sebagai persentase._  

![Cuplikan layar hasil perintah yang dibuat menggunakan Copilot di Excel.](../media/ask_copilot-explain-formula-results-excel.png)

Perintah ini memiliki semua detail yang dibutuhkan - **Tujuan**, **Konteks**, **Sumber**, dan **Harapan** - sehingga Copilot dapat memberi Anda jawaban yang Anda cari.

## Lihat selengkapnya

Gunakan perintah ini sebagai titik awal. Salin dan ubah agar sesuai dengan kebutuhan Anda.

- Hitung total biaya per produk di kolom baru.

- Tambahkan kolom yang menghitung total laba untuk setiap kampanye pemasaran pada tahun 2022.

- Tambahkan kolom yang menghitung jumlah hari setelah peristiwa peluncuran produk.

Untuk informasi selengkapnya, lihat [Membuat kolom rumus dengan Copilot di Excel](https://support.microsoft.com/office/generate-formula-columns-with-copilot-in-excel-d866d926-9791-4e5f-be2a-c6dd9e587a47).
