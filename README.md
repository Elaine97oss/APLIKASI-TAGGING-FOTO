# 📸 Evident Photo Tagger (Web Version)

Aplikasi berbasis web sederhana (Single File HTML) untuk menambahkan watermark berupa **Waktu**, **Tanggal**, **Alamat**, dan **Koordinat GPS** pada foto dokumentasi.

Aplikasi ini dirancang untuk memudahkan petugas lapangan atau dokumentasi dalam membuat *evident* (bukti) kegiatan dengan tampilan yang rapi, informatif, dan data lokasi yang akurat menggunakan peta interaktif.

## ✨ Fitur Utama

* **100% Client-Side (Aman):** Semua proses pengeditan foto dilakukan di browser Anda. **Foto tidak diunggah ke server mana pun**, sehingga privasi dan data perusahaan terjamin aman.
* **Multi-Upload:** Mendukung input hingga 5 foto sekaligus dalam satu sesi.
* **Peta Interaktif:** Terintegrasi dengan **OpenStreetMap** untuk memilih titik lokasi secara akurat.
* **Auto-Address:** Mengubah koordinat GPS menjadi alamat lengkap (Jalan, Kelurahan, Kota) secara otomatis.
* **Format Profesional:** Tampilan watermark rapi dengan garis pemisah kuning (mirip aplikasi Timemark).
* **Tanpa Instalasi:** Hanya butuh satu file HTML, bisa dijalankan tanpa internet kencang (hanya butuh sedikit data untuk memuat peta).

## 🚀 Cara Penggunaan

### A. Menjalankan Aplikasi
1.  Pastikan Anda memiliki file `app_tagging.html` (atau nama file yang Anda simpan).
2.  **Klik dua kali** file tersebut untuk membukanya di browser modern (Google Chrome, Microsoft Edge, Firefox, atau Safari).
3.  Pastikan perangkat terhubung ke internet untuk memuat Peta (Maps).

### B. Langkah-langkah Tagging
1.  **Upload Foto:** Klik tombol input file dan pilih foto (maksimal 5).
2.  **Atur Waktu:** Sesuaikan tanggal dan jam jika tidak ingin menggunakan waktu saat ini.
3.  **Tentukan Lokasi:**
    * Klik tombol **"🗺️ Peta"**.
    * Geser peta dan klik pada titik lokasi kejadian.
    * Klik "Gunakan Lokasi Ini". Alamat dan Koordinat akan terisi otomatis.
4.  **Edit Manual (Opsional):** Anda bisa menyunting teks alamat secara manual jika hasil otomatis kurang sesuai.
5.  **Proses:** Klik tombol hitam **"⚡ Proses Semua Foto"**.
6.  **Preview & Download:** Lihat hasil di layar, lalu klik tombol hijau **"✅ Download Hasil"** pada masing-masing foto.
7.  **Reset:** Gunakan tombol "🔄 Mulai Ulang" di bagian bawah atau klik tanda "X" pada foto untuk menghapus foto tertentu.

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan teknologi web standar tanpa *backend*:
* **HTML5 & Canvas API:** Untuk struktur dan pemrosesan gambar.
* **Bootstrap 5:** Untuk tampilan antarmuka (UI) yang responsif.
* **Leaflet.js:** Library peta interaktif.
* **OpenStreetMap (Nominatim):** Penyedia data peta dan layanan *reverse geocoding*.
* **Moment.js:** Untuk format tanggal dan waktu bahasa Indonesia.

## ⚠️ Disclaimer (Penafian)

> **Disclaimer:** Aplikasi ini dibuat untuk penyesuaian minor terhadap evident, tidak untuk tools utama. Tools utama harus diambil dari device masing-masing sesuai dengan tanggal dan waktu kejadian. Segala penyalahgunaan terhadap aplikasi ini di luar tanggung jawab pembuat.

---
*Dibuat untuk keperluan dokumentasi internal.*
