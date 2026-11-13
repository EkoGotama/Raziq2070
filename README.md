# EYE-7 — dashboard simulasi bergaya "God's Eye"

Prototipe web satu file (`index.html`), terinspirasi film Furious 7.
**Seluruh data fiktif**: target, kamera, dan log dibangkitkan acak di browser. Tidak ada pelacakan orang sungguhan.

## Menjalankan
Buka `index.html` di browser (perlu internet untuk Leaflet dan tile peta), atau:

    python3 -m http.server 8000   # lalu buka http://localhost:8000

## Isi
- Peta gelap (Leaflet) dengan 28 target sintetis di 6 kota
- Daftar target + pencarian; klik target untuk lock, peta terbang ke sana dan menggambar jejak
- 4 feed kamera prosedural (kotak deteksi kendaraan, tanpa wajah)
- Log jaringan, jam, dan boot sequence
