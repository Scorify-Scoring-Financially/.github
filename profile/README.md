# 🚀 Scorify – Predictive Lead Scoring for Banking Sales Organization

![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square&logo=dependabot&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Web_App-blue?style=flat-square&logo=google-chrome&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Enabled-orange?style=flat-square&logo=tensorflow&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-Framework-black?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-Library-61DAFB?style=flat-square&logo=react&logoColor=black)

## 📌 Ringkasan Proyek
**Selamat datang di Scorify!**

Scorify adalah aplikasi web yang dirancang untuk membantu tim *sales* perbankan bekerja lebih efisien dalam menentukan calon nasabah (*lead*) yang memiliki potensi konversi tertinggi. Dengan memanfaatkan model Machine Learning, sistem ini memberikan **skor prediksi** untuk setiap calon nasabah, sehingga proses prioritas menjadi lebih cepat, terarah, dan berbasis data.

Aplikasi ini menyajikan daftar calon nasabah yang telah diurutkan secara otomatis berdasarkan tingkat prioritas, lengkap dengan fitur panggilan langsung, pencatatan status interaksi, serta integrasi API untuk melakukan prediksi secara *realtime*. Scorify hadir sebagai solusi praktis bagi tim *sales* untuk meningkatkan produktivitas, efektivitas penawaran, dan akurasi dalam pengambilan keputusan.

---

## 📦 Struktur Repositori Organisasi

Organisasi **Scorify** di GitHub memisahkan kode aplikasi dan layanan model Machine Learning menjadi dua repositori utama untuk mempermudah pengembangan, *deployment*, dan pemeliharaan:

### 1. 🌐 Scorify
> Repositori Utama (Front-End & Back-End Application)

Repositori ini mencakup seluruh *stack* aplikasi web, dibangun di atas **Next.js**.

| Komponen | Teknologi Utama | Deskripsi |
| :--- | :--- | :--- |
| **Front-End** | React.js, Next.js, Tailwind CSS, Axios | UI/UX responsif untuk Sales dan Admin, termasuk Dashboard, sistem Direct Call, dan Laporan. |
| **Back-End** | Next.js API Routes, Prisma, PostgreSQL, JWT | Logika bisnis, Autentikasi/Otorisasi, manajemen data nasabah, dan *endpoint* untuk integrasi. |
| **Integrasi** | Axios | Menghubungkan aplikasi utama ke layanan model prediksi di `ML-Cloud-Backend`. |

**[👉 Kunjungi Repo Scorify (Aplikasi)](https://github.com/Scorify-Scoring-Financially/Scorify)**

<br>

### 2. 🧠 ML-Cloud-Backend
> Repositori Layanan Model Machine Learning (API Prediction)

Repositori ini fokus pada *deployment* model yang sudah terlatih sebagai layanan API independen.

| Komponen | Teknologi Utama | Deskripsi |
| :--- | :--- | :--- |
| **Model** | Logistic Regression, XGBoost | Model yang terlatih berdasarkan Bank Marketing Dataset. |
| **Penyajian** | Python Framework | Menyediakan *endpoint* API yang stabil dan efisien untuk menerima data nasabah dan mengembalikan skor prioritas. |

**[👉 Kunjungi Repo ML-Cloud-Backend (Model)](https://github.com/Scorify-Scoring-Financially/ML-Cloud-Backend)**

---

## 🛠 Fitur Utama Scorify

* **Dashboard Sales:** Menampilkan daftar nasabah yang sudah diurutkan otomatis berdasarkan skor prioritas (Hijau/Kuning/Merah).
* **Direct Call System:** Fitur panggilan langsung dan pencatatan hasil interaksi (*Berhasil/Tidak berhasil*, *Setuju/Tidak setuju*).
* **Tracking Interaksi:** Menyimpan histori interaksi untuk pelacakan performa individu Sales.
* **Integrasi Machine Learning:** Skor prediksi real-time melalui API dengan model **Logistic Regression & XGBoost**.
* **Manajemen Admin:** Fitur untuk mengelola akun Sales, filter data per Sales, dan melihat laporan performa tim.

---

## 🎬 Dokumentasi & Akses Cepat

| Deskripsi | Tautan |
| :--- | :--- |
| 🌐 **Website Demo** | [Click Here](https://scorify-two.vercel.app/) |
| 📖 **Notebook Pengembangan ML** | [Buka Notebook Google Colab](https://colab.research.google.com/drive/1r5zFDuOx5J5awtuLxa4hjYeGk3Hgi347?usp=sharing) |
| 📁 **Download File Model Terlatih** | [Google Drive](https://drive.google.com/drive/folders/1DT857d-xcnRz_UuIdplyAPIPrYMk97sf?usp=sharing) |
| 📊 **Sumber Dataset (Bank Marketing)** | [UCI Archive](https://archive.ics.uci.edu/dataset/222/bank+marketing) |
| 🎥 **Video Demo** | *(Akan diisi nanti)* |

---

## 👥 Tim Pengembang (ID Tim : A25-CS067)

| Nama | ID Anggota | Learning Path |
| :--- | :--- | :--- |
| Adinda Rahma Yuni Sumarlin | R891D5X0048 | React & Back End Developer with AI |
| Alif Jovani Safik | M891D5Y0162 | Machine Learning |
| Muhammad Dwi Khadafi | R891D5Y1237 | React & Back End Developer with AI |
| Muhammad Naufal Saputra | R193D5Y1332 | React & Back End Developer with AI |
| Shafa Aqilah Fahdah | M299D5X1833 | Machine Learning |
