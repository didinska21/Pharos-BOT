# Pharos BOT

Pharos BOT adalah bot otomatis berbasis Python untuk interaksi dengan blockchain (seperti swap, liquidity, dll). Repositori ini menyediakan script dan konfigurasi yang mudah digunakan untuk menjalankan bot dengan cepat.

---

## Prasyarat

- Python 3.12 telah terpasang
- `git` telah terinstal
- Akses terminal (Linux/WSL/Mac)
- Private key wallet EVM kamu

---

## Instalasi

1. **Clone repositori**
   ```bash
   git clone https://github.com/didinska21/Pharos-BOT.git
   cd Pharos-BOT
   ```

2. **Install `venv` untuk Python 3.12**
   ```bash
   sudo apt install python3.12-venv
   ```

3. **Buat virtual environment**
   ```bash
   python3 -m venv venv
   ```

4. **Aktifkan virtual environment**
   ```bash
   source venv/bin/activate
   ```

5. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

6. **Masukkan Private Key ke `accounts.txt`**
   ```bash
   echo "0xPRIVATEKEYKAMU" >> accounts.txt
   ```

   > Gantilah `0xPRIVATEKEYKAMU` dengan private key asli kamu.  
   > ¸ **JANGAN share file ini ke publik atau upload ke GitHub.**

---

## Menjalankan Bot

Setelah semua langkah selesai:

```bash
python main.py
```

---

## Keamanan

Untuk keamanan, **jangan pernah commit file `accounts.txt` atau data private ke repositori.**

Tambahkan file berikut ke `.gitignore`:

```
accounts.txt
```

---

## Lisensi

MIT License.  
Silakan digunakan dan dimodifikasi sesuai kebutuhan.

---
