# SmartHR - Sistem Manajemen Pegawai Berbasis AI

## 📌 Deskripsi Proyek
**SmartHR** adalah sistem manajemen sumber daya manusia berbasis AI yang dirancang untuk membantu organisasi pemerintah atau perusahaan dalam mengelola data pegawai secara efisien. Sistem ini menggabungkan teknologi **SQL database**, **vector embedding**, dan **Retrieval-Augmented Generation (RAG)** untuk menyediakan solusi pencarian dan analisis data pegawai yang cerdas.

## ✨ Fitur Utama
- **Manajemen Database Pegawai**  
  Penyimpanan terstruktur data pegawai menggunakan **SQLite**
  
- **Pencarian Semantik**  
  Pencarian cerdas berbasis embedding dan **vector database** (ChromaDB)

- **Analisis Kebutuhan Pelatihan**  
  Rekomendasi pelatihan berdasarkan profil pegawai
  
- **Antarmuka Interaktif**  
  Dashboard visual dan user-friendly dengan **Streamlit**

- **Optimasi Prompt**  
  Tiga tingkat kecerdasan dalam menjawab pertanyaan HR melalui LLM

## 🛠️ Teknologi yang Digunakan
- **Bahasa Pemrograman**: Python  
- **Database**: SQLite, ChromaDB  
- **Embedding Model**: Sentence Transformers, Google Generative AI  
- **LLM**: Gemini 2.5 Pro  
- **Framework**: LangChain, Streamlit  
- **Infrastruktur Demo**: Ngrok  

## 🚀 Cara Menjalankan

### Persyaratan
- Python 3.8+

### Instalasi

1. **Clone repositori**
    ```bash
    git clone https://github.com/username/SmartHR.git
    cd SmartHR
    ```

2. **(Opsional) Buat virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate      # Linux/Mac
    venv\Scripts\activate         # Windows
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

### Menjalankan Aplikasi

- **Versi CLI**
    ```bash
    python main.py
    ```

- **Versi Streamlit**
    ```bash
    streamlit run app.py
    ```

- **Akses via Ngrok**
    > Setelah Streamlit berjalan:
    ```bash
    ngrok http 8501
    ```

## 📝 Contoh Penggunaan

### 🔍 Pencarian Pegawai
- `"Tampilkan semua pegawai di BPS dengan pengalaman >5 tahun"`
- `"Siapa yang memiliki spesialisasi Data Science?"`

### 📊 Analisis Kebutuhan
- `"Analisis kebutuhan pelatihan AI untuk pegawai"`
- `"Rekomendasi pelatihan untuk staf Diskominfo"`

### 🧾 Manajemen Data
- Filter pegawai berdasarkan **unit kerja**, **pendidikan**, atau **pengalaman**
- Ekspor data ke **CSV**

---

> Dibuat untuk keperluan seleksi AI Engineer Test - #SealAIEngineerTest 🚀
