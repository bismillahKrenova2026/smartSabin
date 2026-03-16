# 🌱 Smart Sabin Dashboard (Dummy IoT Monitoring)

Smart Sabin Dashboard adalah **prototype web dashboard** untuk monitoring sistem pertanian berbasis IoT.
Project ini menampilkan **simulasi data sensor secara realtime** menggunakan JavaScript tanpa koneksi ke backend atau perangkat IoT.

Web ini dibuat sebagai **demo UI / dummy dashboard** sebelum dihubungkan dengan sensor asli seperti ESP32, Arduino, atau sistem database.

---

# 🚀 Features

* 📊 Dashboard monitoring sensor pertanian
* 🌡 Simulasi data suhu udara
* 💧 Simulasi kelembaban tanah
* 🧪 Simulasi pH air
* 🌱 Simulasi pH tanah
* 📈 Grafik realtime menggunakan Chart.js
* 📋 Tabel riwayat sensor
* 🌾 Analisis tanaman sederhana
* 🎨 UI modern menggunakan TailwindCSS
* ✨ Animasi menggunakan AOS

---

# 📷 Preview

Dashboard menampilkan beberapa komponen utama:

1. **Sensor Cards**

   * pH Air
   * pH Tanah
   * Suhu Udara
   * Kelembaban Tanah

2. **Realtime Charts**

   * Grafik pH Air
   * Grafik Suhu
   * Grafik Kelembaban Tanah

3. **Sensor History Table**

   * Waktu update
   * Data sensor terbaru

4. **Plant Analysis**

   * Rekomendasi tanaman
   * Status servo
   * Target pH

---

# ⚙️ How It Works

Data pada dashboard **bukan data sensor asli**.
Semua nilai dihasilkan menggunakan fungsi JavaScript berikut:

```
function random(min,max){
 return (Math.random()*(max-min)+min).toFixed(1)
}
```

Nilai sensor akan **diupdate setiap 5 detik** menggunakan:

```
setInterval(updateDummy,5000)
```

Sehingga dashboard terlihat seperti menerima data realtime.

---

# 🧰 Technologies Used

* HTML5
* TailwindCSS
* JavaScript
* Chart.js
* AOS Animation Library

---

# 📂 Project Structure

```
smart-sabin-dashboard
│
├── index.html
└── README.md
```

Karena ini adalah **dummy prototype**, semua kode berada dalam satu file HTML.

---

# 🌐 How to Run

1. Download atau clone repository ini

```
git clone https://github.com/bismilahKrenova2026/smartSabin.git
```

2. Buka file:

```
index.html
```

di browser.

Tidak membutuhkan:

* database
* server
* backend
* instalasi tambahan

---

# 🔌 Future Development

Dashboard ini dapat dikembangkan menjadi **sistem IoT monitoring nyata** dengan menambahkan:

* ESP32 
* MQTT broker
* REST API
* Firebase / Realtime Database
* Node.js backend

Contoh alur sistem:

```
Sensor → ESP32 → Internet → API / Database → Dashboard
```

---

# 🎯 Purpose

Project ini dibuat untuk:

* Prototype IoT Agriculture Dashboard
* UI/UX testing
* Demo presentasi sistem Smart Farming
* Belajar visualisasi data sensor

---

# 👨‍💻 Author

Smart Sabin Monitoring System
2026
