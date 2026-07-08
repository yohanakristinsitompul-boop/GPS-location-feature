# Profile Card App

## Deskripsi App

Profile Card App adalah aplikasi mobile berbasis React Native yang digunakan untuk membuat dan menyimpan informasi profil pengguna secara sederhana.

Aplikasi ini menyediakan fitur pengelolaan data profil seperti nama, NIM, program studi, kelas, serta foto profil. Selain itu, aplikasi memanfaatkan fitur native perangkat seperti kamera, galeri, GPS, penyimpanan lokal, dan integrasi Google Maps.

Data pengguna akan tersimpan otomatis menggunakan AsyncStorage sehingga informasi profil tetap tersedia ketika aplikasi dibuka kembali.

---

## Fitur Native yang Digunakan

Aplikasi ini menggunakan beberapa fitur native dari perangkat:

1. **Camera**
   - Mengambil foto secara langsung menggunakan kamera perangkat.

2. **Gallery / Media Library**
   - Memilih foto profil dari penyimpanan galeri perangkat.

3. **GPS / Location**
   - Mengambil koordinat lokasi pengguna secara real-time.

4. **Google Maps Integration**
   - Membuka lokasi pengguna melalui Google Maps berdasarkan koordinat GPS.

5. **AsyncStorage**
   - Menyimpan data profil secara lokal pada perangkat.

6. **Permission System**
   - Meminta izin akses kamera, galeri, dan lokasi dari pengguna.

---

# Daftar Fitur Aplikasi

## Level 2 Features

| No | Fitur | Status |
|---|---|---|
| 1 | Profile Card dengan data pengguna | ✅ Level 2 |
| 2 | Input Nama, NIM, Program Studi, dan Kelas | ✅ Level 2 |
| 3 | Mengambil foto menggunakan Camera | ✅ Level 2 |
| 4 | Memilih foto melalui Gallery | ✅ Level 2 |
| 5 | Mengambil lokasi menggunakan GPS | ✅ Level 2 |
| 6 | Menampilkan Latitude dan Longitude | ✅ Level 2 |
| 7 | Membuka lokasi melalui Google Maps | ✅ Level 2 |
| 8 | Auto Save menggunakan AsyncStorage | ✅ Level 2 |
| 9 | Load data otomatis ketika aplikasi dibuka | ✅ Level 2 |
| 10 | Reset data dengan dialog konfirmasi | ✅ Level 2 |
| 11 | Permission dialog untuk Camera, Gallery, dan Location | ✅ Level 2 |

---

# Screenshot Aplikasi

## 1. Tampilan Awal Profile Card

![Tampilan Awal](img width="540" height="1412" alt="WhatsApp Image 2026-07-09 at 01 35 29 (2)" src="https://github.com/user-attachments/assets/d2051986-c55c-4d4b-9636-d81675ed6e18" /)


## 2. Input Data Profile

![Input Data Profile](img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 35 45 (1)" src="https://github.com/user-attachments/assets/4a4e524e-9c2a-44e9-a278-a92d4d494d04" /)


## 3. Fitur Camera

![Camera](img width="540" height="1412" alt="WhatsApp Image 2026-07-09 at 01 36 02" src="https://github.com/user-attachments/assets/8a4682a4-4ae6-4a93-a279-5cdd002da516" /)


## 4. Fitur Gallery

![Gallery](img width="540" height="1412" alt="WhatsApp Image 2026-07-09 at 01 36 11" src="https://github.com/user-attachments/assets/e93d1165-83a9-4069-aee6-ab69526dd59b" /)


## 5. Fitur GPS

![GPS](img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 36 27" src="https://github.com/user-attachments/assets/b26f8b98-1e03-46f8-91c1-f93631b17c74" /)


## 6. Fitur Google Maps

![Google Maps](img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 36 44" src="https://github.com/user-attachments/assets/56f6a8da-ec20-41eb-b2b3-cbead86d935f" /)


## 7. Reset Data

![Reset](img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 37 55" src="https://github.com/user-attachments/assets/24890324-5f42-48ab-9b7c-f0c187e06eec" /)


## 8. Dialog Izin Permission

![Permission](img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 52 06" src="https://github.com/user-attachments/assets/e3a3b000-c25b-492c-845a-fe51986ec8ef" /)

---

# Cara Menjalankan Aplikasi

## 1. Install
Jalankan Expo:npx expo start

Kemudian:

Scan QR Code menggunakan aplikasi Expo Go
Pastikan perangkat terhubung dengan jaringan yang sama
Izinkan permission Camera, Gallery, dan Location

# Expo Snack

Link Expo Snack:

https://snack.expo.dev/@yohana06/b102b6
