# Mehul Parmar — Professional Portfolio & RCM Funnel

> Business Development Manager · Medical Billing & RCM Partner for US Practices
> 15+ years professional experience · 11+ years in BPO/KPO operations

**Live site:** https://kumarmehul48.github.io/Kumarmehul48/

---

## About

This repository hosts the professional portfolio website of **Mehul Parmar**, a freelance Business Development Manager specializing in medical billing and Revenue Cycle Management (RCM) for solo and small US practices. The site doubles as a complete RCM sales funnel with WhatsApp-integrated lead capture.

- **LinkedIn:** https://www.linkedin.com/in/kumarmehul181
- **WhatsApp:** +91 70437 95279
- **Email:** kumarmehul48@gmail.com
- **Book a call:** https://calendly.com/kumarmehul48

## Pages

| Page | Purpose |
|---|---|
| `index.html` | Home — hero, four pillars, track request |
| `rcm.html` | Full RCM funnel — industry stats, 5 revenue leaks, 8-step cycle with SLAs, WhatsApp enquiry form |
| `services.html` | Four service pillars (Healthcare, BPO/KPO, AI, CSC) |
| `about.html` | Professional profile, experience, education |
| `contact.html` | Contact form + WhatsApp + Calendly |
| `track.html` | Client portal — doctor login & admin login |
| `privacy.html` / `terms.html` / `refund.html` / `disclaimer.html` | Legal pages (Indian digital business standards) |

## RCM Funnel Highlights

- 2025 industry data: 12–15% denial rates, $57–125 per denied claim rework, ~12 hrs/week on prior auth, 10–20% collectible revenue lost
- The **five revenue leaks**: denials written off, underpayments, unworked A/R, eligibility & credentialing gaps, single-person dependency
- **8-step revenue cycle** with speed commitments: 24-hr claim submission, 48-hr denial follow-up, weekly A/R recovery, monthly plain-English reporting
- Free 48-hour revenue review funnel with WhatsApp pre-filled enquiry form

## Backend

The forms and client portal are powered by a centralized Google Sheet (**"Mehul Portfolio Data"**) on Google Drive with tabs: Leads, Doctors, Updates, Admin.

Three deployed Base44 backend functions handle the logic:

- `mehulSubmitLead` — contact & funnel forms append leads to the Leads tab
- `mehulDoctorLogin` — secure login for RCM clients (Doctors tab)
- `mehulAddUpdate` — project status updates pushed to client portal

## Tech

- Pure HTML + CSS + JavaScript (no build step) — fast static site
- Premium dark theme (emerald + gold), fully responsive
- Hosted free on GitHub Pages
- Floating WhatsApp button site-wide

## License

© 2026 Mehul Parmar. All rights reserved.
