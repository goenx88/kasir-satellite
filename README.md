# Kasir Voice Satellite — Standalone Web POS

Web Satellite hands-free dengan aktivasi suara (Wake Word: "Halo Kasir" / "Halo Bagir"), sintesis suara balasan (TTS), dan integrasi printer termal RawBT untuk Simple Kasir UMKM.

## Fitur Unggulan:
1. **Akses Mikrofon Penuh & Native**: Berdiri sendiri (tanpa Google Apps Script iframe), izin mic langsung diminta secara resmi oleh browser (Chrome/Brave).
2. **Custom Wake Word**: Kata pemicu fleksibel (default: "Halo Kasir", bisa diganti "Halo Bagir", "Halo Kopi", dll).
3. **Voice Feedback (TTS)**: Asisten kasir membalas balik dengan suara setelah transaksi sukses atau jika darurat.
4. **Thermal Printer Integration**: Tombol langsung cetak ke printer termal via RawBT Base64 dan auto-print port 40213.
5. **PWA Ready**: Bisa di-"Add to Home screen" di Android agar menjadi aplikasi layar penuh seperti tablet kasir profesional.

## Cara Deploy ke GitHub Pages:
1. Buat repository baru di GitHub bernama `kasir-satellite` (pilih **Public**).
2. Push seluruh file dalam folder ini ke branch `main`.
3. Di GitHub: Masuk ke **Settings > Pages > Branch: `main` > Save**.
4. Buka URL: `https://<username>.github.io/kasir-satellite/` di browser Brave / Chrome HP Anda.
