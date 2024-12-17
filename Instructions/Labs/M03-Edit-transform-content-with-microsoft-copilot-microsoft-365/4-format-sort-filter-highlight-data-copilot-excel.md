
Dengan Microsoft 365 Copilot di Excel, mudah untuk menyoroti, mengurutkan, dan memfilter tabel Anda untuk dengan cepat memanggil perhatian pada hal yang penting bagi Anda. Dengan menggunakan satu tabel di Excel, Anda bisa membuat Copilot dengan mudah: 

- Urutkan dan filter data Anda.

- Terapkan pemformatan bersyarat sederhana.

Untuk memulai, format data Anda sebagai tabel dan pilih ikon **Copilot** di pita. Kemudian, beri tahu Copilot bagaimana Anda ingin memanipulasi tabel untuk melihat bagian data Anda dengan lebih baik. 

Dalam contoh berikut, kita mulai dengan perintah sederhana dan menambahkan elemen di sepanjang jalan. Ikuti contoh menggunakan data Anda sendiri.

## Mari kita mulai membuat kerajinan tangan

Pertama, unduh **_[Kampanye pemasaran Pabrikam Q1.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** dan simpan file tersebut ke **Folder OneDrive** jika Anda belum melakukannya.

Buka spreadsheet di Excel, lalu buka panel **Copilot** dengan memilih ikon Copilot pada tab **Beranda** di pita. Masukkan petunjuk di bawah ini dan ikuti petunjuknya.

> [!NOTE]
> Perintah awal:
>
> _Urutkan tabel ini._

Dalam perintah sederhana ini, Anda mulai dengan perintah dasar **Tujuan**: _untuk mengurutkan dan memfilter tabel Excel_. Namun, tidak ada indikasi bagaimana Anda ingin data diurutkan dan bidang mana yang ingin Anda filter.

| Elemen | Contoh |
| :------ | :------- |
| Perintah dasar: <br>Mulai dengan **Tujuan** | **_Urutkan tabel ini..._** |
| Perintah yang baik: <br>Tambahkan **Konteks** | **Menambahkan Konteks** dapat membantu Copilot memahami tujuan slide dan topik apa yang akan difokuskan.<br><br>"_...untuk mencari staf penjualan yang paling berdampak._" |
| Perintah yang lebih baik: <br>Tentukan **Sumber** | **Sumber** untuk perintah ini diasumsikan sebagai tabel yang sedang kami kerjakan di Excel.<br><br>“_... tabel ini [Tabel1]..._” |
| Perintah terbaik: <br>Tetapkan dengan jelas **Harapan** | Terakhir, menambahkan **Harapan** dapat membantu Copilot memahami bagaimana Anda ingin tabel diurutkan, difilter, dan disajikan.<br><br>"_Tambahkan kolom ketiga yang menghitung pendapatan bersih per pengguna yang terlibat, dengan memperhitungkan biaya anggarannya. Urutkan tabel ini dalam urutan menurun menurut pendapatan bersih per pengguna yang terlibat, lalu sorot pemilik baris teratas dan terbawah._" |

> [!NOTE]
> **Perintah yang dibuat**:
>
> _Urutkan tabel ini [Table1] untuk mencari tenaga penjual yang paling berdampak. Tambahkan kolom ketiga yang menghitung pendapatan bersih per pengguna yang terlibat, dengan memperhitungkan biaya anggarannya. Urutkan tabel ini dalam urutan menurun menurut pendapatan bersih per pengguna yang terlibat, lalu sorot pemilik baris teratas dan terbawah._

Perintah ini memerlukan beberapa langkah untuk dieksekusi, sebuah teknik perintah yang disebut **penautan** di mana Anda meminta Copilot melakukan perintah berurutan dan terus-menerus untuk mencapai satu tujuan. 

Dalam permintaan yang dibuat, Copilot memahaminya terlebih dahulu perlu menghasilkan rumus untuk kolom baru untuk menghitung pendapatan bersih per pengguna yang terlibat dan memasukkannya ke dalam tabel.

![Cuplikan layar Copilot di Excel yang menghasilkan rumus untuk disisipkan ke dalam tabel.](../media/copilot-add-formula-excel.png)

Sekarang setelah kolom baru dimasukkan ke dalam tabel, Anda dapat meminta Copilot mengurutkan tabel berdasarkan pendapatan bersih tertinggi per pengguna yang terlibat, serta menyoroti penjual atas dan bawah.

[![Cuplikan layar hasil perintah yang dibuat terhadap lembar bentang sampel menggunakan Copilot di Excel.](../media/copilot-sort-highlight-table-excel.png)](../media/copilot-sort-highlight-table-excel.png#lightbox)

Perintah ini memiliki semua detail yang dibutuhkan - **Tujuan**, **Konteks**, **Sumber**, dan **Harapan** - sehingga Copilot dapat memberi Anda jawaban yang Anda cari.

## Lihat selengkapnya

Cobalah perintah sederhana ini untuk menyoroti, mengurutkan, dan memfilter data Anda dan menambahkan elemen lain untuk meningkatkan hasil Anda:

- Tebalkan 10 nilai teratas di kolom Penjualan.

- Sorot nilai tertinggi dalam Unit Terjual.

- Urutkan tingkat keterlibatan dari terkecil ke terbesar.  

- Filter ke item yang jatuh tempo minggu depan.

> [!IMPORTANT]
> Salinan hanya akan berfungsi pada file yang disimpan di OneDrive atau SharePoint. Jika Anda tidak dapat memilih tombol Copilot di pita, coba simpan file ke cloud terlebih dahulu. Untuk informasi lebih lanjut, lihat **[Sorot, urutkan, dan filter data Anda dengan Copilot di Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936)**.