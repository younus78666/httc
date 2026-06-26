# Hair Transplant Training Our Team

- **Live URL:** https://www.hairtransplant-trainingcenter.com/team/
- **New-site permalink:** /team/
- **Meta title:** OUR TEAM - HTTC
- **Meta description:** (none — page uses og:description only: "Hair Transplant Training Our Team DR. JOHN COLE Medical director Forhair, Owner of Coleinstruments DR. ÖZGÜR ÖZTAN Medical Director of the Hairline Clinic GOEKHAN DOGAN Manager of the Hair Transplant Training Center DR. CENGIZ Specialist for motorized FUE devices like the PCID DR. ELIF Hair Surgeon and shareholder at the Hairline Clinic DR. ALI Hair ... Read more")
- **Page type:** team-index
- **Suggested template:** 3-card grid (member cards: portrait + name + role, each linking to profile)

## Sections (in page order)

### S1 — Page heading
- **Layout:** full-width centered (H1)
- **Heading:** "Hair Transplant Training Our Team"

### S2 — Team member card grid
- **Layout:** 3-card grid (7 cards, in order)
- **Cards (in order):**

  1. **DR. JOHN COLE** — "Medical director Forhair, Owner of Coleinstruments"
     - Link: `/doctors/dr-john-cole/` (⚠️ should be `/team/dr-john-cole/`)
     - Image: `dr_john_peter_cole.jpg` — alt "Dr. John Cole" — use → `images/team/dr-john-cole.jpg`

  2. **DR. ÖZGÜR ÖZTAN** — "Medical Director of the Hairline Clinic"
     - Link: `/doctors/dr-ozgur-oztan/` (⚠️ should be `/team/dr-ozgur-oztan/`)
     - Image: `dr_ozgur_1.jpg` — alt "Dr. Ozgur Oztan" — use → `images/team/dr-ozgur-oztan.jpg`

  3. **GOEKHAN DOGAN** — "Manager of the Hair Transplant Training Center"
     - Link: `/doctors/goekhan-dogan/` (⚠️ should be `/team/goekhan-dogan/`)
     - Image: `gokhan_dogan.jpg` — alt "Goekhan Dogan" — use → `images/team/gokhan-dogan.jpg`

  4. **DR. CENGIZ** — "Specialist for motorized FUE devices like the PCID"
     - Link: `/doctors/dr-cengiz/` (⚠️ should be `/team/dr-cengiz/`)
     - Image: `dr_cengiz_1.jpg` — alt "Dr. Cengiz" — use → `images/team/dr-cengiz.jpg`

  5. **DR. ELIF** — "Hair Surgeon and shareholder at the Hairline Clinic"
     - Link: (none — no anchor; card is NOT linked)
     - Image: `dr_elif_1.jpg` — alt "Dr. Elif" — use → `images/team/dr-elif.jpg`
     - ⚠️ No standalone profile page exists for Dr. Elif (no `/team/dr-elif/` page in this batch).

  6. **DR. ALI** — "Hair Surgeon"
     - Link: `/doctors/dr-ali/` (⚠️ should be `/team/dr-ali/`)
     - Image: `dr.unbekannt.jpeg` — alt "Dr. Ali" — use → `images/team/dr-unknown.jpg`

  7. **HAIRFORLIFE** — "Cooperation Partner Hairforlife"
     - Link: `/doctors/hairforlife/` (⚠️ should be `/team/hairforlife/`)
     - Image: `andreas-kraemer.jpg` — alt "Hairforlife" — use → `images/team/andreas-kraemer-hairforlife.jpg`

## All links on page
| Anchor text | Href (relative if internal) | Type | Notes |
|---|---|---|---|
| (image + DR. JOHN COLE) | /doctors/dr-john-cole/ | internal | should be /team/dr-john-cole/ |
| (image + DR. ÖZGÜR ÖZTAN) | /doctors/dr-ozgur-oztan/ | internal | should be /team/dr-ozgur-oztan/ |
| (image + GOEKHAN DOGAN) | /doctors/goekhan-dogan/ | internal | should be /team/goekhan-dogan/ |
| (image + DR. CENGIZ) | /doctors/dr-cengiz/ | internal | should be /team/dr-cengiz/ |
| (image + DR. ALI) | /doctors/dr-ali/ | internal | should be /team/dr-ali/ |
| (image + HAIRFORLIFE) | /doctors/hairforlife/ | internal | should be /team/hairforlife/ |

## All content images
| WP src filename | Alt text | Section | Suggested local file |
|---|---|---|---|
| dr_john_peter_cole.jpg | Dr. John Cole | S2 card 1 | images/team/dr-john-cole.jpg |
| dr_ozgur_1.jpg | Dr. Ozgur Oztan | S2 card 2 | images/team/dr-ozgur-oztan.jpg |
| gokhan_dogan.jpg | Goekhan Dogan | S2 card 3 | images/team/gokhan-dogan.jpg |
| dr_cengiz_1.jpg | Dr. Cengiz | S2 card 4 | images/team/dr-cengiz.jpg |
| dr_elif_1.jpg | Dr. Elif | S2 card 5 | images/team/dr-elif.jpg |
| dr.unbekannt.jpeg | Dr. Ali | S2 card 6 | images/team/dr-unknown.jpg |
| andreas-kraemer.jpg | Hairforlife | S2 card 7 | images/team/andreas-kraemer-hairforlife.jpg |

## ⚠️ Notes
- All 6 linked cards point to `/doctors/<slug>/` but the new-site permalink convention is `/team/<slug>/`. Hrefs recorded verbatim; rewrite to `/team/<slug>/` when rebuilding.
- **Dr. Elif** has a card (name + role + portrait) but NO link and NO standalone profile page in this batch. Flag: needs a profile page or leave the card unlinked.
- Card order in source: John Cole, Özgür Öztan, Goekhan Dogan, Cengiz, Elif, Ali, Hairforlife.
- Page has no `<meta name="description">`; only og:description (truncated "Read more" excerpt).
- Names in source HTML used HTML entities (`&Ouml;` = Ö, `&Uuml;` = Ü) — decoded here to "ÖZGÜR ÖZTAN".
