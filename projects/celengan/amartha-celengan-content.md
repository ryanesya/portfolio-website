# Celengan — Content (contoh TERISI, mirror hi-fi final)

Ini contoh acuan buat project lain (struktur + gaya nulis). Sinkron dengan yang LIVE di
`portfolio-hifi.html`. English, tanpa em-dash (—). Theme color: GREEN.

---

## CARD (grid homepage)
- Cover image   → [[IMG: celengan_cover.png]]
- Title         → Celengan: Investment for Rural Women Entrepreneurs
- Company       → Amartha  (logo: assets/company-logos/logo-amartha.png)
- Year          → 2024

---

## DETAIL PAGE

### 1. Title & meta
- Title → Celengan: Investment for Rural Women Entrepreneurs
- Role → Product Designer · Year → 2024 · Company → Amartha (with logo)

### 2. Banner
[[IMG: celengan_cover.png]]

### 3. Achievement
Subtitle: "Celengan product metrics, 2024 to Jan 2026"
- 67K       → Monthly transaction unit
- Rp63.85B  → Gross merchandise value
- 15K+      → Monthly new user

### 4. What is Celengan?
Celengan is an investment product for Amartha's rural women borrowers. It adapts the saving
habits they already have and adds something those habits never gave them: a recurring passive return.

### 5. Background
From our research, we found that Amartha's borrowers already have a habit of saving regularly,
whether through arisan (rotating savings groups), cooperatives, or cash kept at home. As a platform
that already lends to these borrowers, Amartha saw an opportunity to help them save too, and even
earn a return in the process, supporting their broader financial wellbeing. Their existing ways of
saving also came with real constraints of their own. That gap is what led Amartha to build a
dedicated saving product for its borrowers.

Main goal → Enhance borrowers' existing saving habit with a rewarding, interest-bearing product so
they can work toward their financial goals.

### 6. User research
[[IMG: celengan_research.png  caption: "User interview sessions with borrowers"]]

"Our core users already save, but in ways that earn them nothing"
Amartha's largest segment is its women borrowers, up to 3.3 million of them. Most already save
regularly, just through inconvenient channels: arisan (rotating savings groups), cooperatives,
and cash kept at home. None of these earn a return; they only store money.

"Celengan gives them a better way to save"
That gap was the opening: a way to keep saving, but now earning a recurring return, and one that
fits their wider financial life at Amartha, where the same relationship already covers borrowing
and repayment. None of them had invested like this before, yet our interviews and concept testing
showed they grasped the idea quickly, a real step forward for financial literacy in rural areas.

User journey map:
From the research, I mapped out how borrowers save today, a reference point for the rest of the design.
[[IMG: celengan_journey.png]]   (belum ada, kosong dulu)

### 7. Crafting the solution
From these insights, we shaped Celengan around two core flows that mirror how borrowers already
handle money: putting money in to earn a return (invest), and taking it back out when they need it (divest).

