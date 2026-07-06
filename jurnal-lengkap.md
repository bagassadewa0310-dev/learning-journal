# Jurnal Belajar RE - Bagas Sadewa

### Minggu 1
- **Topik:** Setup Lab VM & Ghidra
- **Paham:** Berhasil melakukan instalasi Ghidra dan konfigurasi Virtual Machine Windows secara aman untuk analisis.
- **Bingung:** Masih melakukan penyesuaian dengan beberapa shortcut penting yang ada di dalam Ghidra.

### Minggu 2
- **Topik:** Pengenalan Arsitektur x86 dan Register
- **Paham:** Memahami fungsi dasar dari register utama seperti EAX, EBX, ECX, EDX, serta instruksi dasar assembly seperti MOV dan ADD.
- **Bingung:** Cara kerja manajemen stack pointer (ESP) dan base pointer (EBP) saat sebuah fungsi program dipanggil.

### Minggu 3
- **Topik:** Analisis Statis Dasar & Ekstraksi String
- **Paham:** Menggunakan utility Strings dan BinText untuk mencari informasi hardcoded key atau indikasi alamat URL di dalam file binary.
- **Bingung:** Membedakan mana strings bawaan dari compiler dan mana strings asli yang ditulis oleh programmer.

### Minggu 4
- **Topik:** Membaca Control Flow Graph (CFG)
- **Paham:** Memahami visualisasi alur eksekusi program lewat percabangan instruksi kondisional seperti JZ, JNZ, JE, dan JMP di Ghidra.
- **Bingung:** Menelusuri alur graf fungsi jika strukturnya sudah terlalu kompleks dan memiliki banyak loop berputar.

### Minggu 5
- **Topik:** Praktik Menyelesaikan Crackme #1
- **Paham:** Berhasil mem-bypass pengecekan password sederhana dengan menganalisis percabangan logika fungsi string_compare.
- **Bingung:** Menentukan letak modul atau fungsi utama yang melakukan validasi jika file target berukuran besar.

### Minggu 6
- **Topik:** Reverse Engineering Logika XOR
- **Paham:** Memahami konsep enkripsi dan dekripsi string sederhana menggunakan operasi logika XOR dengan nilai konstan tertentu.
- **Bingung:** Melakukan kalkulasi manual jika key XOR berubah secara dinamis di setiap perulangan per karakter.

### Minggu 7
- **Topik:** Analisis Tabel Import (IAT)
- **Paham:** Mengidentifikasi fungsi Windows API yang mencurigakan seperti InternetOpenA (jaringan) atau RegSetValueExA (registry).
- **Bingung:** Mengatasi fungsi API tersembunyi yang di-load secara dinamis menggunakan LoadLibrary dan GetProcAddress.

### Minggu 8
- **Topik:** Review Mandiri Portofolio Akhir
- **Paham:** Berhasil merapikan dokumentasi writeup, menambahkan screenshot Ghidra beranotasi, dan melengkapi tabel ringkasan utama.
- **Bingung:** Memastikan visibilitas semua repositori sudah benar-benar publik dan dapat diakses dengan baik oleh dosen penguji.
