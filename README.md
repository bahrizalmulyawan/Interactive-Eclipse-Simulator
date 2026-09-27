# Eclipse Simulation 🌑

Simulator interaktif edukatif untuk memvisualisasikan gerhana Bulan dan gerhana Matahari menggunakan HTML5 Canvas dan JavaScript murni.

## Fitur

- 🌕 Gerhana Bulan dari POV pengamat di Bumi
- ☀️ Gerhana Matahari dari Bumi
- 🌍 Simulasi gerhana dari POV permukaan Bulan
- Jenis gerhana: penumbral, sebagian, total, cincin, dan hybrid (sesuai mode)
- Kontrol fase/posisi simulasi
- Kontrol skala objek
- Play, Pause, dan Replay
- Toggle label dan bintang
- POV sistem orbit untuk melihat konfigurasi Matahari–Bumi–Bulan
- Toggle tema Light/Dark
- Responsive untuk layar desktop dan mobile
- Tidak membutuhkan library atau dependency eksternal

## Cara Instalasi

Proyek ini adalah aplikasi web statis, jadi tidak memerlukan instalasi package.

### Opsi 1 — Jalankan langsung

1. Ekstrak ZIP ini.
2. Buka file `eclipse-simulation.html` di browser modern seperti Chrome, Edge, Firefox, atau Safari.
3. Simulator langsung dapat digunakan.

### Opsi 2 — Jalankan dengan local server

Jika ingin menjalankannya melalui local server:

```bash
python -m http.server 8000
```

Kemudian buka:

```text
http://localhost:8000/eclipse-simulation.html
```

## Cara Upload ke GitHub

1. Buat repository baru di GitHub.
2. Upload `eclipse-simulation.html` dan `README.md`.
3. Commit perubahan.
4. Jika ingin dipublikasikan sebagai website, aktifkan **GitHub Pages** pada repository tersebut.

## Struktur Proyek

```text
eclipse-simulation/
├── eclipse-simulation.html
└── README.md
```

## Teknologi

- HTML5
- CSS3
- JavaScript
- HTML5 Canvas 2D

Tidak ada framework, build tool, atau dependency eksternal.

## Catatan

Visualisasi ini bersifat **edukatif dan ilustratif**. Ukuran, jarak, dan beberapa parameter objek astronomi tidak dibuat berdasarkan skala fisik sebenarnya.
