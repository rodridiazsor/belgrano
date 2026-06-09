# Belgrano Studio · Welcome Guide

Bilingual (English / Spanish) welcome guide for guests staying at the Belgrano Studio Airbnb in Buenos Aires, Argentina.

🌐 **Live site:** https://rodridiazsor.github.io/belgrano/

## About

A single-page guide covering everything a guest needs during their stay:

- Arrival from Ezeiza and Aeroparque airports
- Money in Argentina (the MEP rate, Western Union, what to avoid)
- Public transit (subway, train, buses, Ecobici bikes)
- House rules
- Neighborhood attractions with Google Maps links
- Personal restaurant and café recommendations
- How to use the parrilla (Argentine BBQ)
- Practical tips
- Emergency numbers
- Check-out instructions

## Bonus: Brújula solar 🌞

A standalone tool to find the Sun's position by pointing your phone.

🌐 **Live:** https://rodridiazsor.github.io/belgrano/sol.html

- Uses the phone's **compass** + **GPS** to show where the Sun is (azimuth & altitude)
- **Camera (AR) mode**: point your phone and see the Sun marker overlaid on the real view
- **Time slider** to preview the Sun's position at any hour, plus sunrise/sunset directions
- Self-contained `sol.html`, no dependencies — solar math (SunCalc/NOAA) runs fully offline
- Installable as a PWA ("Add to Home Screen") via `sol.webmanifest` + service worker
- Manual compass-offset slider for calibration

> Requires HTTPS (GitHub Pages provides it). On iOS, tap **Comenzar** to grant motion/orientation access.

## Stack

- Single-file HTML, CSS, vanilla JS
- No build step, no dependencies
- Hosted on GitHub Pages
- Mobile-first design
- Bilingual toggle with browser language auto-detection
- Print-friendly (works as PDF when printed from browser)

## Privacy

No personal contact info, Wi-Fi credentials, or access codes are stored in this public repo. Those are shared with confirmed guests via the Airbnb chat.

## License

Personal project. Feel free to use the structure as inspiration for your own listing.
