# Wisdom Surgery Clinic — Booking / Patient Forms Site

## What this is
Patient-facing appointment request and forms site for Dr Anna Raymond's practice.
Live at **wisdomsurgery.me** (GitHub Pages with custom domain).

## Stack
- Vanilla HTML/CSS/JS, no framework, no build step
- Deployed via `git push`

## File map
```
index.html                  # Appointment request page (57KB — grep don't read whole file)
patient-information.html    # Patient information form (118KB — grep only, very large)
new-patient-form-print.html # Printable new patient form (43KB — grep only)
telehealth.html             # Telehealth consultation page (34KB — grep only)
sitemap.xml                 # SEO sitemap
robots.txt                  # Crawl rules
```

## Critical rules
- **Never read whole HTML files** — 34KB–118KB monoliths with embedded CSS+JS. Grep for what you need.
- No build step — changes go live on push, test in browser before pushing
- Patient-facing — professional tone, accessibility matters
