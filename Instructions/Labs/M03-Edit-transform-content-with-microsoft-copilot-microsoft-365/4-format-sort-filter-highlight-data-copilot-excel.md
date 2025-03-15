# Memformat, mengurutkan, memfilter, dan menyoroti data menggunakan Microsoft 365 Copilot di Excel

Dengan Microsoft 365 Copilot di Excel, mudah untuk menyoroti, mengurutkan, dan memfilter tabel Anda untuk dengan cepat memanggil perhatian pada hal yang penting bagi Anda. Dengan menggunakan satu tabel di Excel, Anda bisa membuat Copilot dengan mudah:

- Urutkan dan filter data Anda.

- Terapkan pemformatan bersyarat sederhana.

Untuk memulai, format data Anda dalam [format yang didukung](https://support.microsoft.com/topic/format-data-for-copilot-in-excel-1604c8eb-57f1-4db1-8363-d53336228c65) dan pilih tombol **Copilot** pada pita. Kemudian, beri tahu Copilot bagaimana Anda ingin memanipulasi tabel untuk melihat bagian data Anda dengan lebih baik.

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
| **Perintah dasar:** Mulai dengan **Tujuan** | **_Urutkan tabel ini..._** |
| **Perintah yang baik:** Tambahkan **Konteks** | **Menambahkan Konteks** dapat membantu Copilot memahami tujuan slide dan topik apa yang akan difokuskan. _"...untuk mencari staf penjualan yang paling berdampak."_ |
| **Perintah yang lebih baik:** Tentukan **Sumber** | **Sumber** untuk perintah ini diasumsikan sebagai tabel yang sedang kami kerjakan di Excel. _“... tabel ini [Tabel1]...”_ |
| **Perintah terbaik:** Berikan **Ekspektasi** yang jelas | Terakhir, menambahkan **Harapan** dapat membantu Copilot memahami bagaimana Anda ingin tabel diurutkan, difilter, dan disajikan. _"dan menyoroti pemilik kampanye teratas dan terbawah berdasarkan pendapatan bersih."_ |

> [!NOTE]
> **Perintah yang dibuat**:
>
> _Urutkan tabel ini [Table1] untuk mencari penjual yang paling berdampak dan menyoroti pemilik kampanye teratas dan bawah berdasarkan pendapatan bersih_

Perintah ini memerlukan beberapa langkah untuk dieksekusi, sebuah teknik perintah yang disebut **penautan** di mana Anda meminta Copilot melakukan perintah berurutan dan terus-menerus untuk mencapai satu tujuan.

**Perintah pertama**:

```text
Sort this table [Table1] to look for the most impactful salesperson.
```

**Perintah Kedua**:

```text
highlight the top and bottom campaign owners based off of net revenue
```

Perintah ini memiliki semua detail yang dibutuhkan - **Tujuan**, **Konteks**, **Sumber**, dan **Harapan** - sehingga Copilot dapat memberi Anda jawaban yang Anda cari.

## Lihat selengkapnya

Cobalah perintah sederhana ini untuk menyoroti, mengurutkan, dan memfilter data Anda dan menambahkan elemen lain untuk meningkatkan hasil Anda:

- Tebalkan 10 nilai teratas di kolom Penjualan.

- Sorot nilai tertinggi dalam Unit Terjual.

- Urutkan tingkat keterlibatan dari terkecil ke terbesar.  

- Filter ke item yang jatuh tempo minggu depan.

> [!IMPORTANT]
> Salinan hanya akan berfungsi pada file yang disimpan di OneDrive atau SharePoint. Jika Anda tidak dapat memilih tombol Copilot di pita, coba simpan file ke cloud terlebih dahulu. Untuk informasi lebih lanjut, lihat [Sorot, urutkan, dan filter data Anda dengan Copilot di Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936).
