# Kalkulator Waris (Faraid) Modern

Sebuah kalkulator Faraid (waris Islam) *single-page application* (SPA) yang modern, responsif, dan *offline-ready*. Dibuat murni dengan Vanilla JavaScript, HTML, dan CSS untuk memberikan pengalaman pengguna yang elegan dan fungsional.

## 📜 Fitur Utama

Aplikasi ini dirancang dengan fokus pada akurasi (sesuai Al-Qur'an & Sunnah) dan pengalaman pengguna yang modern.

* **Alur Perhitungan Lengkap (Sesuai Syariah):**
    1.  **Kalkulasi Harta Bersih (Tirkah):** Menghitung total harta siap bagi setelah dikurangi biaya jenazah, hutang, dan wasiat.
    2.  **Validasi Wasiat:** Wasiat otomatis dibatasi maksimal 1/3 dari sisa harta (setelah hutang).
* **Logika Faraid yang Komprehensif:**
    * **Hijab (Penghalang) Otomatis:** Input ahli waris yang terhalang (*mahjub*) oleh ahli waris yang lebih dekat akan otomatis nonaktif (*disabled*).
    * **Penanganan Kasus Lanjut:** Mendeteksi dan menangani kasus:
        * **'Aul:** Jika total bagian (*saham*) melebihi pokok masalah.
        * **Tashih:** Jika bagian *'asabah* tidak bisa dibagi habis (menghindari pecahan).
        * **Radd:** Mendeteksi adanya sisa harta tanpa *'asabah* (meski perhitungannya masih prototipe).
* **Informatif & Edukatif:**
    * **Penjelasan Interaktif:** Setiap status perhitungan ('Aul, Tashih, Radd, Adil) memiliki *popup modal* [?] untuk menjelaskan konsep tersebut dengan bahasa yang mudah dipahami.
    * **Referensi Dalil Shahih:** Setiap pembagian ahli waris disertai dengan referensi dalil (Al-Qur'an atau Hadits Shahih) sebagai dasar hukum.
* **Teknis:**
    * **Single File:** Seluruh aplikasi (HTML, CSS, JS) berada dalam **satu file HTML**.
    * **Offline Ready:** Dapat dijalankan 100% *offline* di browser tanpa memerlukan koneksi internet.
    * **Vanilla JavaScript:** Dibangun murni tanpa *framework* atau *library* eksternal untuk performa yang ringan.

## 🚀 Cara Menggunakan

1.  Unduh file `index.html`.
2.  Klik dua kali untuk membukanya di browser favorit Anda (Chrome, Firefox, Edge, dll).
3.  Aplikasi siap digunakan.

## 💻 Tumpukan Teknologi

* **HTML5**
* **CSS3** (Modern CSS: Grid, Flexbox, Animations, Backdrop Filter)
* **Vanilla JavaScript (ES6+)**

## ⚠️ Peringatan Penting

Kalkulator ini dibuat untuk **tujuan edukasi dan sebagai prototipe**. Ilmu Faraid sangat kompleks dan memiliki banyak detail serta perbedaan pendapat (*khilafiyah*) dalam kasus-kasus tertentu (seperti *Radd*, kakek bersama saudara, dll).

Untuk pembagian warisan dalam kasus nyata, **selalu konsultasikan dan validasi hasilnya dengan ulama atau ahli fiqih yang kompeten di bidang mawaris.**
