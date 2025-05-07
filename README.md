# Pencarian dan Eksplor Data Cuaca BMKG

Aplikasi web sederhana yang menyajikan informasi cuaca berdasarkan data dari BMKG. Dibangun menggunakan Python (Flask) dan dilengkapi dengan antarmuka pengguna berbasis HTML/CSS.

## Struktur Direktori

```
Bot Informasi Cuaca BMKG/
│
├── output/               # Folder output, bisa berisi hasil ekspor atau file sementara
├── static/               # File statis seperti CSS, JS, gambar
├── templates/            # Template HTML (untuk Flask)
├── app.py                # File utama aplikasi Flask
├── requirements.txt      # Daftar dependensi Python
└── vercel.json           # Konfigurasi untuk deployment di Vercel
```

## Fitur

- Menampilkan informasi cuaca berdasarkan wilayah dari data BMKG
- Tampilan antarmuka yang sederhana dan responsif
- Mendukung ekspor hasil pencarian
- Siap untuk di-deploy ke Vercel

## Cara Menjalankan Aplikasi

1. **Aktifkan virtual environment (opsional tapi disarankan):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Untuk Linux/Mac
   venv\Scripts\activate     # Untuk Windows
   ```

2. **Install dependensi:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Jalankan aplikasi:**

   ```bash
   python app.py
   ```

4. **Akses melalui browser:**
   Buka `http://127.0.0.1:5000/`

## Deployment ke Vercel

Pastikan file `vercel.json` telah dikonfigurasi dengan benar untuk deployment. Ikuti dokumentasi resmi Vercel untuk Flask [di sini](https://vercel.com/docs/concepts/functions/serverless-functions/python).

## Lisensi

Proyek ini bersifat open-source dan dilisensikan di bawah MIT License.

# pencarian-dan-eksplor-data-cuaca

> > > > > > > b1198fbfb9f0c097b41836d3208a5b3701b6ebe2
