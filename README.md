# eproc — Prototype INAPROC

| Prototype | Link |
|---|---|
| Daftar Master Produk | [`/`](https://sitorusreinhard30-svg.github.io/eproc/) |
| Harga Zonasi HET — Alt. 1 (edit harga di popup) | [`/harga-zonasi/?alt=1`](https://sitorusreinhard30-svg.github.io/eproc/harga-zonasi/?alt=1) |
| Harga Zonasi HET — Alt. 2 (popup baca-saja) | [`/harga-zonasi/?alt=2`](https://sitorusreinhard30-svg.github.io/eproc/harga-zonasi/?alt=2) |

## Simulasi kasus gagal (Harga Zonasi HET)

Tambahkan parameter `simulasi` ke link:

- `?simulasi=unduh-gagal`: unduh template gagal
- `?simulasi=unggah-format`: unggah gagal, format tidak sesuai
- `?simulasi=unggah-aturan`: unggah gagal, pengisian tidak sesuai ketentuan
- `?simulasi=unggah-ukuran`: unggah gagal, ukuran melebihi 50 MB

Contoh: `/harga-zonasi/?alt=2&simulasi=unggah-format`

## Konvensi

Setiap prototype disimpan di foldernya sendiri dengan nama file `index.html`.
