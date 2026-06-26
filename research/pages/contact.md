# Contact Us

- **Live URL:** https://www.hairtransplant-trainingcenter.com/contact/
- **New-site permalink:** /contact/
- **Meta title:** Contact HTTC | Hair Transplant Training Turkey
- **Meta description:** (none)
- **Page type:** contact
- **Suggested template:** two-column — left contact details (location/WhatsApp/email), right contact form

## Sections (in page order)

### S1 — Contact Us (page heading + two-column block)
- **Layout:** full-width centered H1 above a 2-column grid (left = contact info, right = contact form)
- **Eyebrow/label:** (none)
- **Heading:** "Contact Us" (H1)

#### S1a — Location (left column)
- **Heading:** "Location" (H3)
- **Body (verbatim, icon list items):**
  > Kazım Özalp Mah. Uğur Mumcu Caddesi. No:6 G.O.P. 06680 Cankaya Turkey – Ankara
  >
  > WhatsApp +41765694284
  >
  > info@hairtransplant-trainingcenter.com
- **Links in section:**
  - `WhatsApp +41765694284` → `https://api.whatsapp.com/send?phone=41765694284&text=Hi` (external)
  - `info@hairtransplant-trainingcenter.com` → `mailto:info@hairtransplant-trainingcenter.com`
- **Images in section:** none (SVG icons only — location pin, WhatsApp, envelope)

#### S1b — Contact Form (right column)
- **Heading:** "Contact Form" (H3)
- **Form (Contact Form 7, id wpcf7-f7-p83):** fields in order —
  - Text input — placeholder "Your name" (name `your-name`, required)
  - Email input — placeholder "@ Email" (name `your-email`, required)
  - Tel input — placeholder "Phone Number" (name `tel`)
  - Textarea — placeholder "Your message (optional)" (name `your-message`)
  - Privacy consent checkbox (required), label verbatim:
    > I have read the Privacy Policy and agree that my data will be processed by Raken AG for the purpose of my enquiry and, if relevant to my training enrolment, shared with training partners in Turkey.
  - Submit button — value "Send"
  - (Also contains honeypot/anti-spam hidden fields `yourname-443` and `phone-444` — ignore in rebuild.)
- **Links in section:**
  - `Privacy Policy` → `/privacy-policy/` (internal, opens in new tab)
- **Images in section:** none

## All links on page
| Anchor text | Href (relative if internal) | Type | Notes |
|---|---|---|---|
| WhatsApp +41765694284 | https://api.whatsapp.com/send?phone=41765694284&text=Hi | external | WhatsApp click-to-chat |
| info@hairtransplant-trainingcenter.com | mailto:info@hairtransplant-trainingcenter.com | mailto | |
| Privacy Policy | /privacy-policy/ | internal | inside consent checkbox, target=_blank |

## All content images
| WP src filename | Alt text | Section | Suggested local file |
|---|---|---|---|
| (none) | — | — | — |

## ⚠️ Notes
- The page entry-content has **no content images** — only inline SVG icons.
- An "Apply Now / email / YouTube / LinkedIn" CTA button bar sits in the header/nav chrome just above the article (the global `gb-container-38ac3c54` block, same on every page); it is template chrome, not page content, so it is excluded here. For reference its links are: Apply Now → /contact/, envelope → mailto:info@hairtransplant-trainingcenter.com, YouTube → https://www.youtube.com/channel/UCv23DoWWExc8aSmEsVJqx8A, LinkedIn → https://tr.linkedin.com/pub/hair-transplant-training-center-dr-%C3%B6zg%C3%BCr/bb/450/a28
- Form action posts to `/contact/#wpcf7-f7-p83-o1`. On a static rebuild this needs a new form handler (the original is WP Contact Form 7).
- The address uses an en dash (Turkey – Ankara) — kept verbatim.
