DEMOPLOT PWA V3
================

Isi:
- index.html
- manifest.json
- sw.js
- logo-demoplot.png
- logo-symbol.png
- icons/

Perubahan utama:
1. Mobile Android dibuat seperti aplikasi native:
   - header DEMOPLOT
   - brand card
   - KPI cards
   - dashboard cards
   - bottom navigation Dashboard / Input Data
2. Logo DEMOPLOT dipakai sebagai branding dan icon PWA.
3. Install App button + beforeinstallprompt.
4. Service worker cache dinaikkan ke demoplot-v3 agar versi lama tidak tertahan.
5. Desktop tetap memakai sidebar.

Deploy:
1. Extract ZIP.
2. Replace file project GitHub Pages dengan semua file di folder ini.
3. Pastikan URL dibuka melalui HTTPS GitHub Pages:
   https://stratoart.github.io/SuperAPP/
4. Setelah update, buka Chrome Android -> menu -> reload.
5. Jika Chrome belum menampilkan prompt otomatis, tekan tombol Install App di halaman.
6. Jika tombol browser masih tidak muncul, buka menu Chrome (⋮) dan pilih Install app / Tambahkan ke layar utama.

Catatan:
- API Google Apps Script tidak diubah.
- Semua 40 allocation tetap fixed.
