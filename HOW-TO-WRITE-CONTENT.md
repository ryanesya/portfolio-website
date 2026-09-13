# Cara Menulis Konten — Panduan Umum

File ini berlaku untuk SEMUA file konten (homepage & tiap project). Baca sekali,
lalu pakai aturan ini di mana pun kamu nulis.

## Struktur folder

```
Portfolio website/
  homepage-content.md          ← isi SEKALI aja (identitas, about, CV, contact, urutan project)
  project-content-template.md  ← JANGAN diisi — ini master template, copy aja per project baru
  projects/
    celengan/
      content.md                ← isi khusus project Celengan
      images/
        celengan_gallery-hero.png
        celengan_flow-invest.png
        ...
    project-2/
      content.md
      images/
    project-3/
      content.md
      images/
```

Tiap kali mulai project baru: **copy `project-content-template.md`** ke
`projects/<nama-project>/content.md`, lalu isi.

## Cara naruh gambar

Filename doang nggak cukup buat nentuin posisi. Aturannya cuma satu:

> **Posisi marker di dokumen = posisi gambar di halaman.**

Taruh markernya tepat di baris atas paragraf yang mau didampingi gambar itu. Formatnya:

```
[[IMG: nama-file.png
  caption: "teks kecil di bawah gambar (boleh kosong)"
  layout: full        # full | grid-2 | (right/left — lihat catatan di bawah)
]]
```

- `layout: full`   → **default, standar.** Gambar diletakkan DI BAWAH paragraf, full-width.
  Dipilih karena kebanyakan aset kita (screenshot, dokumentasi UT, dst) punya detail/teks
  yang perlu terbaca jelas — kalau ditaruh sempit di samping teks, jadi kekecilan.
- `layout: grid-2` → dua gambar sejajar, di bawah paragraf. Tulis dua marker `grid-2` berturut-turut.
- `layout: right` / `layout: left` → **exception, bukan default.** Cuma pakai ini kalau gambarnya
  simple/dekoratif (ikon, ilustrasi kecil, potret tanpa detail teks) dan sengaja mau ditaruh
  di samping paragraf. Kalau ragu, pakai `full`.

Contoh penggunaan (kasus umum — pakai `full`):

```
Kami interview urban lender dan menemukan mayoritas mereka invest di instrumen low-risk...
[[IMG: celengan-persona.png
  caption: "Low risk persona in urban lender"
  layout: full
]]
```

## Cara embed Figma prototype

Kasih link-nya (Share → Copy link, mode "Prototype"). Aku yang urus embed-nya.

```
[[PROTOTYPE: https://www.figma.com/proto/xxxxxxxx
  caption: "Try the end-to-end invest flow"
]]
```

## Aturan file gambar

- Export @2x dari Figma, format PNG (atau JPG kalau foto).
- Nama file: `namaproject_slot.png` (contoh: `celengan_gallery-hero.png`, `celengan_flow-invest.png`).
- Taruh file aslinya di folder `images/` project masing-masing — jangan tempel gambar di dalam .md, cukup markernya.
