# Skilqu: Landing Page Cheat Sheet for Internship Interviews

Mobile-first landing page for the **Skilqu Free Starter Kit**, built for the Digital Marketing course (Module 2: Landing Page & Usability Testing), Digital Innovation, Information Systems Department, ITS. Skilqu is a case study from the module.

**Live:** https://skilqu-interview-magang.netlify.app

> [!IMPORTANT]
> **This is a university assignment, not a real product or service.**
> Skilqu is a fictional case study from the course module. No company, course, video, cheat sheet, or Skilqu Pass package is actually sold.
> The numbers on the page (e.g., 100+ students per month and Rp49,000/month) come from the module's business case data, not real data.
> Registration (via Lynk.id) is only used for assignment testing. Please do not enter sensitive personal data.

![Skilqu landing page hero view](share.jpg)

## About the project

- **Goal:** a single conversion goal — visitors register for the Free Starter Kit (Rp0): a 15-minute STAR Technique video and a cheat sheet of 10 internship interview questions. The advanced Skilqu Pass package (Rp49,000/month) is introduced afterwards.
- **Target:** final-year students and fresh graduates (persona "Nadya", 21 years old). 85% open it from a phone.
- **KPI:** Landing Conversion Rate = registrants ÷ visitors × 100%. Baseline 5%, target ≥ 8%.

## Page structure (5-Section Mobile Framework)

1. **Hero:** H1 from the Module 1 SEO research, CTA button directly in the hero, and the STAR cheat sheet card as a product mockup.
2. **Problem & Agitation:** 3 moments that make an interview fail, closed with a sentence that lights up word by word on scroll.
3. **Solution & Inside Preview:** comparison of a plain answer vs. the STAR Technique (clickable per part), Starter Kit contents, and a YouTube vs. Bootcamp vs. Skilqu table.
4. **Trust & FAQ:** a blurred cheat sheet preview, transparent Skilqu Pass info, and 5 FAQs.
5. **Final CTA:** 3 steps to claim it and a button to the Rp0 product on Lynk.id (since Module 3; previously a Google Form). Plus a bonus YouTube video with interview tips added earlier.

## Features

- Single column on mobile, 31px H1, 16–18px body text, and touch targets of at least 44px.
- Amber CTA button `#F59E0B` visible on the first screen and repeated below. There is a sticky button on mobile that steps aside when the final section is visible.
- All "Ambil Gratis" buttons open the Free Starter Kit Rp0 product on Lynk.id. The `utm_*` parameters from the s.id link (Hook A/B, Module 3) are forwarded to the Lynk.id link.
- Smooth motion: sections fade in on scroll, cards lift on hover, table checkmarks, button shimmer, and "Siap interview" / "Terkirim" stamps. All motion stops when the user prefers reduced motion.
- On-page SEO: title tag, meta description, canonical, and Open Graph for link previews.

## Tech stack

- HTML, CSS, and a little JavaScript — no framework and no build step.
- Font: Plus Jakarta Sans (Google Fonts). Icons: line SVGs.
- Hosting: Netlify. Registrant data: Lynk.id.
- Layout and motion system use the kit from [taste-skill](https://github.com/Leonxlnx/taste-skill) (MIT license, see `assets/LICENSE-taste-skill.txt`).

## File structure

```
index.html        main page
privacy.html      privacy policy
favicon.svg       tab icon
share.jpg         link preview image (Open Graph)
assets/           CSS and JS kit used by the page
*.md              process documents: page content, product profile, design system, design plan
```

## Running locally

Open this folder through a local server, because some scripts use ES modules that do not run from `file://`:

```bash
python -m http.server 8480
```

Then open http://localhost:8480.

## Notes

- The video in the bonus section belongs to the respective YouTube channels and is only linked, not created by Skilqu.
- The cheat sheet on the page is demonstration material for a university assignment.
