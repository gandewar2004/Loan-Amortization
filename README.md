# Payal Motors – Loan Amortization Calculator

**Installable web application** for loan EMI & amortization schedules.

## Live App

After enabling GitHub Pages (see below):

**https://gandewar2004.github.io/Loan-Amortization/**

## Features

- **EMI Frequencies:** Monthly · Half-Yearly · Annual
- **Interest Methods:** Reducing Balance & Flat Interest
- **Extra Payments:** Optional extra principal
- **Schedules:** Full period table + Annual summary
- **Customer & Agent:** Name, contact, agent watermark
- **Installable PWA:** Add to Home Screen on phone / desktop
- **Works offline** after first open
- Indian Rupee (₹) formatting
- No login, no backend, no external libraries

## How to use (local)

1. Open `index.html` in Chrome / Edge / Safari
2. Enter customer & agent details (optional)
3. Fill loan amount, term (years), interest rate
4. Choose method & EMI frequency
5. Click **Calculate ▶**

## Enable live application (GitHub Pages)

1. Open: https://github.com/gandewar2004/Loan-Amortization
2. **Settings** → **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / folder **/** (root)
5. Save → wait 1–2 minutes
6. Open: https://gandewar2004.github.io/Loan-Amortization/

### Install on phone

1. Open the live link in Chrome (Android) or Safari (iPhone)
2. Menu → **Add to Home Screen** / **Install app**
3. App icon appears like a normal app

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main application |
| `manifest.json` | PWA install config |
| `sw.js` | Offline cache (service worker) |
| `icon-192.svg` / `icon-512.svg` | App icons |
| `loan-amortization-calculator.html` | Same calculator (backup name) |

## Branding

**Payal Motors** – Loan Amortization Calculator

## License

Free to use and modify.
