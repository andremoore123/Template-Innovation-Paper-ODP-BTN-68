# **Template Innovation Paper (LaTeX) \- ODP BTN 68**

Template ini disusun khusus untuk rekan-rekan **ODP BTN Angkatan 68** guna memudahkan penyusunan Innovation Paper dengan format yang rapi, standar, dan profesional.

## **📋 Fitur Utama**

* **Modular & Rapi:** Konten (Bab 1, Bab 2, dst.) otomatis terpisah ke file berbeda saat kompilasi pertama.  
* **Branding BTN:** Header, Footer, dan Cover didesain menggunakan aset gambar untuk fleksibilitas maksimal.  
* **Full Otomatis:** Daftar Isi, Daftar Gambar, Tabel, dan Pustaka tergenerate otomatis.

## **📥 Cara Download**

Ada dua cara mudah untuk mendapatkan template ini:

1. **Download ZIP (Paling Mudah):**  
   * Klik tombol hijau **\<\> Code** di bagian kanan atas halaman repositori ini.  
   * Pilih opsi **Download ZIP**.  
   * Ekstrak (unzip) file yang telah didownload ke komputer Anda.  
2. **Menggunakan Git:**  
   * Buka terminal atau command prompt.  
   * Jalankan perintah: git clone https://github.com/andremoore123/Template-Innovation-Paper-ODP-BTN-68.git

## **🚀 Cara Penggunaan**

### **1\. Upload Aset Gambar**

Agar tampilan sesuai standar desain angkatan, upload file berikut ke folder root project (Overleaf/Lokal):

* header.png & footer.png: Hiasan atas/bawah halaman (kecuali cover).  
* cover.png: Background *full page* khusus halaman judul.  
* background.png: Watermark untuk halaman isi.  
* logo.png: Logo BTN/BUMN untuk cover.

*Catatan: Jika gambar belum ada, template aman digunakan (akan muncul kotak placeholder).*

### **2\. Kompilasi (Compile)**

1. Buka file utama: main.tex.  
2. Jalankan kompilasi (rekomendasi: **pdfLaTeX** atau **LuaLaTeX**).  
3. File-file bab (bab1.tex, References.bib, dll) akan otomatis dibuat oleh sistem.

### **3\. Edit Konten**

Setelah kompilasi pertama, edit isi makalah Anda pada file-file yang terbentuk:

* abstrak.tex, bab1.tex, bab2.tex, bab3.tex, lampiran.tex.  
* References.bib untuk daftar pustaka.

## **📂 Struktur File**

├── main.tex  \# File Utama (JANGAN DIHAPUS)  
├── References.bib                  \# Daftar Pustaka  
├── Cover.tex                       \# Layout Judul  
├── Bab-X.tex                       \# File Isi Materi  
└── Lampiran.tex                    \# Data Tambahan

## **🙌 Credits**

Special thanks to **Tim Creative ODP Angkatan 68** atas kontribusi aset desain dan layout visual.

## **📄 Lisensi**

**MIT License**. Bebas digunakan dan dimodifikasi oleh seluruh ODP BTN Angkatan 68\.
