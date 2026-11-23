# Praktikum IoT - Node-RED

Praktikum Internet of Things (IoT) menggunakan Mosquitto MQTT Broker, simulasi ESP32, Node-RED, REST API, Web Dashboard, WebSocket, dan SQLite.

## Struktur Praktikum

### Bagian A – Setup MQTT Broker
Melakukan instalasi dan konfigurasi Mosquitto sebagai MQTT Broker untuk komunikasi data IoT.

### Bagian B – Simulasi ESP32 (Publisher)
Menggunakan Python untuk menyimulasikan ESP32 sebagai publisher yang mengirimkan data sensor suhu dan kelembapan melalui MQTT.

### Bagian C – Flow Node-RED (Backend API)
Membangun flow Node-RED sebagai backend untuk menerima data MQTT dan menyediakan layanan REST API.

### Bagian D – Custom Web Dashboard
Membuat dashboard berbasis HTML untuk menampilkan informasi sensor dan melakukan kontrol melalui backend Node-RED.

### Bagian E – Testing & Uji Coba
Melakukan pengujian komunikasi MQTT, REST API, dashboard, dan fungsi sistem secara keseluruhan.

## Pengembangan Tambahan

Selain praktikum utama, dilakukan lima pengembangan berikut:

1. **Endpoint `/api/threshold` (PUT)**  
   Menambahkan fitur pengaturan batas suhu dan notifikasi ketika suhu melewati batas.

2. **Grafik Real-Time Chart.js**  
   Menambahkan grafik untuk menampilkan perubahan data sensor secara real-time pada dashboard.

3. **Autentikasi API Key**  
   Menambahkan autentikasi sederhana menggunakan header `X-API-Key`.

4. **WebSocket**  
   Mengimplementasikan WebSocket pada Node-RED melalui endpoint `/ws/sensor` untuk pembaruan data tanpa polling.

5. **Penyimpanan Database SQLite**  
   Menyimpan riwayat data sensor menggunakan SQLite dan menyediakan endpoint `/api/history` untuk mengambil data historis.

## Struktur Repository

```text
Praktikum-IoT-NodeRED-2410010525/
│
├── database/
│   └── sensor.db
│
├── Screenshots/
│   ├── Bagian A/
│   ├── Bagian B/
│   ├── Bagian C/
│   ├── Bagian D/
│   ├── Bagian E/
│   ├── Tugas 1/
│   ├── Tugas 2/
│   ├── Tugas 3/
│   ├── Tugas 4/
│   └── Tugas 5/
│
├── dashboard.html
├── flows.json
├── simulasi_ESP32.py
└── README.md
```

## Teknologi yang Digunakan

- Python
- Mosquitto MQTT Broker
- Node-RED
- MQTT Protocol
- REST API
- HTML, CSS, dan JavaScript
- Chart.js
- WebSocket
- SQLite

## Dokumentasi

Dokumentasi pengerjaan praktikum utama Bagian A–E dan pengembangan Tugas 1–5 tersedia pada folder `Screenshots`.

## Repository GitHub

https://github.com/novicahyanilukman12211-ai/Praktikum-IoT-NodeRED-2410010525
