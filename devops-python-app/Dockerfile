# Gunakan image python resmi
FROM python:3.10-slim

# Tentukan direktori kerja di dalam container
WORKDIR /app

# Salin semua file dari project lokal ke direktori kerja di container
COPY . .

# Install dependensi dari requirements.txt (kalau ada)
RUN pip install --no-cache-dir -r requirements.txt

# Jalankan aplikasi
CMD ["python", "app.py"]
