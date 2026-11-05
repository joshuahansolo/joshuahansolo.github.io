# AGENTS.md — Rules for working on joshuahansolo.github.io

This is Joshua Han's personal website, which will be served publicly via GitHub Pages
(github.com/joshuahansolo). Anything committed here should be treated as public.

## 1. Never publish

- **Phone number.** It is on the CV but must never appear on the site, in commits, or in metadata.
- **The CV PDF itself** (`HAN_JOSHUA_RESUME.pdf`) — it contains the phone number. It is listed in
  `.gitignore`. Do not link to it, copy it, or commit it.
- **Personal email addresses** (e.g. a personal Gmail). Only the school email shown on the CV
  (`JHan27@gsb.columbia.edu`) may be shown.
- Home address, date of birth, IDs, or any other personal identifiers.
- Private details about other people beyond what the CV already names publicly (e.g. no contact
  info for colleagues, investors, or founders).
- Confidential company information: non-public deal terms, startup names from the 37 Angels
  pipeline, internal financials, or anything not already on the CV.
- Invented facts. Never fabricate metrics, titles, dates, links, testimonials, or URLs. If a value
  is missing (e.g. the LinkedIn URL), leave a clearly marked TODO and tell Joshua.
- Secrets of any kind: API keys, tokens, analytics IDs that aren't Joshua's, `.env` files.

## 2. Ask Joshua first before

- Pushing, committing, creating a repo, or enabling GitHub Pages — anything that makes content public.
- Adding any information that is **not** on the CV (new roles, numbers, bios, photos, projects).
- Rewording CV claims in a way that changes their meaning or numbers.
- Adding third-party scripts, trackers, analytics, fonts from new CDNs, or contact forms.
- Adding a photo, a downloadable resume, or any new file type to the public site.
- Deleting or overwriting existing files.
- Changing the domain, repo name, or site structure (adding pages beyond `index.html`).

## 3. Style

- **Tone:** professional but casual — confident, warm, first-person-friendly, no buzzword stacking.
- **Color:** Columbia blue palette.
  - Columbia blue `#B9D9EB` (primary accent / backgrounds)
  - Light tint `#EAF4FA` (section backgrounds)
  - Columbia navy `#1D4F91` (headings, links, buttons — meets contrast on white)
  - Ink `#0F2A44` (body text)
- **Typography:** clean sans-serif (Inter, falling back to system fonts). Generous spacing.
- **Navigation:** one slim sticky top bar; links to each section in CV order; smooth scrolling;
  works on mobile without a hamburger menu where possible.
- **Content order:** must match the CV — Education → Experience → Additional Information.
- **Tech:** plain HTML + CSS (+ minimal vanilla JS only if needed). No build step, no frameworks.
  Must work when opened directly from disk and on GitHub Pages.
- **Accessibility:** semantic HTML, alt text, visible focus states, color contrast ≥ WCAG AA,
  respects `prefers-reduced-motion`.
- Keep CV wording faithful; light formatting changes (tiles, bolded metrics) are fine.

## 4. Approved sources

Only these may be used as content. Anything else needs Joshua's OK first (see section 2).

- The CV (`HAN_JOSHUA_RESUME.pdf`). Use its content, but never publish the file or the phone number.
- LinkedIn: https://www.linkedin.com/in/wjoshuahan/
- GitHub: https://github.com/joshuahansolo
- Joshua's own bio (approved 2026-11-05). Use it word for word in the hero and contact sections:
  > Hi there! I'm Josh, an MBA candidate at Columbia Business School and Investment Associate at
  > 37 Angels, passionate about longevity and creativity. That vision grew out of sharing insights
  > from my own fitness journey following personal health challenges.
  > Outside of work, I'm working towards scratch golf and training for my first full Ironman triathlon.
  > If you're building something bold — especially in health and wellness, consumer, and creator
  > economy — I'd love to connect.
- Update from Joshua (2026-11-05). This replaces the CV's "training for Hawaii 70.3": he finished
  Ironman 70.3 Hawaii in May 2026 and is now training for a full Ironman (140.6).
