# 🥷 karashiBOT COMING SOON

> Multi-Platform Bot with OSINT, Automation & Fun Features

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Python](https://img.shields.io/badge/Python-3.9+-green)
![Platform](https://img.shields.io/badge/platform-Telegram%20%7C%20WhatsApp-orange)
![Status](https://img.shields.io/badge/status-Beta-yellow)

---

## 📌 Tentang Proyek

**karashiBOT** adalah bot multi-platform yang dirancang untuk memudahkan berbagai tugas, mulai dari pengumpulan informasi sumber terbuka (OSINT), otomatisasi, hingga hiburan. Bot ini berjalan di **Telegram** dan **WhatsApp**, dengan fokus utama pada kemudahan penggunaan dan kecepatan respon.

---

## ✨ Fitur Utama

### 🤖 Telegram

#### 1. OSINT Tools
Kumpulan alat untuk pencarian dan verifikasi data dari sumber terbuka.

| Perintah | Deskripsi |
|----------|-----------|
| `nomor_data` | Mencari informasi publik dari nomor telepon |
| `nomor_nik` | Mencari NIK (Nomor Induk Kependudukan) dari nomor telepon |
| `nik_parse` | Mengurai dan memvalidasi data dari NIK |
| `leak_nama` | Mengecek kebocoran data berdasarkan nama |
| `email_breach` | Mengecek apakah email pernah terlibat dalam kebocoran data |
| `gtc_nomor` | Get Contact - mencari informasi dari nomor/tag |
| `nik_nomor` | Mencari nomor telepon dari NIK |

#### 2. Spam OTP
- Total **12 API** yang terkumpul untuk keperluan testing dan simulasi OTP.
- ⚠️ *Hanya untuk tujuan edukasi dan pengujian keamanan.*

#### 3. Menu Track
- Tracking informasi publik seperti:
  - Nomor telepon
  - Alamat IP
  - Domain/Situs web

#### 4. Menu Lembaga
- Informasi dan data dari berbagai lembaga publik/instansi (terintegrasi dengan sumber terbuka).

---

### 💬 WhatsApp

#### 1. Generate Sticker
- Ubah gambar atau video menjadi stiker WhatsApp.
- Dukungan untuk stiker animasi (GIF).
- Mudah digunakan: kirim media + perintah `!sticker`.

---

## 🚀 Instalasi & Menjalankan Bot

### Prasyarat
- Python 3.9 atau lebih baru
- Telegram Bot Token (dari [@BotFather](https://t.me/BotFather))
- WhatsApp Device (untuk QR Code login)

### Langkah Instalasi

```bash
# Clone repositori
git clone https://github.com/yourusername/karashiBOT.git
cd karashiBOT

# Install dependensi
pip install -r requirements.txt

# Konfigurasi environment
cp .env.example .env
# Isi .env dengan token dan konfigurasi Anda

# Jalankan bot Telegram
python bot_telegram.py

# Jalankan bot WhatsApp (di terminal terpisah)
python bot_whatsapp.py
