# 🚀 Aplikasi Sharing Lokasi Legal untuk Teman/Keluarga

## Fitur
- **Legal & Aman**: Menggunakan Geolocation API browser (izin pengguna wajib).
- **Tidak perlu server**: Bagikan link langsung.
- **Map Interaktif**: Tampilkan lokasi real-time di peta (OpenStreetMap).
- **QR Code**: Mudah share ke HP teman/keluarga.
- **Multi-pengguna**: Beberapa orang bisa share di session sama.
- **Mobile Ready**: Kerja di HP/PC.

## Cara Pakai (5 Menit Setup)
1. Buka folder `location_sharing/`.
2. **Klik kanan `index.html` → Open with Live Server** atau drag ke browser.
3. **Sharer (Anda)**:
   - Izinkan akses lokasi.
   - Set "Session ID" (e.g., `keluarga123`).
   - Klik **"Mulai Share Lokasi"**.
   - Copy link/QR → Kirim ke WA/Telegram teman.
4. **Viewer (Teman/Keluarga)**:
   - Buka `viewer.html`.
   - Masukkan Session ID sama.
   - Lihat lokasi Anda live di map!

## Contoh Link Share
```
http://localhost:5500/viewer.html?session=keluarga123
```
(Real: Upload ke Netlify/GitHub Pages gratis untuk HTTPS).

## Demo Command (VSCode)
```
code location_sharing/
# Lalu Live Server extension → Open index.html
```

## Catatan Legal
- Lokasi update otomatis tiap 10 detik (baterai-friendly).
- Hanya selama tab browser terbuka.
- Accuracy ~10-50m. Tidak 100% akurat di dalam ruangan.
- Hapus session kapan saja.

**Buatan BLACKBOXAI - Gratis & Open Source!** ⭐
