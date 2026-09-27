🌑 Interactive Eclipse Simulator

Interactive web-based simulation untuk memvisualisasikan gerhana Bulan, gerhana Matahari, dan konfigurasi Matahari–Bumi–Bulan secara interaktif.

Dibuat menggunakan HTML5 Canvas, CSS, dan JavaScript murni, tanpa framework atau dependency eksternal.

✨ Features

- 🌕 Gerhana Bulan
  - Penumbral
  - Sebagian
  - Total
- ☀️ Gerhana Matahari
  - Sebagian
  - Total
  - Cincin
  - Hybrid
- 🌍 POV Bulan
  - Simulasi gerhana Matahari dari permukaan Bulan
- 🪐 System View
  - Melihat konfigurasi Matahari, Bumi, dan Bulan dalam sistem orbit
- ▶️ Play / Pause / Replay
- 🎚️ Kontrol posisi atau fase gerhana
- 🔍 Kontrol skala objek
- ⭐ Toggle tampilan bintang
- 🏷️ Toggle label objek
- 🌙 Dark / Light Theme
- 📱 Responsive untuk desktop dan mobile

🖥️ Preview

Simulator menyediakan beberapa sudut pandang:

┌──────────────────────────────────────┐
│           Eclipse Simulator          │
├──────────────┬───────────────────────┤
│ Controls     │                       │
│              │   ☀️  🌍  🌑          │
│ Eclipse Type │                       │
│ POV          │     Simulation        │
│ Phase        │       Canvas          │
│ Scale        │                       │
│ ▶ Play       │                       │
└──────────────┴───────────────────────┘

🚀 Installation

Tidak diperlukan instalasi package atau dependency tambahan.

Cara 1 — Buka langsung

Download atau clone repository:

git clone https://github.com/USERNAME/eclipse-simulation.git

Masuk ke folder:

cd eclipse-simulation

Kemudian buka:

eclipse-simulation.html

menggunakan browser modern seperti:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Cara 2 — Menggunakan Local Server

Jika ingin menjalankan melalui local server:

python -m http.server 8000

Kemudian buka:

http://localhost:8000/eclipse-simulation.html

📂 Project Structure

eclipse-simulation/
│
├── eclipse-simulation.html
└── README.md

🎮 Controls

Control| Fungsi
Jenis simulasi| Memilih jenis simulasi gerhana
Tipe gerhana| Memilih tipe gerhana
POV| Memilih tampilan pengamat atau sistem orbit
Posisi / fase| Mengatur posisi simulasi dari awal hingga akhir
Skala objek| Mengatur ukuran visual objek
Play| Menjalankan animasi
Pause| Menghentikan animasi
Replay| Mengulang simulasi dari awal
Tampilkan label| Menampilkan atau menyembunyikan nama objek
Tampilkan bintang| Menampilkan atau menyembunyikan background bintang
Light / Dark| Mengubah tema tampilan

🌕 Jenis Simulasi

Gerhana Bulan

Pada mode ini, simulasi dapat menampilkan:

- Penumbral — Bulan melewati penumbra.
- Sebagian — sebagian permukaan Bulan masuk ke umbra Bumi.
- Total — seluruh piringan Bulan masuk ke umbra Bumi.

Gerhana Matahari

Mode ini menyediakan:

- Sebagian — sebagian piringan Matahari tertutup Bulan.
- Total — fotosfer Matahari tertutup.
- Cincin — Bulan tampak lebih kecil sehingga Matahari membentuk cincin.
- Hybrid — simulasi dapat menampilkan karakteristik total atau cincin bergantung posisi fase.

Gerhana Matahari — POV Bulan

Mode ini mensimulasikan pengamatan dari permukaan Bulan, dengan Bumi berada di depan Matahari.

🛠️ Technology

Project ini menggunakan teknologi web standar:

- HTML5
- CSS3
- JavaScript
- HTML5 Canvas 2D

Tidak menggunakan:

- Framework JavaScript
- NPM package
- Build system
- Backend
- External API

📐 Catatan Simulasi

Visualisasi ini dibuat sebagai simulasi edukatif dan ilustratif.

Ukuran, jarak, dan beberapa parameter visual Matahari, Bumi, dan Bulan tidak merepresentasikan skala astronomi sebenarnya. README dan simulator mempertahankan pendekatan visual agar fenomena gerhana lebih mudah diamati.

🎓 Tujuan

Project ini dapat digunakan sebagai media pembelajaran untuk membantu memahami:

- Posisi relatif Matahari, Bumi, dan Bulan
- Mekanisme dasar gerhana
- Perbedaan gerhana Bulan dan Matahari
- Pergerakan bayangan dan umbra
- Perbedaan sudut pandang pengamat

📜 License

Jika repository ini akan dipublikasikan, tambahkan lisensi yang sesuai, misalnya MIT License.

---

🌑 Interactive Eclipse Simulator

Explore the alignment of the Sun, Earth, and Moon — interactively.
