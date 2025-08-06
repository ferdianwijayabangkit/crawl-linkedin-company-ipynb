# 🕷️ LinkedIn Company Crawler™

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Selenium](https://img.shields.io/badge/Selenium-4.0+-green.svg)
![License](https://img.shields.io/badge/License-Academic%20Use-red.svg)
![Affiliation](https://img.shields.io/badge/Affiliation-UNTIRTA-orange.svg)

Sistem otomatis tingkat lanjut untuk mengumpulkan data perusahaan dari LinkedIn, dilengkapi dengan teknologi *Anti-CAPTCHA Protection™* dan *Smart Challenge Handler™*.

## ✨ Fitur Utama

- **🛡️ Anti-Deteksi & CAPTCHA**: Menggunakan rotasi *user agent*, simulasi perilaku manusia, dan deteksi *challenge* otomatis untuk melewati mekanisme keamanan LinkedIn.
- **🧠 Smart Challenge Handler™**: Mampu menangani berbagai verifikasi (email, telepon, CAPTCHA) secara otomatis untuk sesi *crawling* yang lebih lancar.
- **🔍 Pencarian Multi-Keyword**: Mendukung input banyak *keyword* sekaligus, dengan pemrosesan berurutan dan deduplikasi hasil untuk efisiensi.
- **📊 Manajemen Data Lengkap**: Mengekspor data ke format **CSV**, **Excel**, dan **JSON** dengan *monitoring* proses dan validasi kualitas data secara *real-time*.
- **📱 Antarmuka Responsif**: Didesain agar berfungsi dengan baik di berbagai perangkat, termasuk antarmuka Jupyter Notebook yang *mobile-friendly*.

## 🔧 Tumpukan Teknologi (Tech Stack)

- **Bahasa**: `Python 3.7+`
- **Automasi & Crawling**: `Selenium 4.x`
- **Manajemen Data**: `Pandas`
- **Antarmuka**: `IPython Widgets`
- **Lingkungan**: `Jupyter Notebook / Lab`

## 🚀 Cara Memulai

### Prasyarat
- **Perangkat Lunak**: Python 3.7+, Browser Google Chrome, Jupyter Notebook/Lab.
- **Perangkat Keras**: RAM minimal 4GB (8GB direkomendasikan).
- **Akun**: Akun LinkedIn yang valid untuk proses autentikasi.

### Instalasi & Penggunaan

1.  **Unduh Notebook**: *Clone* atau unduh *repository* proyek ini ke komputer Anda.

2.  **Buka di Jupyter**: Jalankan file `.ipynb` menggunakan Jupyter Notebook atau Jupyter Lab.

3.  **Instalasi Otomatis**: Jalankan **Tahapan 1** di dalam *notebook*. Skrip akan secara otomatis menginstal semua *dependencies* yang diperlukan (`selenium`, `pandas`, dll.).

4.  **Ikuti Alur Kerja 4 Tahapan**:
    - **Tahap 1: Konfigurasi**: Menyiapkan *environment* dan dependensi.
    - **Tahap 2: Autentikasi**: *Login* ke LinkedIn dengan aman menggunakan fitur anti-deteksi.
    - **Tahap 3: Pencarian**: Masukkan *multiple keyword* untuk memulai proses *crawling*.
    - **Tahap 4: Analisis & Ekspor**: Lihat hasil dalam tabel interaktif dan ekspor ke format yang Anda inginkan.

## 📊 Struktur Data Output

Data yang berhasil diekstrak mencakup informasi perusahaan yang komprehensif, seperti:

| Field                   | Deskripsi                                          | Contoh                                     |
| ----------------------- | -------------------------------------------------- | ------------------------------------------ |
| `company_name`          | Nama lengkap dan resmi perusahaan                  | "PT Teknologi Indonesia Maju"              |
| `description`           | Deskripsi detail mengenai bisnis perusahaan        | "Perusahaan solusi teknologi informasi..." |
| `industry`              | Klasifikasi sektor industri                        | "Teknologi Informasi dan Layanan"          |
| `location`              | Lokasi geografis kantor pusat                      | "Jakarta, Indonesia"                       |
| `company_size`          | Rentang jumlah karyawan perusahaan                 | "1,001-5,000 karyawan"                     |
| `linkedin_url`          | URL unik profil perusahaan di LinkedIn             | "https://linkedin.com/company/..."         |
| `follower_count`        | Jumlah pengikut di halaman LinkedIn                | 150234                                     |
| `contact_info`          | Informasi kontak publik (jika tersedia)            | "info@techindo.com"                        |

## ⚖️ Lisensi & Ketentuan Penggunaan

- **Hak Cipta**: © 2025 Ferdian Bangkit Wijaya - Seluruh Hak Dilindungi.
- **Penggunaan Akademik**: Diizinkan secara bebas untuk keperluan penelitian, tesis, dan pendidikan non-komersial dengan atribusi.
- **Penggunaan Komersial**: Memerlukan izin tertulis dari pengembang.
- **Teknologi**: *Anti-CAPTCHA Protection™* dan *Smart Challenge Handler™* adalah algoritma *proprietary* yang dikembangkan untuk proyek ini. Distribusi ulang kode harus mempertahankan pemberitahuan hak cipta ini.

## 👨‍💻 Author

- **Ferdian Bangkit Wijaya**
- Program Studi Statistika, Fakultas Teknik
- **Universitas Sultan Ageng Tirtayasa (UNTIRTA)**
- Banten, Indonesia 🇮🇩

---

> Dirancang untuk penelitian tingkat lanjut, sistem ini menyediakan alat yang kuat dan etis untuk pengumpulan data dari LinkedIn.
