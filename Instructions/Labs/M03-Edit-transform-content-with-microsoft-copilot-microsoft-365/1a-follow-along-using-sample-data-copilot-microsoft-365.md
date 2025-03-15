# Latihan - Ikuti menggunakan data sampel dengan Microsoft 365 Copilot

Di seluruh modul ini, kami akan membuat perintah untuk Microsoft 365 Copilot yang mereferensikan file-file ini:

- [Graphic Design Institute - Employee Benefits.docx](https://go.microsoft.com/fwlink/?linkid=2268825)
- [Mystic Spice Premium Chai Market Analysis Presentation.pptx](https://go.microsoft.com/fwlink/?linkid=2268768)
- [Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)

**Catatan**: Ini adalah file yang akan kita referensikan di seluruh modul. Namun, untuk lab ini, kita akan mulai dengan mengunggah semua file ke **OneDrive** untuk memastikan file tersebut dapat diakses untuk perintah Copilot nantinya.

## Mengunggah file ke OneDrive

Ikuti langkah-langkah di bawah ini untuk mengunggah semua file yang diperlukan ke **OneDrive**:

1. Masuk ke komputer virtual yang disediakan oleh penyedia penyewa Anda sebagai akun **Administrator** lokal dengan kata sandi `Pa55w.rd`.
2. Pada taskbar, pilih ikon **Microsoft Edge**.
3. Di bilah alamat, masukkan `https://www.office.com`.
4. Di bawah **Selamat Datang di Microsoft 365**, pilih **Masuk**.
5. Pada **permintaan Masuk**, masukkan `userx@yourtenant.onmicrosoft.com` (nama pengguna dan penyewa yang disediakan oleh penyewa Anda) dan pilih **Berikutnya**.

    [![Tangkap layar panel sumber daya dalam Skillable](../media/lab_resources_password.png)](../media/lab_resources_password.png#lightbox)

6. Di layar **Masukkan kata sandi**, masukkan kata sandi (disediakan oleh penyedia penyewa) untuk akun Pengguna, lalu pilih **Masuk**.
7. Jika diminta untuk **Tetap masuk**, pilih **Jangan tampilkan ini lagi** lalu **Ya**.
8. Di **Microsoft 365**, pilih **Aplikasi**.
9. Dalam **Aplikasi**, pilih **OneDrive**.
10. Di **OneDrive**, di sudut kiri atas, pilih **+**(tambahkan baru) > **Unggahan file**.
11. Di **File Explorer**, select **This PC** > **Local Disk (C:)** dan buka **folder ResourceFiles.**
12. Pilih semua file dalam folder **ResourceFiles**, lalu pilih **Buka** untuk mengunggahnya ke **OneDrive**.
13. Setelah pengunggahan selesai, Anda akan melihat **29 item yang diunggah ke My files** di tengah bawah layar.
14. Biarkan **Edge** terbuka dan lanjutkan ke tugas berikutnya.

### Mereferensi file

Saat mereferensikan file dari Copilot, terkadang Anda tidak dapat menemukan beberapa file dari saran yang diberikan kepada Anda. Ini terjadi karena pengalaman tertentu dengan Copilot hanya mereferensikan file dari daftar Paling Baru Digunakan (MRU), sementara yang lain memungkinkan Anda menelusuri OneDrive untuk menemukan file Anda. Menambahkannya ke daftar tersebut semudah membukanya di aplikasi Microsoft 365 yang sesuai.  Setelah dibuka, file akan muncul dalam daftar MRU.

> [!IMPORTANT]
> Microsoft 365 Copilot hanya akan berfungsi dengan file yang disimpan ke OneDrive. Jika file disimpan secara lokal di PC Anda, Anda harus memindahkannya ke OneDrive untuk mengaktifkan Copilot.

Saat menelusuri modul, Anda berkesempatan mencoba perintah lain untuk file-file ini dan disarankan untuk mencobanya agar dapat memahami dan meningkatkan keterampilan membuat perintah.
