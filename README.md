# SiGAWAT — Prototipe Website

Website statis responsif untuk prototipe gagasan SiGAWAT, sistem pendukung keputusan untuk mitigasi banjir dan tanah longsor.

## Fitur prototipe
- Landing page dan ringkasan dashboard
- Peta interaktif dengan Leaflet + OpenStreetMap
- Filter jenis ancaman dan pencarian lokasi contoh
- Kartu informasi peringatan simulasi
- Formulir laporan warga demo (tersimpan sementara di memori halaman)
- Daftar laporan dan status pemeriksaan contoh
- Visualisasi analitik ilustratif dan roadmap pengembangan
- Tampilan responsif untuk desktop dan ponsel

## Penting
- Semua metrik, titik risiko, laporan, dan sebagian konten adalah **data simulasi**.
- Sistem ini **tidak terhubung ke sumber peringatan resmi**, belum memiliki backend/database, dan tidak menjalankan model AI.
- Jangan gunakan untuk keputusan keselamatan atau pelaporan darurat nyata.
- Peta dasar membutuhkan koneksi internet karena memuat Leaflet dan tile OpenStreetMap dari layanan eksternal.

## Menjalankan lokal
Buka `index.html` di browser. Untuk pengujian yang lebih baik, gunakan ekstensi Live Server di VS Code.

## Hosting di GitHub Pages
1. Buat repository GitHub baru, misalnya `sigawat-prototype`.
2. Unggah `index.html`, `style.css`, `script.js`, dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses selesai; GitHub akan menampilkan URL Pages pada bagian Pages.

Jika ingin mengganti nama atau identitas tim, edit judul/teks di `index.html` dan periksa label simulasi agar tetap jelas.
