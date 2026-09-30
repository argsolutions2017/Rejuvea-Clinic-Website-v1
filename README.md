# Rejuvea Skin & Hair Clinic Website

Static, Cloudflare-friendly clinic website created by adapting the same lightweight HTML/CSS/JavaScript approach used for the Gajanan Hospital website.

## Included

- `index.html` — responsive one-page clinic website
- `styles.css` — bright blush/rose/peach/green design system
- `script.js` — mobile navigation, scroll reveal, appointment-to-WhatsApp flow
- `privacy.html` — basic website privacy notice
- `robots.txt`
- `sitemap.xml`
- `_headers` — suggested Cloudflare Pages/Workers static security/cache headers
- `assets/rejuvea-logo.webp`
- `assets/doctor-placeholder.svg` — intentionally kept as a placeholder
- `assets/hero-visual.svg`
- `assets/og-image.jpg`
- `assets/favicon.png`

## Clinic information used

- Clinic: Rejuvea Skin & Hair Clinic | Diet & Nutrition Center
- Doctor: Dr. Priyanka G. Shirbhate
- Phone: +91 98342 22352
- Address: Jamb Road, near Vidya Vihar, Yavatmal – 445001
- Timings: 10:00 AM–2:00 PM and 5:00 PM–9:00 PM
- Doctor registration number is intentionally NOT displayed anywhere.

## Before production deployment

1. Replace `assets/doctor-placeholder.svg` with the doctor's approved photograph.
2. Confirm spelling of all degrees/qualifications with the doctor.
3. Confirm exact clinic address and operating days.
4. Confirm the final domain.
5. Update:
   - canonical URL in `index.html`
   - `og:url` and absolute `og:image`
   - JSON-LD `url`
   - `sitemap.xml`
   - `robots.txt` Sitemap line
6. Review treatment/service wording with the doctor before publishing.
7. If you add analytics, cookies, online payment, patient records, report uploads, or stored appointment data, update the privacy/compliance design accordingly.

## Local preview

Open `index.html` directly or run a local server:

```bash
python -m http.server 8080
```

Then browse to `http://localhost:8080`.

## Cloudflare deployment

This project is suitable for static deployment on Cloudflare Pages or Workers Static Assets. No database is required for the current version.
