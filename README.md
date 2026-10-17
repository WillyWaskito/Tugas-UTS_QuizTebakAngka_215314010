# Quiz Tebak Angka

**Nama :** Sirilus Espianto Willy Waskito  
**Nim    :** 215314010

**Nama project:** `Tugas-UTS_QuizTebakAngka_215314010`  
**Nama aplikasi:** Quiz Tebak Angka  
**Application ID:** `com.example.quiztebakangka`  
**Bahasa:** Kotlin  
**UI:** Android XML  
**Minimum Android:** Android 6.0 (API 23)  
**Compile SDK:** 35  
**JDK yang disarankan:** JDK 17 untuk Android Gradle Plugin 8.7.3

## Fitur
- Angka rahasia diacak pada rentang 0–100 setiap kali memulai permainan.
- Skor awal 100.
- Setiap tebakan yang salah mengurangi skor 10 poin, dengan batas bawah 0.
- Petunjuk apakah tebakan terlalu kecil atau terlalu besar.
- Permainan berakhir saat angka benar ditebak atau skor mencapai 0.
- Validasi input kosong dan angka di luar rentang 0–100.
- Menu utama, bantuan, informasi aplikasi, mulai ulang, dan kembali ke menu.
- UI responsif berbasis layout vertikal dan dapat digulir pada layar yang lebih kecil.
- Skor terbaik tersimpan permanen (SharedPreferences) dan tampil di menu.
- Rentang angka yang masih mungkin ditampilkan setelah tiap petunjuk.
- State permainan bertahan saat Activity dibuat ulang; tombol Back di game meminta konfirmasi.
- Semua teks berada di `strings.xml`; ikon launcher vektor.


## Menguji di Samsung Galaxy A06
- Pastikan perangkat menggunakan Android yang didukung (Android 6.0/API 23 atau lebih baru).
- Aktifkan Developer options dan USB debugging bila ingin menjalankan langsung dari Android Studio.
- Hubungkan kabel USB, setujui dialog izin debugging di HP, lalu pilih perangkat di Android Studio dan tekan **Run**.
- Uji: mulai game, input kosong, angka -1/101, tebakan terlalu kecil/besar, tebakan benar, pengurangan skor, skor 0, restart, dan kembali ke menu.
