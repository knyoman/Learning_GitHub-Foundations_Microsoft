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

## 🚀 Cara Memulai Kontribusi Open Source

Di GitHub, semua orang dapat berkontribusi ke proyek open source, baik pemula maupun profesional.

---

### Menemukan Proyek

- Mulai dari proyek yang sudah atau ingin digunakan  
- Gunakan **GitHub Search** dan **Topics**  
- Pilih proyek dengan komunitas yang aktif  

---

### Mengenal Proyek

Periksa dokumen penting:

- **LICENSE** → memastikan proyek bersifat open source  
- **README** → gambaran dan tujuan proyek  
- **CONTRIBUTING** → panduan kontribusi  
- **CODE_OF_CONDUCT** → aturan komunitas  

---

### Menemukan Tugas

- Buka tab **Issues** atau halaman `/contribute`  
- Cari label:
  - `good first issue`  
  - `help wanted`  
  - `beginner-friendly`  

---

### Bentuk Kontribusi

- Memperbaiki bug, dokumentasi, atau typo  
- Berpartisipasi dalam diskusi Issue atau Pull Request  
- Mendukung proyek melalui **GitHub Sponsors**  

---

**Intinya:**  
Semua kontribusi itu berharga—mulai dari hal kecil, pahami komunitas, dan berani membantu.

---

## 🌍 Inti Kontribusi Open Source

Kontribusi open source di GitHub menekankan **komunikasi**, **kolaborasi**, dan **kesabaran** agar perubahan dapat diterima oleh pemilik proyek.

---

### Langkah Utama Kontribusi

**1. Komunikasikan Niat**

- Cek issue yang sudah ada  
- Beri komentar atau buat issue baru sebelum mulai bekerja  

**2. Siapkan Pull Request (PR)**

- Fork repositori  
- Clone ke lokal atau gunakan Codespaces  
- Buat branch terpisah *(disarankan)*  
- Commit dan push perubahan  
- Buat Pull Request  

**3. Ikuti Proses Review**

- Lengkapi deskripsi PR dan tautkan issue terkait  
- Pastikan lolos status checks (CI/test)  
- Tanggapi komentar dari reviewer  

---

### Hasil Review

- PR disetujui dan digabung (*merged*)  
- PR perlu revisi  
- PR ditutup jika tidak sesuai  

---

### Praktik Terbaik

- Terbuka terhadap umpan balik  
- Sabar menunggu respons  
- Diskusi dilakukan secara publik  
- Hormati *code of conduct* proyek  


---

**Intinya:**  
Komunikasi yang baik dan Pull Request yang jelas meningkatkan peluang kontribusi diterima.

---

### 🔗 Praktek Kontribusi
👉 <https://gist.github.com/knyoman/d8571bf726513cd3e79645a6738de9eb> >

---

## ✍️ Menulis Commit & Pull Request yang Baik

Kualitas Pull Request (PR) sangat dipengaruhi oleh cara menjelaskan perubahan yang dibuat.

---

### Praktik Utama

**Judul Commit / PR**
- Gunakan bentuk imperatif & present tense  
  *(contoh: `Add feature`, bukan `Added feature`)*  
- Maksimal 50 karakter  
- Huruf kapital di awal, tanpa tanda titik  

**Deskripsi Pull Request**
- Jelaskan **apa** dan **mengapa** perubahan dibuat  
- Bandingkan perilaku sebelum dan sesudah perubahan  

---

### Granularitas & Metadata
- Kirim perubahan kecil dan terfokus  
- Tambahkan:
  - Reviewer / assignee  
  - Label (Bug, Documentation, Enhancement, dll.)  
  - Tautan Issue agar PR dapat menutup issue otomatis  

---

### Latihan Praktik
- Gunakan proyek **First Contributions**  
- Alur latihan: *fork → clone → commit → pull request*  
- Ikuti `CONTRIBUTING.md` atau template PR jika tersedia  

---

**Intinya:**  
Pull Request yang jelas, ringkas, dan terstruktur lebih mudah ditinjau dan lebih cepat digabung.

---

## ✅ Inti Membuat Pull Request (PR) yang Baik

Di GitHub, kualitas PR dinilai dari **kejelasan perubahan** dan **komunikasi yang efektif**.

---

### Praktik Utama

**Judul Commit / PR**
- Gunakan bentuk imperatif & present tense  
  *(contoh: `Add feature`, bukan `Added feature`)*  
- Maksimal 50 karakter  
- Huruf kapital di awal, tanpa tanda titik  

**Deskripsi Pull Request**
- Jelaskan **apa** dan **mengapa** perubahan dibuat  
- Bandingkan kondisi **sebelum vs sesudah**  
- Buat perubahan kecil dan terfokus agar mudah ditinjau  

---

### Tambahan Penting
- Tambahkan **reviewer** atau **assignee**  
- Gunakan **label** (Bug, Documentation, Enhancement, dll.)  
- Tautkan **issue terkait** agar dapat *auto-close*  
- Atur notifikasi PR sesuai kebutuhan  

