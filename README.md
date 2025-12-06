<h1 align="center">Responsive Dashboard</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" />
  <img src="https://img.shields.io/badge/React%20Native-0.82-61DAFB" />
  <img src="https://img.shields.io/badge/Expo-~51-000020" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6" />
  <img src="https://img.shields.io/badge/License-MIT-orange" />
</p>

<p align="center">Dashboard berbasis <strong>React Native</strong> yang mendukung tampilan <strong>Mobile, Tablet, dan Large Tablet</strong> dengan konsep <strong>Responsive dan Orientation-Aware Layout</strong>. Project ini dikembangkan sebagai bagian dari tugas Pemrograman Mobile.</p>

---

## Fitur Utama

* Responsive layout untuk Mobile dan Tablet
* Breakpoint khusus untuk Large Tablet (≥ 1024px)
* Orientation-aware layout (Portrait dan Landscape)
* Grid card responsif (1 kolom menjadi 2 kolom)
* Icon responsif pada setiap card
* Dukungan SafeAreaView untuk menghindari area notch dan status bar

---

## Preview Tampilan

Bagian ini menampilkan hasil pengujian tampilan aplikasi pada berbagai ukuran layar dan orientasi.

### Tabel Preview Screenshot

| No | Mode Tampilan      | Label                   | Preview                                                                                                                              |
| -- | ------------------ | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| 1  | Mobile Portrait    | Mobile View             | ![Mobile Portrait](https://raw.githubusercontent.com/username/rn-responsive-dashboard/main/assets/screenshots/mobile-portrait.png)   |
| 2  | Tablet Portrait    | Tablet View             | ![Tablet Portrait](https://raw.githubusercontent.com/username/rn-responsive-dashboard/main/assets/screenshots/tablet-portrait.png)   |
| 3  | Mobile Landscape   | Mobile View (Landscape) | ![Mobile Landscape](https://raw.githubusercontent.com/username/rn-responsive-dashboard/main/assets/screenshots/mobile-landscape.png) |
| 4  | Large Tablet / Web | Tablet View (Large)     | ![Large Tablet](https://raw.githubusercontent.com/username/rn-responsive-dashboard/main/assets/screenshots/large-tablet.png)         |

**Catatan:**

* Screenshot ditampilkan langsung dari repository GitHub menggunakan raw link.
* Ganti `username/rn-responsive-dashboard` dengan username dan nama repository milik kamu.
* Pastikan file berada di path `assets/screenshots/` sesuai struktur folder.

----|----------------|--------|------------|
| 1 | Mobile Portrait | Mobile View | `assets/screenshots/mobile-portrait.png` |
| 2 | Tablet Portrait | Tablet View | `assets/screenshots/tablet-portrait.png` |
| 3 | Mobile Landscape | Mobile View (Landscape) | `assets/screenshots/mobile-landscape.png` |
| 4 | Large Tablet / Web | Tablet View (Large) | `assets/screenshots/large-tablet.png` |

**Catatan:**

* Simpan seluruh file screenshot di dalam folder `assets/screenshots/`.
* Pastikan nama file sesuai dengan yang tercantum di tabel agar mudah ditautkan ke README.

---

## Teknologi yang Digunakan

* React Native
* Expo
* TypeScript
* react-native-safe-area-context
* @expo/vector-icons (Feather)

---

## Cara Menjalankan Project

1. Clone repository

```bash
git clone https://github.com/username/rn-responsive-dashboard.git
cd rn-responsive-dashboard
```

2. Install dependency

```bash
npm install
```

3. Jalankan project

```bash
npx expo start
```

4. Pilih metode menjalankan aplikasi:

* Tekan `a` untuk Android Emulator
* Tekan `w` untuk Web Browser
* Scan QR Code untuk menjalankan di perangkat fisik

---

## Breakpoint yang Digunakan

| Mode         | Lebar Layar |
| ------------ | ----------- |
| Mobile       | < 768px     |
| Tablet       | ≥ 768px     |
| Large Tablet | ≥ 1024px    |

---

## Perilaku Orientation-Aware Layout

* Mobile Portrait: 1 kolom
* Mobile Landscape: 2 kolom (tablet-style layout)
* Tablet (semua orientasi): 2 kolom

---

## Struktur Data Card

Setiap card menggunakan struktur data sebagai berikut:

```ts
{
  title: string;
  description: string;
  icon: IconName;
}
```

---

## Tujuan Pengembangan

Project ini bertujuan untuk:

* Menerapkan konsep responsive layout pada React Native
* Mengimplementasikan breakpoint dan orientation-aware UI
* Mengelola tampilan lintas ukuran layar secara dinamis dan konsisten

---

## Author

Ranggis

---

## Penutup

Repository ini diharapkan dapat menjadi referensi dalam pengembangan antarmuka responsif berbasis React Native. Apabila terdapat saran atau pengembangan lanjutan, silakan disampaikan melalui repository ini.
