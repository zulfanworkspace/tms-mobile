# Tyre Monitoring (PWA)

Aplikasi monitoring ban yang bisa dipakai offline dan otomatis upload saat online.

## Deploy ke GitHub Pages
1. Upload semua file di folder ini (index.html, sw.js, manifest.json, icon-192.png, icon-512.png) ke root repository.
2. Repository > Settings > Pages > Source: "Deploy from a branch" > branch `main` / folder `/ (root)` > Save.
3. Buka `https://<username>.github.io/<repo>/` di Chrome HP (wajib HTTPS), login sekali saat online, lalu tekan "Pasang" / "Add to Home screen".

## Cara pakai di lapangan
1. Online: login lalu tekan **Sinkron** untuk mengunduh data unit & ban.
2. Di lapangan (tanpa sinyal): Mulai Monitoring > isi sesi > input per unit > Simpan. Data masuk antrian di HP.
3. Begitu online, antrian terkirim otomatis (atau tekan **Kirim Sekarang**).

## Update aplikasi
Setiap mengubah index.html, naikkan versi `CACHE` di sw.js (mis. `tyre-monitoring-v2`).
