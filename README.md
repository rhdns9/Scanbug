# scan-websocket-bughost




![20230525_235701](https://github.com/willstore69/scan-websocket-bughost/assets/107354006/5829b7c7-776f-405e-804f-e78ce55ced6a)

Scan Bug Websocket - Termux Only

══════════════

Disclaimer: Jangan Gunakan Kuota Reguler Saat Menjalankan Script, Sesuaikan Dengan Sisa Paketan Yang Ada. Misalnya Akrab.

Caritahu Terlebih Dahulu Paketan Nya Itu Bisa Untuk Mengakses Apps / Website Apa.

Lalu Domain Website nya tinggal di masukin ke script & Tunggu Hingga Proses Selesai

══════════════
══════════════

Requirement Package

══════════════

pkg install wget -y

pkg install which -y

pkg install openssl -y

pkg update && pkg upgrade -y

SETUP TUTORIAL

STEP 1 : ambil Wordlist

``wget -q https://raw.githubusercontent.com/rhdns9/Scanbug/main/wordlist.txt``

STEP 2 : ambil script

``wget -q -O cek "https://raw.githubusercontent.com/rhdns9/Scanbug/main/scan_bug.sh" && chmod +x cek``

STEP 3 : jalankan script

./cek <bug.com>

══════════════

Pengecekan Multi Target Sesuai Wordlist

Command : ```./cek <domain>```
  
contoh : ```./cek udemy.com```

Pengecekan Single Target

Command : ```./cek <subdomain>```
  
contoh : ```./cek dashboard.udemy.com```
