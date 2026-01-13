# Learning GitHub Foundations (Microsoft Learn)

📘 **Repository pembelajaran Sertifikasi GitHub Foundations** melalui **Microsoft Learn**.  
Repository ini berisi rangkuman materi, praktik langsung, dan eksperimen penggunaan GitHub untuk kolaborasi serta pengelolaan proyek.

---

## 🎯 Tujuan Pembelajaran
- Memahami konsep dasar Git dan GitHub  
- Mengelola repositori dan perubahan kode  
- Berkolaborasi menggunakan fitur GitHub  
- Mengenal fitur produktivitas, keamanan, dan skala GitHub Enterprise  

---
## 📁 Repositori

Repositori menyimpan seluruh file proyek dan riwayat perubahannya. Digunakan untuk:
- Mengelola proyek  
- Melacak perubahan  
- Kolaborasi tim  

### Fungsi Dasar Repositori
- Membuat repositori  
- Mengkloning repositori  
- Menambahkan file dan melakukan commit  

---

## ✂️ Gist

Gist adalah repositori mini untuk berbagi cuplikan kode atau catatan kecil.

**Fitur utama:**
- Publik atau rahasia *(tidak sepenuhnya privat)*  
- Mendukung versioning  
- Bisa di-*fork* dan di-*clone*  

### 🔗 Latihan Gist
📌 Contoh latihan membuat Gist:  
👉 https://gist.github.com/knyoman/d8571bf726513cd3e79645a6738de9eb  

⚠️ **Catatan Penting:**  
> Jangan pernah menyimpan data sensitif (password, API key, secret) di Gist.

---

## 📚 Wiki

Wiki digunakan untuk dokumentasi panjang proyek, seperti:
- Panduan penggunaan  
- Penjelasan desain dan arsitektur  
- Dokumentasi tambahan di luar README  

### 🔗 Latihan Wiki
📌 Repository Wiki latihan:  
👉 https://github.com/knyoman/Learning_GitHub-Foundations_Microsoft.wiki.git  

---

## 🔄 GitHub Flow

### Pengertian GitHub Flow
GitHub Flow adalah alur kerja pengembangan perangkat lunak yang sederhana dan fleksibel untuk mengelola perubahan kode secara aman dan kolaboratif. Alur ini memanfaatkan **branch**, **commit**, dan **pull request** sebagai inti proses kerja di GitHub.

---

### 🧩 Komponen Utama GitHub Flow
- **Branch**  
  Digunakan untuk membuat dan mengisolasi perubahan dari cabang utama (*main*).

- **Commit**  
  Menyimpan perubahan kode secara bertahap dengan pesan yang jelas.

- **Pull Request (PR)**  
  Digunakan untuk meninjau, mendiskusikan, dan menggabungkan perubahan kode.

- **Merge**  
  Proses menggabungkan perubahan dari branch ke cabang utama (*main*).

---

### 🔁 Alur GitHub Flow
1. Membuat branch baru dari cabang utama (*main*)  
2. Melakukan perubahan dan commit di branch tersebut  
3. Membuka pull request untuk meminta peninjauan (*review*)  
4. Meninjau dan memperbaiki kode berdasarkan masukan  
5. Menggabungkan (*merge*) perubahan ke cabang utama  
6. Menghapus branch yang sudah tidak digunakan  

---

## 🤝 GitHub sebagai Platform Kolaboratif

GitHub mendukung kolaborasi tim melalui berbagai fitur seperti **Repositories**, **Pull Requests**, **Issues**, dan **Discussions** untuk mengelola pekerjaan, komunikasi, dan pengembangan proyek secara terstruktur.

---

## 🐞 GitHub Issues

GitHub Issues digunakan untuk melacak dan mengelola pekerjaan dalam proyek, seperti:
- Ide  
- Tugas  
- Bug  
- Umpan balik  

### Fungsi Utama Issues
- Mendokumentasikan pekerjaan yang perlu ditindaklanjuti  
- Dapat diberi **label**, **assignee**, dan **milestone**  
- Dapat dibuat dari:
  - Kode
  - Komentar
  - Task list
  - Repositori  

Issues membantu tim menjaga pekerjaan tetap terorganisir dan mudah dipantau.

---

## 💬 GitHub Discussions

GitHub Discussions digunakan untuk komunikasi yang bersifat terbuka dan tidak langsung terkait dengan perubahan kode, seperti:
- Tanya jawab (Q&A)  
- Diskusi umum  
- Ide dan masukan  
- Pengumuman komunitas  

### Ciri Utama Discussions
- Tidak langsung terkait kode  
- Berbasis kategori (Announcement, Q&A, Ideas, dll.)  
- Mendukung percakapan komunitas secara terbuka  

---

## 🔗 Hubungan Issues dan Discussions

- **Discussions** → Digunakan untuk percakapan dan pertukaran ide  
- **Issues** → Digunakan untuk pekerjaan yang perlu dilacak dan diselesaikan  
- Diskusi dapat **dikonversi menjadi Issue** jika memerlukan tindak lanjut teknis  

Pendekatan ini membantu memisahkan antara diskusi dan pekerjaan nyata secara jelas dan efisien.

--- 

---

## 📌 Ringkasan Aktivitas GitHub

Pada latihan **Introduction to GitHub**, saya telah melakukan beberapa aktivitas berikut:

- Membuat dan mengelola repository GitHub  
- Membuat branch untuk pengembangan terpisah  
- Melakukan commit perubahan pada file `README.md`  
- Membuat Pull Request (PR) dari branch ke `main`  
- Melakukan merge Pull Request sesuai workflow GitHub  
- Memahami perbedaan:
  - Repository pribadi  
  - Fork  
  - Open-source workflow  

### 🔗 Repository Latihan
📌 Praktik GitHub Skills – Introduction to GitHub:  
👉 https://github.com/knyoman/introduction-to-github.git  

Latihan ini membantu saya memahami alur kerja dasar GitHub yang umum digunakan dalam kolaborasi tim dan pengembangan perangkat lunak modern.

---

## 🔐 Pemindaian Kode (Code Scanning)

### Pengertian
Pemindaian kode adalah fitur keamanan GitHub yang menggunakan **CodeQL** untuk menganalisis kode dan mendeteksi kerentanan keamanan serta kesalahan pengkodean.

---

### Tujuan
- Menemukan masalah keamanan lebih awal  
- Mencegah bug dan kerentanan baru  
- Menampilkan peringatan di tab **Security** repositori  

---

### CodeQL
- Mesin analisis kode milik GitHub  
- Memperlakukan kode sebagai data  
- Mendukung berbagai bahasa pemrograman  

---

### Cara Kerja
- Berjalan otomatis melalui **GitHub Actions**  
- Dipicu oleh *push*, *pull request*, atau jadwal tertentu  

---
## 🔐 Pemindaian Kode dengan Alat Pihak Ketiga

- Analisis kode dilakukan di luar GitHub  
- Hasil pemindaian diunggah ke GitHub dalam format **SARIF (v2.1.0)**  
- Peringatan tetap ditampilkan di tab **Security**  

### Cara Upload SARIF
- Code Scanning API  
- CodeQL CLI  
- GitHub Actions (`upload-sarif`)  

### Batasan
- Maksimum 5.000 hasil pemindaian  
- Ukuran file maksimal 10 MB  

**Intinya:**  
Scan eksternal + upload SARIF = keamanan tetap terpantau di GitHub  

---


## 🧭 Catatan
Repository ini dibuat sebagai bagian dari proses belajar dan latihan 
**GitHub Foundations Certification – Microsoft Learn**.
