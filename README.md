# 🛡️ Integrity System V5.2 — SMKN 1 MALTENG
> **Advanced Student Discipline Management & Digitalization Hub**

![Version](https://img.shields.io/badge/Version-5.2--Stable-blue)
![Architecture](https://img.shields.io/badge/Architecture-SOLID--SPA-green)
![Theme](https://img.shields.io/badge/Theme-Dual--Adaptive-orange)
![Storage](https://img.shields.io/badge/Storage-LocalStorage-red)

**Integrity System** adalah aplikasi manajemen data pelanggaran siswa berbasis web (Single Page Application) yang dirancang secara presisi untuk membantu pihak kesiswaan SMKN 1 Malteng. Sistem ini mendigitalisasi proses pemantauan razia perangkat seluler (HP) dengan efisiensi tinggi dan integritas data maksimal.

---

## 🚀 Overview: Solusi Modern vs Manual
Aplikasi ini hadir sebagai solusi strategis untuk menggantikan metode pencatatan konvensional yang sering mengalami kendala *data loss* (a.k.a. kehilangan data) dan sulitnya sinkronisasi riwayat pelanggaran.

* **Reliability:** Data tersimpan secara persisten di level client.
* **Accessibility:** Akses instan di berbagai perangkat tanpa hambatan server.
* **Decision Making:** Memberikan wawasan berbasis data bagi guru kesiswaan untuk tindakan kedisiplinan yang objektif.

---

## 💎 Fitur Utama (Core Modules)

### 📊 Live Monitoring & Dashboard Statistik
Menyajikan visualisasi data real-time untuk pemantauan cepat:
* **Total Records:** Agregasi seluruh riwayat pelanggaran.
* **Current Custody (Disita):** Monitoring aktif perangkat yang masih berada di ruang kesiswaan.
* **Historical Logs (Catatan):** Arsip penyelesaian masalah tanpa penyitaan fisik.

### 🏷️ Smart Badge System (Status Otomatis)
Sistem menggunakan logika kondisional untuk memberikan label status visual:
* 🔴 **Sitaan:** Indikator perangkat dalam pengamanan fisik.
* 🟢 **Clear:** Masalah terselesaikan secara administratif dan fisik.
* ⚪ **Recorded:** Pencatatan riwayat pelanggaran sebagai database peringatan.

### ⚡ Pencarian Progresif & Instant Filter
Mengimplementasikan **Instant Search** (a.k.a. pencarian langsung saat mengetik) yang memungkinkan petugas menemukan data siswa berdasarkan Nama atau Kelas dalam milidetik tanpa memuat ulang halaman (Zero-Refresh).

---

## 🧠 Integrasi Cerdas (Smart Features)

### 📱 Automated WhatsApp Bridge
Menghubungkan sekolah dengan orang tua siswa secara otomatis:
* **Threshold Trigger:** Tombol kontak WhatsApp hanya muncul jika siswa mencapai ambang batas minimal 3 kali pelanggaran.
* **Pre-filled Templates:** Mempercepat pengiriman laporan peringatan kepada nomor orang tua yang terdaftar.

### 💾 Data Integrity Hub (Import/Export)
Fungsi manajemen database mandiri yang mematuhi prinsip **SOLID** (a.k.a. lima prinsip desain agar software mudah dikelola):
* **Full Backup (.json):** Ekspor seluruh database lokal untuk cadangan eksternal.
* **Data Recovery:** Impor kembali data lama setelah pembersihan browser atau migrasi perangkat tanpa kehilangan satu pun entri data.

---

## 🏗️ Arsitektur & Integritas Kode
Sistem ini dibangun dengan fondasi yang kokoh untuk memastikan stabilitas:

1.  **OOP (Object-Oriented Programming):** Logika bisnis dipisahkan secara modular untuk memudahkan pembaruan fitur di masa depan.
2.  **DRY (Don't Repeat Yourself):** Optimasi baris kode guna mencegah duplikasi fungsi dan meningkatkan kecepatan eksekusi.
3.  **Atomic Persistence:** Menggunakan **LocalStorage** (a.k.a. penyimpanan data di memori browser) untuk menjamin data tetap ada meskipun koneksi internet terputus.
4.  **Dual-Theme Engine:** Mendukung Dark Mode dan Light Mode yang adaptif terhadap kondisi pencahayaan pengguna.

---

## 🎨 Toggle Theme Preview
Sistem menyediakan antarmuka yang fleksibel:
* **Light Mode:** Optimal untuk penggunaan di siang hari di ruang terbuka.
* **Dark Mode:** Meminimalkan ketegangan mata saat penggunaan di dalam ruangan atau kondisi cahaya rendah.

---

### 🛡️ Integritas Proyek
Dikembangkan dengan standar presisi tinggi untuk mendukung transformasi digital di lingkungan **SMKN 1 Malteng**.

&copy; 2026 Integrity System Project. All Rights Reserved.
