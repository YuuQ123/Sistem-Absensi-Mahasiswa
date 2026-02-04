# Sistem Absensi Mahasiswa dengan Blockchain

Sistem absensi digital berbasis QR Code dan pengenalan wajah dengan blockchain untuk keamanan data.

## 📋 Persyaratan
- Python 3.8+
- pip

## 🚀 Langkah-Langkah Instalasi

### 1. Masuk ke Folder Aplikasi
```bash
cd Sistem-Absensi-Mahasiswa
```

### 2. Buat Virtual Environment

**Windows:**
```bash
python -m venv venv
```

**macOS/Linux:**
```bash
python3 -m venv venv
```

### 3. Aktivasi Virtual Environment

**Windows:**
```bash
venv\Scripts\activate
```

**macOS/Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

## ▶️ Menjalankan Aplikasi

### 1. Pastikan Virtual Environment Aktif
```bash
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

### 2. Jalankan Aplikasi
```bash
python app.py
```

### 3. Buka di Browser
```
http://localhost:5000
```

## 📁 Struktur File
```
Sistem-Absensi-Mahasiswa/
├── app.py              # File utama
├── requirements.txt    # Daftar library
├── templates/          # Template HTML
├── static/             # CSS dan file statis
└── *.json              # Data (auto-generated)
```

## 📝 Dependencies
- Flask
- Pillow
- qrcode
- face-recognition
