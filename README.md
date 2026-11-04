# Dr. Caroline Coene — dr. caroline coene bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `drcarolinecoene.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/drcarolinecoene.mjs`).
> To change the content, edit that file and run `node build.mjs drcarolinecoene` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@drcarolinecoene.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($On request / $On request / $Excluded) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are the practice of Dr. Caroline Coene, based in Ravels in the province of Antwerp and registered since 2008 for general medical practice and for diagnostic imaging. This page is information rather than advertising, because the rules on what a doctor may say publicly exclude comparisons, claims of superiority, patient testimonials and promises about outcomes. What is worth explaining instead is the principle that governs imaging and that almost no patient has heard stated. Any examination using ionising radiation has to be justified, meaning the expected benefit for that individual must outweigh the harm the exposure causes, and an alternative that uses no radiation has to be considered first. The consequence is one people find surprising: an examination that is not justified should not be carried out even when the patient asks for it, and agreeing to an unnecessary scan is not a courtesy. Where an examination is justified, the dose is kept as low as reasonably achievable for the diagnostic purpose. There is no dose ceiling protecting a patient the way there is for a worker, so justification and optimisation are the protection. Ultrasound, by contrast, uses no ionising radiation at all. Site: drcarolinecoene.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