---

### Latihan
- Gunakan proyek **First Contributions**  
- Alur praktik: *fork → clone → commit → pull request*  

---

**Intinya:**  
PR yang jelas, ringkas, dan terstruktur meningkatkan peluang untuk di-*merge*.

---

## 🔐 Pentingnya Keamanan Repositori

Keamanan repositori harus diterapkan sejak awal (*shift left*) untuk mencegah kebocoran data, perubahan tidak sah, dan pelanggaran regulasi.

---

### Fitur Keamanan Utama di GitHub
Melalui tab **Security**, GitHub menyediakan:
- **SECURITY.md** → panduan pelaporan celah keamanan  
- **Dependabot alerts** → deteksi dependensi rentan  
- **Security Advisories** → diskusi & publikasi kerentanan (CVE)  
- **Code scanning** → deteksi bug dan celah keamanan  
- **Secret scanning** → mencegah kebocoran token/kredensial  

---

### Praktik Keamanan Penting
- Gunakan **.gitignore** untuk mencegah file sensitif ter-*commit*  
- Hapus data sensitif dengan benar *(anggap data yang pernah di-*commit* sudah bocor)*  
- Terapkan **branch protection rules**:
  - Wajib Pull Request  
  - Wajib review  
  - Wajib lulus status checks  
- Gunakan **required reviewers** untuk mencegah *merge* tanpa review  
- Atur **CODEOWNERS** untuk menentukan penanggung jawab review kode  

---

**Intinya:**  
Repositori yang aman adalah hasil dari kombinasi proses, kebijakan, dan otomatisasi keamanan yang diterapkan sejak awal dan dijalankan secara konsisten.

---

## 🤖 Keamanan Otomatis di Repositori

Di GitHub, keamanan dapat diautomatisasi untuk mengurangi risiko dan beban kerja manual.

---

### Fitur Utama

- **Dependency Graph**  
  Melacak seluruh dependensi proyek secara otomatis  

- **Dependabot Alerts**  
  Mendeteksi dependensi yang memiliki kerentanan keamanan  

- **Dependabot Updates**  
  Membuat Pull Request otomatis untuk memperbarui dependensi rentan  

- **Code Scanning (CodeQL)**  
  Menganalisis kode untuk menemukan bug dan celah keamanan  

- **Secret Scanning**  
  Mendeteksi token, API key, dan kredensial yang bocor  

---

**Intinya:**  
Otomatisasi keamanan membantu mendeteksi, memperbaiki, dan mencegah risiko keamanan sejak dini tanpa memperlambat proses pengembangan.

---

## 🛡️ Exercise – Secure Your Repository’s Supply Chain

### Tujuan Latihan
Mengamankan *software supply chain* repositori di GitHub menggunakan fitur keamanan dependensi.

---

### Fitur yang Digunakan
- **Dependency Graph** → memetakan dependensi proyek  
- **Dependabot Alerts** → mendeteksi dependensi rentan  
- **Dependency Security Updates** → Pull Request otomatis untuk perbaikan keamanan  
- **Dependency Version Updates** → menjaga versi dependensi tetap terbaru  

---

### Tips Mengerjakan
- Baca **README** repositori latihan  
- Ikuti instruksi **How to start**  
- Periksa hasil di tab **Actions → Grading workflow**  
- Jangan mengubah file `.github/workflows/grading.yml`  

---

**Intinya:**  
Mengamankan dependensi berarti mencegah risiko keamanan sejak sumbernya secara otomatis dan terukur.

---

## 🛠️ GitHub Administration

### Pengertian
Administrasi GitHub bertujuan memastikan kolaborasi, akses, dan keamanan berjalan lancar melalui pengelolaan **team**, **organization**, dan **enterprise**.

---

### Level Administrasi

#### 1️⃣ Team Level
- Mengelola anggota dan izin repositori secara granular  
- Mendukung *nested teams* dan *team sync* dengan IdP (misalnya Microsoft Entra ID)  
- Mengatur review Pull Request, diskusi tim, dan notifikasi  

**Best Practices:**
- Susun tim sesuai struktur organisasi  
- Buat tim berbasis keahlian  
- Aktifkan sinkronisasi IdP untuk onboarding/offboarding otomatis  

---

#### 2️⃣ Organization Level
- Mengelola anggota, tim, dan kolaborator eksternal  
- Mengatur izin repositori dan keamanan organisasi  
- Mengelola billing dan kebijakan organisasi  

📌 *Disarankan menggunakan satu organisasi untuk mengurangi kompleksitas.*

---

#### 3️⃣ Enterprise Level
- Manajemen terpusat lintas organisasi  
- SSO (SAML), kebijakan keamanan global, billing terpusat  
- Integrasi GitHub Enterprise Server dengan GitHub.com  

---

**Intinya:**  
Administrasi GitHub yang efektif membutuhkan pengelolaan akses bertingkat, sinkronisasi identitas, dan kebijakan terpusat untuk kolaborasi yang aman dan efisien.

---




