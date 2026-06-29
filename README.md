# 🛒 ShoppingList App - React Native

Aplikasi manajemen daftar belanja pintar berbasis React Native dan Expo yang dirancang untuk memudahkan pencatatan kebutuhan belanjaan harian dengan dukungan keamanan PIN dan manajemen visual barang.

---

## 🚀 Fitur Aplikasi

### 🔹 Fitur Utama (Level 1)
* **Manajemen CRUD Lengkap**: Menambah, melihat, mengedit, dan menghapus item belanjaan.
* **Manajemen Kuantitas & Harga**: Input jumlah barang beserta harga satuan untuk otomatisasi kalkulasi total.
* **Indikator Selesai**: Menandai barang yang sudah dibeli dengan efek coretan teks (*line-through*) dan animasi skala.
* **Statistik Real-time**: Bar ringkasan yang menampilkan total item, barang tersisa, barang dibeli, persentase progres, serta kalkulasi total biaya belanja.

### 🌟 Fitur Lanjutan (Level 2) - *Dipilih*
* **[Pilihan 1] Persistensi Data (AsyncStorage)**: Semua data belanjaan, status dibeli, pengaturan urutan (*sorting*), hingga status tema tersimpan aman dan tidak hilang saat aplikasi ditutup atau dibuka kembali.
* **[Pilihan 2] Mode Gelap / Terang (Dark & Light Theme)**: Transisi tema yang nyaman di mata dan status tema otomatis tersimpan.
* **[Pilihan 3] Keamanan PIN Lock Screen**: Mengamankan daftar belanja dari tangan jahat dengan fitur kunci PIN (termasuk fitur *shake animation* jika salah PIN dan sistem *limit attempt*).
* **[Pilihan 4] Filter Kategori & Pengurutan (Sorting)**: Memisahkan barang berdasarkan jenisnya (Sayur, Daging, Susu, dll.) serta mengurutkan berdasarkan nama (A-Z), harga, tanggal dibuat, atau status pembelian.
* **[Pilihan 5] Integrasi Gambar (Expo Image Picker)**: Mengunggah foto barang langsung melalui galeri handphone untuk visualisasi belanja yang lebih jelas.

---

## 🛠️ Tech Stack

* **Framework**: React Native (Expo SDK)
* **Navigation & Layout**: `react-native-safe-area-context`
* **Storage**: `@react-native-async-storage/async-storage`
* **Media**: `expo-image-picker`

---

## 🔗 Link Demo Interaktif (Expo Snack)

Anda dapat mencoba aplikasi ini secara langsung di browser atau perangkat Anda melalui tautan Expo Snack berikut:
👉 **[KLIK DI SINI UNTUK MENCOBA EXPO SNACK](https://snack.expo.dev/@meisyananda/mission12)**

<img width="720" height="1600" alt="m1" src="https://github.com/user-attachments/assets/abb8dbf0-6bc9-4505-9168-41a611af15f1" />
<img width="720" height="1600" alt="m3" src="https://github.com/user-attachments/assets/c15968bb-7030-441a-9f70-18264440f071" />
<img width="720" height="1600" alt="m2" src="https://github.com/user-attachments/assets/9f6e9258-edc9-43b2-9c5a-b534f98337ca" />
