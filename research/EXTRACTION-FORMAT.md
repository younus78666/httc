# HTTC page extraction — format & rules (read fully before extracting)

You are extracting content from a saved WordPress page (GeneratePress + GenerateBlocks) into a clean Markdown spec that will be used to rebuild the page on a new static site (HTTC style: navy/cyan, Lexend, image-led, split sections).

## Where things are
- Source HTML lives in `d:/Github/HTTC/research/wp-html/<slug>.html`
- Write your output to `d:/Github/HTTC/research/pages/<slug>.md`
- The real page content is inside `<article>` → `.entry-content` (plus the page hero/title block that may sit just above it). IGNORE the site header nav, the cookie banner, and the global footer — those are template chrome, not page content.

## Hard rules
1. **Body text must be VERBATIM.** Copy paragraphs/list items exactly as written, including the site's en dashes (–). Do NOT paraphrase, summarize, fix grammar, or add words. (The client requires word-for-word content.)
2. **Capture EVERY link inside the content** with its exact anchor text and href. Convert absolute `https://www.hairtransplant-trainingcenter.com/<path>` links to the relative permalink `/<path>` (keep external links absolute; keep `mailto:`/`tel:` as-is).
3. **Capture EVERY content image**: the src filename (last path segment, ignore the `-1024x576` style size suffix when noting the base), its alt text, and which section it sits in.
4. Be exhaustive and accurate. No mistakes. If something is ambiguous, note it under "⚠️ Notes".

## Permalink note
Doctor/person pages live under `/team/<slug>/` (e.g. `/team/dr-john-cole/`), NOT `/doctors/`. If content links to `/doctors/<x>/`, record the href verbatim but flag it under Notes as "should be /team/<x>/".

## Local images already available (use these when an image matches)
Team portraits in `images/team/`: dr-john-cole.jpg, dr-ozgur-oztan.jpg, gokhan-dogan.jpg, dr-cengiz.jpg, dr-elif.jpg, dr-unknown.jpg, andreas-kraemer-hairforlife.jpg
General in `images/`: imgi_4_fue-course-turkey-1024x576.jpg, imgi_5_fue_work_shop_2-1.jpg, imgi_6_Training.jpg, imgi_7_hair-transplant-course-3.jpg, imgi_8_dr_ozgur_1.jpg, imgi_9_IMG_3864.jpg, imgi_10_fue_work_shop_1.jpg, imgi_11_doctor.jpg
Blog images in `images/blog/` (16 files, original WP names). The certificate art is `hair-transplant-training-certificate-1.svg` at site root.
If a content image has no local match, record the original WP filename under "suggested local file" with "(NEEDS DOWNLOAD)".

## Output MD template (use exactly this structure)
```
# <Page H1 / main heading>

- **Live URL:** https://www.hairtransplant-trainingcenter.com<path>
- **New-site permalink:** <path>
- **Meta title:** <from <title>>
- **Meta description:** <from meta description, or "(none)">
- **Page type:** home | about | training | doctor-profile | team-index | blog-index | blog-post | legal | contact | faq | general-info
- **Suggested template:** (e.g. split-section text/image, card grid, accordion FAQ, profile hero + bio)

## Sections (in page order)

### S1 — <section label or heading>
- **Layout:** <split-left-text-right-image | split-left-image-right-text | full-width centered | 3-card grid | accordion | stat bar | CTA band>
- **Eyebrow/label:** <if any>
- **Heading:** "<verbatim>"
- **Body (verbatim):**
  > <verbatim paragraph 1>
  >
  > <verbatim paragraph 2 / list items as - bullets>
- **Links in section:** `<anchor>` → `<href>` (internal/external)
- **Images in section:** `<wp filename>` — alt "<alt>" — use → `<local file or NEEDS DOWNLOAD>`

### S2 — ...
(repeat for every section)

## All links on page
| Anchor text | Href (relative if internal) | Type | Notes |
|---|---|---|---|

## All content images
| WP src filename | Alt text | Section | Suggested local file |
|---|---|---|---|

## ⚠️ Notes
- <anything ambiguous, broken, German text, duplicate, redirect, /doctors vs /team, etc.>
```
Keep it tight but complete. One MD file per page.
