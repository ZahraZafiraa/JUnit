# JUnit
Tugas Kualitas Perangkat Lunak Kelas B

# Aplikasi Kalkulator Sederhana Android

Aplikasi kalkulator dasar Android yang menunjukkan konsep pengembangan Android dan praktik pengujian. Aplikasi ini menyediakan operasi aritmatika sederhana (penjumlahan, pengurangan, perkalian, dan pembagian) dengan antarmuka yang bersih dan ramah pengguna.

## Fitur

- Operasi aritmatika dasar: Penjumlahan, Pengurangan, Perkalian, dan Pembagian
- Validasi input dan penanganan kesalahan
- Antarmuka pengguna yang bersih dan intuitif
- Pengujian unit dan pengujian instrumen yang komprehensif

## Struktur Proyek

Proyek ini mengikuti arsitektur proyek Android standar:

- `Calculator.java`: Kelas logika inti yang berisi operasi aritmatika
- `MainActivity.java`: Kelas Activity yang mengelola interaksi UI
- `activity_main.xml`: File layout yang mendefinisikan antarmuka pengguna
- `CalculatorTest.java`: Pengujian unit untuk operasi kalkulator
- `MainActivityTest.java`: Pengujian instrumen untuk interaksi UI

## Pengujian

Proyek ini mencakup pengujian unit lokal dan pengujian instrumen:

### Pengujian Unit Lokal

Terletak di `app/src/test/java/com/example/simplecalculator/CalculatorTest.java`

Pengujian ini memverifikasi fungsi inti dari kelas Kalkulator:
- Penjumlahan angka positif
- Penanganan pengecualian pembagian dengan nol
- Pengurangan yang menghasilkan angka negatif
- Perkalian dengan nilai desimal

Untuk menjalankan pengujian unit:
1. Klik kanan pada `CalculatorTest.java`
2. Pilih "Run 'CalculatorTest'"

### Pengujian Instrumen

Terletak di `app/src/androidTest/java/com/example/simplecalculator/MainActivityTest.java`

Pengujian ini memvalidasi fungsionalitas UI aplikasi:
- Operasi penjumlahan melalui UI
- Operasi pembagian melalui UI
- Perkalian dengan angka desimal melalui UI

Untuk menjalankan pengujian instrumen:
1. Hubungkan perangkat atau mulai emulator
2. Klik kanan pada `MainActivityTest.java`
3. Pilih "Run 'MainActivityTest'"

## Ketergantungan

- JUnit 4.13.2 untuk pengujian unit
- AndroidX Test untuk pengujian instrumen
- Espresso untuk pengujian UI

## Instruksi Pengaturan

1. Kloning repositori
2. Buka proyek di Android Studio
3. Sinkronkan file Gradle
4. Jalankan aplikasi di emulator atau perangkat fisik

## Persyaratan

- Android SDK 21 (Android 5.0 Lollipop) atau lebih tinggi
- Android Studio
