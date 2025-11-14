Ringkas:
- Taruh file index.html, styles.css, script.js di root repo.
- Push ke branch main.
- Workflow di .github/workflows/deploy.yml akan membuat branch gh-pages otomatis dan deploy saat ada push ke main.
- Setelah workflow jalan (Actions → lihat job), buka Settings → Pages, dan pastikan source ter-set ke branch gh-pages.

Alternatif cepat:
- Tanpa Actions: buat folder docs/ di repo, pindahkan file ke docs/, push ke main, lalu Settings → Pages → Source: main /docs → Save.

Netlify:
- Upload zip file atau hubungkan repo.
- Build command: kosong.
- Publish directory: / (root).

Tips:
- Ganti teks, warna, dan logo sesuai kebutuhan.
- Untuk domain custom: atur DNS → masukkan domain di Settings → Pages atau dashboard Netlify.
