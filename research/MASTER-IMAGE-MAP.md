# HTTC — Master Image Map

All content images from the live site are downloaded to **`images/wp/`** (51 files, original WordPress names). Team portraits are also copied, renamed, to **`images/team/`**. Homepage/general images already curated live in **`images/`**. Blog save-zip images live in **`images/blog/`**.

> The site serves images from `/images/<name>` (NOT `/wp-content/uploads/`). Size suffixes like `-1024x576` are thumbnails of the same base file.

## Global chrome (every page)
- `httc-logo-true.png`, `httc_logo-1.png` → replaced by our `Header and footer logo.png` (white lockup). No need to reuse.

## Team portraits (use the clean `images/team/` copies when building profile/founder cards)
| Person | Profile page | WP file (`images/wp/`) | Clean copy (`images/team/`) |
|---|---|---|---|
| Dr. John P. Cole | /team/dr-john-cole/ | dr_john_peter_cole.jpg | dr-john-cole.jpg |
| Dr. Özgür Öztan | /team/dr-ozgur-oztan/ | dr_ozgur_1.jpg | dr-ozgur-oztan.jpg |
| Goekhan Dogan | /team/goekhan-dogan/ | gokhan_dogan.jpg | gokhan-dogan.jpg |
| Dr. Cengiz | /team/dr-cengiz/ | dr_cengiz_1.jpg | dr-cengiz.jpg |
| Dr. Elif (index only, no page) | — | dr_elif_1.jpg | dr-elif.jpg |
| Dr. Ali | /team/dr-ali/ | dr.unbekannt.jpeg | dr-unknown.jpg |
| Hairforlife (Andreas Krämer) | /team/hairforlife/ | andreas-kraemer.jpg | andreas-kraemer-hairforlife.jpg |

## Images by page (build reference)

### / (home)
Training.jpg · IMG_3864.jpeg (hero) · doctor.jpg · dr_ozgur_1.jpg (faculty) · fue-course-turkey.jpg · fue_work_shop_1.jpg · fue_work_shop_2-1.jpg · hair-trans.jpg · hair-transplant-course-3.jpg

### /about-httc/
ZFR1294.jpg (referenced in source; otherwise text-only — currently rebuilt image-led with home photos)

### /fue-workshop/
5e77fe984c71bdfbed474487_Screen-Shot-2018-06-11-at-2.03.38-PM.png · fue_work_shop_2-1.jpg

### /certificate/
hair-transplant-training-certificate-1.svg (certificate art, also at site root) · hair-trans.jpg

### /team/ (index)
all 7 team portraits above

### Doctor profiles
/team/dr-john-cole/ → dr_john_peter_cole.jpg · /team/dr-ozgur-oztan/ → dr_ozgur_1.jpg · /team/dr-cengiz/ → dr_cengiz_1.jpg · /team/dr-ali/ → dr.unbekannt.jpeg · /team/goekhan-dogan/ → gokhan_dogan.jpg · /team/hairforlife/ → andreas-kraemer.jpg

### Blog posts
- **hair-transplant-workshop-training-2024** → har-transplant-workshop.jpg
- **t-lab-academy-remedex-hlc** → 24_may_2024_fRI_regenerative_…practice.jpg · day-2-25-may-2024-sat-platelets-rich-plasma…practice.jpg · regenerative_surgery_in_hair_restoration…practice.jpg · platelets_rich_plaspa.jpg · scientific_commitee.jpg · scientific_commitee_2.jpg
- **latest-technologies** → ZERO-PUNCH-1.png (+ YouTube embed)
- **dr-carlos-calixto-brazil** → hairtransplant-training-dr-carlos-calixto4.jpg (+ YouTube embed)
- **cit-fue-dr-cole** → dr_cole31.jpg
- **dr-mustafa-las-vegas** → usa_dr_mustafa_hair_transplant_training.jpg (+ YouTube embed)
- **training-turkey-alternative-india-uk** → impressionen3.jpg
- **bargello-brothers-germany** → IMG_6032-727x409-1.jpg · IMG_6032-727x409-2.jpg · IMG_6303-1024x683-1.jpg
- **pcid-coleinstruments** → pcid.jpg (+ 2 YouTube embeds)
- **dr-lars-heitmann-pcid** → drheitmann.jpg (+ YouTube embed)
- **hlc-training-centre-ended** → hair-transplant-course-1.jpg … hair-transplant-course-7.jpg (gallery)
- **fue-tools-instruments-devices** → coleinstruments-the-surrounded-punches.gif · Coleinstruments-the-countingdevice-e1432443615473.jpg · coleinstruments-thegraftprocessingboard.jpg · Coleinstruments-the-pcid1.png · Coleinstruments-pcid-Handpiece.jpg · punch.jpg
- **best-fue-training-course-doctors** (pillar) → IMG_3864.jpeg (hero) · fue-training-clinical-workflow-v2.webp · fue-training-course-comparison-v2.webp

## Notes
- All 51 base images downloaded OK (verified). YouTube embeds are not images — capture as video embeds.
- `hair-trans.jpg` is a light-tinted background used on home/certificate CTA bands.
- Per-page exact `<img>`/alt/section detail is in each `research/pages/<slug>.md`.
