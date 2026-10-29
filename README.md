# Stroke Claim Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) stroke medical-malpractice landing page for Weltchek Mallahan & Weltchek, built on the framework of your edited birth-injury GitHub page, with content and colors from **strokeclaim.com**.

## Framework — kept from your upload

- Same structure, classes, branding, logo/awards images, MTAA CIPA block, Meta Pixel, and form embed (`forms.mtaa.ai/f/nf_61e94f8f346b48d2b03c3f14419b8485`) as your uploaded `index-2.html` / `style-2.css`.
- The overflow form card works exactly as in your framework: the form container hangs past the hero over the section below it (your framework's own overlap values, preserved as-is), and the form frame scrolls internally (`overflow: auto`) if the embed runs tall.
- Footer legal links to your `privacy-policy.html` and `disclaimer.html` on justicehelpnow.com.

## CSS — identical to your upload except colors

`css/style.css` is your `style-2.css` with **only color values changed** (verified by diff — every layout, spacing, and overflow rule is untouched) to match strokeclaim.com's black / red / olive scheme, sampled from the live page:

| Role | Your framework | Stroke version |
|---|---|---|
| Dark surfaces (hero, footer, dark section) | navy `#0d2138` family | black / charcoal `#0a0a0a` family |
| Accent (kickers, headline accents, header phone) | gold `#c9a227` | red `#ff0000` |
| Secondary accent (eyebrow, footer phone) | gold-light `#e8c95a` | pale olive `#d7e08a` |
| CTA buttons | gold | olive `#b0b957` (hover `#c2cd6d`) |
| Results band background | pale gold `#fdf8e3` | pale olive tint `#f3f5e6` |
| Text grays / lines | blue-grays | neutral grays |

One legibility tweak that came with the colors: the checkmark glyphs in the round list markers are white instead of navy, since they now sit on red.

## Content (from strokeclaim.com)

- Hero: "Was a Stroke Misdiagnosed, Overlooked, or Improperly Treated?" — every second counts; we fight for stroke victims and their families in Maryland.
- Why Seek Legal Counsel — the proving-responsibility / extent-of-loss copy, plus the stroke-malpractice specialization.
- What Is a Stroke? — ischemic vs. hemorrhagic, the five warning symptoms, and the TIA (transient ischemic attack) paragraph.
- How Negligence Happens — the reference page's three case types as cards: failure to diagnose, improper treatment (tPA, dual anti-platelet therapy, thrombectomy, stroke protocols, blood-pressure management), overlooked warning signs (including younger patients).
- Results — "Over $700,000,000 in verdicts and settlements," 100+ years of combined experience, "Attention Maryland residents."
- What Compensation Can Cover — medical bills and ongoing care, rehab/therapy, lost wages and future income, pain and suffering, wrongful death damages, long-term residential care, home health care, home modifications, handicap-accessible transportation, durable medical equipment, medications. The review summary reflects the reference form's options (not diagnosed but should have been / diagnosed but not treated properly / should have been suspected; within the last 3 years or longer ago).
- Disclaimer: attorney advertising sponsored by Weltchek, Mallahan and Weltchek Trial Attorneys, 2330 W Joppa Rd #203, Timonium, MD 21093, plus the call/text consent text.

## Phone number

None — like strokeclaim.com itself, this page displays no phone number. The (888) 569-1665 that came in with your framework (header span and footer contact block) was stripped on request, along with the now-unused `.header-phone` CSS rule.

## Files

```
github-stroke-claim-landing-page/
├── index.html
├── css/style.css   (your CSS, colors only changed)
└── README.md
```

Publish the same way as the other pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root).