Highlighted flow: invest flow
  Context: Borrowers already set aside at least Rp10,000 a week for arisan, which told us the saving
  capacity was there. They save toward specific goals (their children's education, Lebaran, emergencies),
  and these usually follow a predictable timeline, such as school fees at the start of each academic
  year or savings spent every Lebaran.
 Opportunity
| Rationale | Opportunity | Impact |
| --- | --- | --- |
| Mitra sudah nabung rutin di arisan tapi tanpa imbal hasil | Sediakan wadah menabung yang kasih return rutin | Menabung jadi produktif, bukan cuma nyimpan |
| Tujuan menabung mitra punya timeline pasti (Lebaran, sekolah) | Kasih pilihan tenor yang sesuai timeline mereka | Mitra bisa nabung terarah sesuai kebutuhan |
| Mitra belum terbiasa investasi & masih menyimpan uang tunai | Menyampaikan skema investasi di flow investasi dengan bahasa yang sederhana | Meningkatkan literasi finansial & inklusi keuangan |

  
  Information architecture + user flow → [[IMG: invest-information-architecture.png  caption: "breadboarding"]]
  Try it yourself → [[PROTOTYPE: https://www.figma.com/proto/W0T1qMMemGw4rsgBbiqe5h/Portfolio-2025?page-id=293%3A21607&node-id=2061-71825&viewport=-4256%2C-1219%2C0.17&t=JaJ33fAGz9PPe2D4-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=2061%3A71825 (invest)]]

Highlighted flow: divest flow
  Context: Sometimes borrowers need their money back for something sudden, like medical costs or an
  unplanned expense. So the flow had to state clearly whether an asset could be withdrawn anytime or
  only at the end of its term.
  Opportunity | Rationale | Opportunity | Impact |
  |---|---|---|
  | Mitra bisa sewaktu-waktu membutuhkan uang mendadak | Sediakan akses divest sebelum tenor berakhir | Mitra dapat fleksibilitas dalam mengatur arus kasnya |
  | Mitra punya habit untuk nabung selama tenor tertentu, seperti lebaran | Sediakan pilihan investasi berjangka | Mitra dapat menabung sesuai dengan kebutuhan |
  | Menjaga mitra agar tidak mudah divest | Memberikan perhitungan potensi keuntungan jika tetap keep asetnya | Membuat mitra retain asetnya dan dapat imbal hasil |
  
  Information architecture + user flow → [[IMG: divest-information-architecture.png  caption: "breadboarding"]]
  Try it yourself → [[[PROTOTYPE: https://www.figma.com/proto/...](https://www.figma.com/proto/W0T1qMMemGw4rsgBbiqe5h/Portfolio-2025?page-id=293%3A21607&node-id=2061-72865&viewport=-4256%2C-1219%2C0.17&t=JaJ33fAGz9PPe2D4-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=2061%3A72865&show-proto-sidebar=1) (divest)]]

### 8. Usability testing (tabbed)
Intro: I tested the invest and divest flows with users from both segments. Both could complete the
flows end to end, so the core journeys held up, but three findings still surfaced. Here is what each led to.

Tab "Tenure selection" (Validated, no redesign)
  Users had no trouble entering the amount and tenure or reading the expected returns. The only quirk:
  most tapped the whole card rather than its radio button when choosing a tenure. That was harmless,
  since the card tap selected it anyway.
  Tested → [[IMG: celengan_ut-tenure.png]] · Result → Passed (same screen)

Tab "Product comparison" (Refined)
  Almost everyone chose a product by its tenure and rate, and could tell the options apart; they clearly
  understood both the interest rate and the tenure. To lean into that, I refined the product card so
  those two attributes read more clearly and consistently.
  [[IMG: celengan_ut-products-before.png]] / [[IMG: celengan_ut-products-after.png]]

Tab "Investment date" (Refined)
  A few users misread the maturity date as the investment's start date, and some held onto that
  assumption even after reading the label. I reworked how the date and status are shown so the
  end-of-term date is unmistakable.
  [[IMG: celengan_ut-date-before.png]] / [[IMG: celengan_ut-date-after.png]]

### 9. Built with a local component library
[[IMG: celengan_components.png  caption: "Local component set"]]
- For this project I built and maintained my own components and variants in Figma, evidence that I can
  create and keep a design system consistent at the project level.
- The library also sped up my own work, since many components were reused across screens, and other
  designers picked them up too, on cross-team projects touching mitra and Celengan.

### 10. Summary
Lesson learnt
- Designing an investment product for users with low financial literacy means keeping everything as
  simple as possible, and dropping the financial jargon people usually take for granted.
- Many borrowers have little money left over to set aside, so adoption of Celengan takes time.
Next iteration
- Given timeline and effort constraints, we couldn't yet support divesting a custom, free-form amount.
- After an investment matures, many borrowers leave the money idle, a clear opportunity to prompt a reinvestment.
