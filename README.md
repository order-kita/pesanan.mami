# MASAKAN MAMI - Frontend GitHub Pages

Isi repo `masakan-mami`: `index.html`, `.nojekyll`, folder `assets/` (logo, favicon, ikon produk).

1. Apps Script: tempel Code.gs, OrderService.gs, StatisticsService.gs, AuthService.gs terbaru (ada `doPost` untuk API).
2. Deploy > New deployment > Web app > Execute as: Me, Who has access: Anyone. Salin URL `/exec`.
3. Buka `index.html`, ganti `GAS_URL` dengan URL tersebut.
4. Unggah semua isi folder ini ke repo GitHub (branch main).
5. Settings > Pages > Deploy from branch > main / root. Situs: https://USERNAME.github.io/masakan-mami/
6. Setiap ubah kode Apps Script: Deploy > Manage deployments > Edit > New version.
7. Agar respons cepat: Apps Script > Triggers > Add trigger > fungsi `ping`, Time-driven, setiap 5 menit.

Catatan: URL Apps Script kini diisi di file `config.js` (bukan index.html). Saat memperbarui situs, cukup ganti index.html; config.js Anda tidak perlu diubah.
