<<<<<<< HEAD
# TugasPerkenalanAugmated
=======
# Tugas Praktikum: Scene Perkenalan Diri

* **Nama:** [Dinda Azzahra Lubis]
* **NIM:** [2309020337]
* **Link Demo (GitHub Pages):** https://azzahralubisdinda-rgb.github.io/TugasPerkenalanAugmated/

---

## Jawaban Pertanyaan Refleksi

1. **Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai z negatif?**
   Dalam sistem koordinat 3D A-Frame/WebXR, kamera awal berada di titik origin (0,0,0) dan secara default menghadap ke arah sumbu -Z. Oleh karena itu, agar objek berada tepat di depan pandangan pengguna saat pertama kali scene dibuka, koordinat posisi $Z$ objek harus bernilai negatif.

2. **Mengapa WebXR hanya aktif pada HTTPS atau localhost?**
   WebXR membutuhkan akses langsung ke perangkat keras sensor (seperti giroskop, VR headset, atau kamera AR) yang sensitif terhadap privasi dan keamanan pengguna. Oleh karena itu, browser menerapkan kebijakan keamanan ketat (*Secure Context*) di mana fitur ini hanya diizinkan berjalan di atas koneksi terenkripsi (HTTPS) atau lingkungan pengembangan lokal (`localhost`).

3. **Jelaskan perbedaan peran WebXR Device API, three.js, dan A-Frame dengan bahasa Anda sendiri.**
   * **WebXR Device API:** Menjadi jembatan tingkat rendah (*low-level API*) yang menghubungkan browser dengan perangkat keras VR/AR untuk menangani tracking posisi dan rendering tampilan stereo.
   * **Three.js:** Berperan sebagai *library* JavaScript 3D yang mempermudah pembuatan objek, tata cahaya, dan grafik 3D berbasis WebGL tanpa perlu menulis kode GPU/shader yang rumit.
   * **A-Frame:** Berperan sebagai *framework* tingkat tinggi berbasis HTML (*Entity-Component framework*) yang dibangun di atas three.js, memudahkan kita membuat scene 3D/VR secara deklaratif hanya dengan tag HTML sederhana.
>>>>>>> 523e093 (docs: menambahkan README dan jawaban refleksi)
