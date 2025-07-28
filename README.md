# SealAIEngineerTest

SmartHR - Sistem Manajemen Pegawai Berbasis AI
📌 Deskripsi Proyek
SmartHR adalah sistem manajemen sumber daya manusia berbasis AI yang dirancang untuk membantu organisasi pemerintah atau perusahaan dalam mengelola data pegawai secara efisien. Sistem ini menggabungkan teknologi database SQL, vector embedding, dan Retrieval-Augmented Generation (RAG) untuk menyediakan solusi pencarian dan analisis data pegawai yang cerdas.

✨ Fitur Utama
Manajemen Database Pegawai: Penyimpanan terstruktur data pegawai dengan SQLite

Pencarian Semantik: Kemampuan pencarian cerdas menggunakan teknologi embedding dan vector database

Analisis Kebutuhan Pelatihan: Rekomendasi pelatihan berbasis profil pegawai

Antarmuka Interaktif: Dashboard Streamlit yang user-friendly

Optimasi Prompt: Tiga level kecerdasan dalam menjawab pertanyaan HR

🛠️ Teknologi yang Digunakan
Bahasa Pemrograman: Python

Database: SQLite, ChromaDB

Embedding Model: Sentence Transformer, Google Generative AI

LLM: Gemini 2.5 Pro

Framework: LangChain, Streamlit

Infrastruktur: Ngrok (untuk demo)

🚀 Cara Menjalankan
Persyaratan
Python 3.8+

Library yang diperlukan (lihat requirements.txt)

Instalasi
Clone repositori ini

bash
git clone https://github.com/username/SmartHR.git
cd SmartHR
Buat virtual environment (opsional)

bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
Install dependencies

bash
pip install -r requirements.txt
Menjalankan Aplikasi
Untuk versi CLI:

bash
python main.py
Untuk versi Streamlit:

bash
streamlit run app.py
Untuk mengakses via ngrok (setelah Streamlit berjalan):

bash
ngrok http 8501
