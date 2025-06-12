# 🚀 Tutorial: Membuat ChatGPT Tanpa Internet dengan Streamlit + Ollama

Dengan tutorial ini, kamu akan belajar membuat chatbot ChatGPT yang bisa dijalankan tanpa koneksi internet menggunakan model lokal seperti LLaMA 3.1 8B melalui Ollama, dan UI menggunakan Streamlit.

## 📦 Persiapan Awal

1. Pastikan Python Terinstal

Pastikan Python versi 3.8 atau lebih baru telah terinstal. Cek di cmd dengan:

`python --version`

## 🐍 Buat Virtual Environment

2. Buat dan Aktifkan Virtual Environment

```
# Membuat virtual environment
python -m venv venv

# Aktifkan (Windows)
venv\Scripts\activate

# Aktifkan (macOS/Linux)
source venv/bin/activate
```

## 📜 Buat requirements.txt

3. Isi `requirements.txt` seperti berikut:
```
streamlit
ollama
```

4. Install Dependencies
```
pip install -r requirements.txt
```

## 🤖 Install dan Jalankan Ollama

5. Install Ollama

Download dan install Ollama di [download ollama](https://ollama.com/download) sesuai OS kamu.

6. Jalankan Model llama3.1:8b atau llama3.2:1b (untuk versi yang lebih ringan)
```
ollama run llama3.1:8b
```
> Catatan: Pastikan kamu memiliki spesifikasi PC yang cukup (RAM > 8GB disarankan). Kamu juga bisa memilih model lain seperti llama2, mistral, gemma, dll, cek di [library ollama](https://www.ollama.com/library)

## ▶️ Jalankan Aplikasi

7. Jalankan Streamlit App
```
streamlit run main.py
```

## 📝 Hasil

- Tampilan sederhana chat seperti ChatGPT
- Model dijalankan 100% secara lokal, tidak memerlukan koneksi internet

# 📲 Ingin update tips coding, AI tools, dan teknologi terbaru lainnya?

Follow kami di sosial media:

👉 Instagram: @inticoding  
👉 TikTok: @inticoding  
👉 Threads: @inticoding  

# Jangan lewatkan konten menarik lainnya! 🚀💻