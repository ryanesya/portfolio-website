# Project — Content Template (struktur final, ikut Celengan)

⚠️ JANGAN diisi file ini langsung. Ini master template. Tiap project punya file sendiri
(mis. `projects/<nama>/<slug>-content.md`). Isi bagian bertanda `→`.
Layout/UI TIDAK perlu diotak-atik lagi — Celengan jadi master. Kamu cukup nulis konten,
siapin gambar (nama `<slug>_slot.png` di folder `images/`), dan link prototype Figma.
Kalau udah, kabarin Claude → di-clone ke hi-fi + di-set warna theme-nya.

Baca [HOW-TO-WRITE-CONTENT.md](./HOW-TO-WRITE-CONTENT.md) buat aturan gambar/prototype.
Contoh terisi lengkap: lihat `projects/celengan/amartha-celengan-content.md`.

Catatan gaya: pakai English yang natural, TANPA em-dash (—). Pakai koma / titik dua / titik.

---

## CARD (grid homepage)
- Cover image   → [[IMG: <slug>_cover.png  caption: ""  layout: full]]
- Title         →
- Company       →   (logo: assets/company-logos/logo-xxx.png)
- Year          →

---

## DETAIL PAGE  (urutan section persis kayak Celengan)

### 1. Title & meta
- Title / Role / Year / Company  (Company tampil dengan logo kecil)

### 2. Banner
Pakai cover yang sama dengan card. [[IMG: <slug>_cover.png]]

### 3. Achievement
- Subtitle (italic) → "<produk> product metrics, <rentang waktu>"
- 2–3 metrik → angka + label
  - ...  → ...
  - ...  → ...

### 4. What is <produk>?   (1 paragraf definisi, panel full-width)
→

### 5. User research   (H2)
[[IMG: <slug>_research.png  caption: ""  layout: full]]

Sub-title (kalimat penuh, bold): "→"
  → paragraf
Sub-title (kalimat penuh, bold): "→"
  → paragraf

User journey map:
  → 1 kalimat pengantar
  [[IMG: <slug>_journey.png  caption: ""  layout: full]]   (boleh kosong dulu)

### 6. Crafting the solution   (H2)
→ bridging paragraph (hubungin insight ke solusi)

Highlighted flow: <nama flow 1>
  → context paragraph
  Opportunity   (tabel 3 kolom)
    | Rationale | Opportunity | Impact |
    | ...       | ...         | ...    |
  Information architecture + user flow
    → "Here is the IA and flow, mapped through breadboarding." (atau sesuaikan)
    [[IMG: <slug>_ia-flow1.png  caption: ""  layout: full]]
  Try it yourself
    [[PROTOTYPE: https://www.figma.com/proto/...  caption: "Try the flow"]]

Highlighted flow: <nama flow 2>   (struktur sama: context → Opportunity → IA+flow → prototype)

### 7. Usability testing   (tabbed, 1 finding per tab)
→ intro: ringkasan scope + hasil keseluruhan

Tab "<label finding>"  (status: Validated / Refined)
  → insight
  Tested design  → [[IMG: <slug>_ut-1-before.png]]
  Result/Improved → [[IMG: <slug>_ut-1-after.png]]  (atau, kalau lolos tanpa redesign: tandai "Passed")
(tambah tab sesuai jumlah finding)

### 8. Built with a local component library   (opsional, skip kalau nggak relevan)
[[IMG: <slug>_components.png  caption: "Local component set"  layout: full]]
→ 1–2 poin

### 9. Summary
Lesson learnt   → poin-poin
Next iteration  → poin-poin
