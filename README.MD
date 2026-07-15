# Neurange Nigeria Limited — Landing Page

A single-file, self-contained landing page for **Neurange Nigeria Limited** (RC 7045719), a CAC-registered Lagos company operating across four divisions: Trading, Printing Press, Detergent Production, and General Merchandise.

🔗 **Live file:** [`neurange-nigeria-landing-page.html`](./neurange-nigeria-landing-page.html)

---

## What this is

A modern, conversion-focused marketing page built to establish trust and credibility for the company — leaning on the fact that we're a verifiably CAC-registered entity with named directors and a public incorporation record.

No build step. No dependencies to install. Open the HTML file in a browser and it works.

## Tech stack

| Layer      | Choice                                   |
|------------|-------------------------------------------|
| Markup     | Semantic HTML5                            |
| Styling    | [Tailwind CSS](https://tailwindcss.com) via CDN |
| Fonts      | Fraunces (display), IBM Plex Sans (body), IBM Plex Mono (data/labels) — Google Fonts |
| Interactivity | Vanilla JS (scroll reveals, animated counters, accessible FAQ accordion via `<input type="checkbox">`) |
| Framework  | None — plain HTML/CSS/JS by design         |

## Structure of the page

1. **Hero** — headline, credential strip (RC number, incorporation date, jurisdiction, status)
2. **Stats bar** — animated counters (divisions, shareholders, share capital, year founded)
3. **About / value proposition** — why one registered entity covers four disciplines
4. **Divisions** — Trading, Printing Press, Detergent Production, General Merchandise
5. **Why Neurange** — trust and capability benefits grid
6. **Governance** — named directors and shareholders from our CAC filing
7. **Process** — 4-step engagement flow (enquiry → scoping → fulfilment → delivery)
8. **FAQ** — accessible accordion, no JS required for open/close
9. **Closing CTA** — direct contact
10. **Footer** — registration details

## Running locally

No server required:

```bash
# just open it
open neurange-nigeria-landing-page.html   # macOS
start neurange-nigeria-landing-page.html  # Windows
xdg-open neurange-nigeria-landing-page.html # Linux
```

Or double-click the file in your file explorer.

## Deploying

Because it's a single static HTML file, it can be hosted anywhere with zero configuration:

- **GitHub Pages** — push to a repo, enable Pages, point it at this file (rename to `index.html`)
- **Netlify / Vercel** — drag-and-drop deploy
- **Any static host / CDN**

## Editing

- Copy is written in plain HTML — search for the section you want to change and edit the text directly.
- Colors, fonts, and spacing are controlled via the Tailwind config block in the `<head>` and the `<style>` block below it.
- Icons are inline SVGs (no icon library dependency) — swap the `<path>` data to change them.

## Accessibility & performance notes

- Respects `prefers-reduced-motion` (disables scroll/seal animations for users who request it)
- Visible keyboard focus states on all interactive elements
- FAQ accordion works via native `<input type="checkbox">` — no JS dependency for core functionality
- No external JS frameworks — fast first paint, minimal blocking resources

## Company reference

| Field | Value |
|---|---|
| Company name | Neurange Nigeria Limited |
| RC number | 7045719 |
| Incorporated | 9 July 2023 |
| Company type | Private Company Limited by Shares |
| Registered office | Lagos State Small Scale Industrial Estate, Fatai Atere Way, Mushin, Lagos State, Nigeria |
| Principal activity | Trading, Printing Press, Production of Detergent, General Merchandise |

## License

© Neurange Nigeria Limited. All rights reserved. This code is provided for the company's own use; reach out before reusing the brand assets or copy elsewhere.
