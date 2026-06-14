# 📈 Kalkulator Valuasi Saham (Stock Valuation Calculator)

Aplikasi web sederhana berbasis kalkulator finansial untuk membantu investor melakukan analisis fundamental saham. Aplikasi ini menghitung metrik valuasi utama seperti EPS, BVPS, PER, PBV, serta Nilai Wajar (Intrinsic Value) menggunakan formula klasik Benjamin Graham.

## ✨ Fitur Utama

- **Single-Page Application:** Berjalan sepenuhnya di sisi klien (browser) tanpa memerlukan server atau instalasi tambahan.
- **Kalkulasi Real-Time:** Menghitung valuasi secara instan setelah data dimasukkan.
- **Metrik Fundamental:** - *Earning Per Share* (EPS)
  - *Book Value Per Share* (BVPS)
  - *Price to Earning Ratio* (PER)
  - *Price to Book Value* (PBV)
- **Benjamin Graham Formula:** Dilengkapi dengan perhitungan Harga Wajar saham untuk membandingkan harga pasar saat ini dengan nilai intrinsiknya.

## 🚀 Cara Penggunaan

1. *Clone* atau *download* repositori ini ke komputer Anda.
2. Buka file `kalkulator-saham.html` menggunakan browser web apa pun (Chrome, Firefox, Safari, Edge).
3. Masukkan data keuangan emiten yang ingin dianalisis:
   - Harga Saham Saat Ini
   - Total Laba Bersih
   - Total Ekuitas
   - Jumlah Saham Beredar
   - Proyeksi Pertumbuhan Laba (Growth)
4. Klik tombol **Hitung Valuasi** untuk melihat hasilnya.

> **💡 Tips Skenario:** Anda dapat menggunakan alat ini untuk menguji skenario spesifik. Misalnya, jika Anda sedang menganalisis saham perbankan yang baru saja merilis laporan keuangan dengan lonjakan EPS naik hingga 60%, Anda bisa langsung memasukkan rasio pertumbuhan tersebut ke dalam kolom *Growth* untuk melihat seberapa besar perubahan harga wajarnya.

## 🧮 Rumus yang Digunakan

Kalkulator ini menggunakan formula standar analisis fundamental:

* **EPS** = Total Laba Bersih / Jumlah Saham Beredar
* **BVPS** = Total Ekuitas / Jumlah Saham Beredar
* **PER** = Harga Saham / EPS
* **PBV** = Harga Saham / BVPS
* **Harga Wajar (Graham)** = EPS * (8.5 + 2g)
  *(Keterangan: 8.5 adalah PER dasar untuk perusahaan tanpa pertumbuhan, dan 'g' adalah proyeksi pertumbuhan).*

## 🛠️ Teknologi yang Digunakan

- **HTML5:** Struktur halaman.
- **CSS3:** Desain tata letak yang responsif dan antarmuka pengguna (UI).
- **JavaScript (Vanilla):** Logika perhitungan matematis dan manipulasi DOM.

## 🤝 Kontribusi

Kritik, saran, dan kontribusi sangat dipersilakan! Jika Anda ingin menambahkan fitur baru (misalnya kalkulasi *Discounted Cash Flow* / DCF) atau memperbaiki bug:
1. *Fork* repositori ini.
2. Buat *branch* fitur Anda (`git checkout -b fitur-baru`).
3. *Commit* perubahan Anda (`git commit -m 'Menambahkan fitur DCF'`).
4. *Push* ke *branch* tersebut (`git push origin fitur-baru`).
5. Buka *Pull Request*.

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE). Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini untuk keperluan pribadi maupun komersial.
