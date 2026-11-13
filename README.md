# NetKu Billing

Aplikasi tagihan WiFi (PWA) yang berjalan penuh di HP. Data disimpan lokal di browser (localStorage), bisa diekspor dan diimpor sebagai JSON.

## Pasang lewat GitHub Pages
1. Upload semua file ini ke repo GitHub (di root).
2. Settings > Pages > Source: `main` branch, folder `/ (root)`.
3. Buka `https://<username>.github.io/<repo>/` di Chrome HP, lalu menu ⋮ > **Tambahkan ke layar utama**.

## Catatan
- Data hanya ada di browser HP tersebut. Ekspor JSON berkala (Laporan > Ekspor JSON).
- Isolir saat ini hanya menandai status; integrasi MikroTik dan notifikasi WA otomatis perlu backend Node.js (tahap berikutnya).
