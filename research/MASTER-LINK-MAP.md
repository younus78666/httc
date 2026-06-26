# HTTC — Master Link Map & Sitemap

Source: live WordPress sitemap (page + post + category). 36 content URLs. Each has a detailed spec in `research/pages/<md>`.

## Status legend
✅ built on new site · 🔲 to build · 🔁 redirect to live WP in `vercel.json` until built

## Pages (22)
| # | Permalink | Type | Status | Spec MD |
|---|---|---|---|---|
| 1 | `/` | home | ✅ | home.md |
| 2 | `/about-httc/` | about | ✅ | about-httc.md |
| 3 | `/general-information/` | hub | 🔲 | general-information.md |
| 4 | `/general-information/introduction-objectives-2/` | general-info | 🔁 | introduction-objectives-2.md |
| 5 | `/general-information/training-content-course-outline-hair-transplant-training-fue-workshop-course/` | general-info | 🔁 | training-content-course-outline.md |
| 6 | `/hair-transplant-training-course/` | training | 🔁 | hair-transplant-training-course.md |
| 7 | `/fue-workshop/` | training | 🔁 | fue-workshop.md |
| 8 | `/schedule-and-registration/` | training | 🔲 | schedule-and-registration.md |
| 9 | `/training-cost-pricing/` | training | 🔲 | training-cost-pricing.md |
| 10 | `/certificate/` | training | 🔲 | certificate.md |
| 11 | `/contact/` | contact | 🔲 | contact.md |
| 12 | `/faq/` | faq | 🔲 | faq.md (19 Q&A) |
| 13 | `/team/` | team-index | 🔁 | team-index.md |
| 14 | `/team/dr-john-cole/` | doctor | 🔁 | team-dr-john-cole.md |
| 15 | `/team/dr-ozgur-oztan/` | doctor | 🔁 | team-dr-ozgur-oztan.md |
| 16 | `/team/dr-cengiz/` | doctor | 🔁 | team-dr-cengiz.md |
| 17 | `/team/dr-ali/` | doctor | 🔁 | team-dr-ali.md |
| 18 | `/team/goekhan-dogan/` | doctor | 🔁 | team-goekhan-dogan.md |
| 19 | `/team/hairforlife/` | doctor | 🔁 | team-hairforlife.md |
| 20 | `/privacy-policy/` | legal | 🔲 | privacy-policy.md |
| 21 | `/imprint/` | legal | 🔲 | imprint.md |
| 22 | `/cookie-policy/` | legal | 🔲 | cookie-policy.md |

## Blog (1 index + 13 posts)
| # | Permalink | Status | Spec MD |
|---|---|---|---|
| 23 | `/blog/` (+ `/blog/page/2/`) | 🔲 | blog-index.md |
| 24 | `/hair-transplant-workshop-training-2024/` | 🔲 | post-hair-transplant-workshop-training-2024.md |
| 25 | `/a-unique-hands-on-training-hosted-by-t-lab-academy-in-collaboration-with-remedex-at-ankara-hlc-clinic/` | 🔲 | post-t-lab-academy-remedex-hlc.md |
| 26 | `/hair-transplant-training-the-latest-technologies/` | 🔲 | post-latest-technologies.md |
| 27 | `/dr-carlos-calixto-from-brazil-expanded-his-skills-through-a-3-day-training-program/` | 🔲 | post-dr-carlos-calixto-brazil.md |
| 28 | `/cit-fue-hair-transplant-from-dr-cole/` | 🔲 | post-cit-fue-dr-cole.md |
| 29 | `/dr-mustafa-from-las-vegas-usa-participated-in-a-hair-transplant-training-from-httc-in-turkey/` | 🔲 | post-dr-mustafa-las-vegas.md |
| 30 | `/training-in-turkey-as-alternativ-to-india-easy-access-from-united-kingdom-uk/` | 🔲 | post-training-turkey-alternative-india-uk.md |
| 31 | `/hair-transplant-training-with-the-brothers-dr-andreas-bargello-dr-matthias-bargello-from-germany/` | 🔲 | post-bargello-brothers-germany.md |
| 32 | `/about-the-pcid-from-coleinstruments/` | 🔲 | post-pcid-coleinstruments.md |
| 33 | `/dr-lars-heitmann-testing-the-pcid/` | 🔲 | post-dr-lars-heitmann-pcid.md |
| 34 | `/hlc-and-the-hair-transplant-training-centre-has-successfully-ended/` | 🔲 | post-hlc-training-centre-ended.md |
| 35 | `/fue-hair-transplant-tools-instruments-devices/` | 🔲 | post-fue-tools-instruments-devices.md |
| 36 | `/best-fue-hair-transplant-training-course-doctors/` | 🔲 | post-best-fue-training-course-doctors.md |

(Category `/uncategorized/` exists but is empty/noise — skip.)

## ⚠️ Permalink correction: `/doctors/` → `/team/`
Several pages' content (About, Intro/Objectives, team index cards, a few posts) link doctors as `/doctors/<slug>/`. The **canonical live permalink is `/team/<slug>/`**. Use `/team/` everywhere when building:
- /doctors/dr-john-cole/ → **/team/dr-john-cole/**
- /doctors/dr-cengiz/ → **/team/dr-cengiz/**
- /doctors/dr-ali/ → **/team/dr-ali/**
- /doctors/goekhan-dogan/ → **/team/goekhan-dogan/**
- /doctors/hairforlife/ → **/team/hairforlife/**
- /doctors/dr-akin/ → **no such page** (broken empty-anchor link in About source; drop it — there is no Dr. Akın, the faculty is Cengiz/Ali/Elif)

## Primary nav / footer targets (for global header & footer)
Home `/` · About `/about-httc/` · Our Team `/team/` · Certificate `/certificate/` · Training Course `/hair-transplant-training-course/` · FUE Workshop `/fue-workshop/` · Introduction/Objectives `/general-information/introduction-objectives-2/` · Training Content/Outline `/general-information/training-content-course-outline-hair-transplant-training-fue-workshop-course/` · Schedule & Registration `/schedule-and-registration/` · Pricing `/training-cost-pricing/` · Blog `/blog/` · Contact `/contact/` · FAQ `/faq/` · Privacy `/privacy-policy/` · Imprint `/imprint/` · Cookie Policy `/cookie-policy/`

## Contact constants (used across pages)
- WhatsApp: `https://api.whatsapp.com/send?phone=...` (+41 76 569 4284 on current site chrome; confirm canonical number)
- Email in legal/contact content: `info@hairtransplant-trainingcenter.com` (site chrome elsewhere uses info@httc-training.com — **must reconcile to one**)
- Legal entity: **Raken AG**, Bahnhofstrasse 3, 5070 Frick, Switzerland · CHE-305.773.861

## External links referenced in content
youtube.com (video embeds) · tr.linkedin.com (team socials) · api.whatsapp.com (CTA) · coleinstruments.com · fuehairtransplant-pcid.com · ishrs.org · abhrs.org · hairforlife-international.com · fue-hlc.com · fue-haartransplantation.ch · fue-europe.org · forhair.com · drozguroztan.com · handsonankara.com · mailchi.mp · browser cookie-help (google/mozilla/microsoft/apple support)
