# 🚢 Rio–Antirrio Ferry Live

A real-time information app for the **Rio–Antirrio ferry** crossing (Patraikos Gulf, Greece).

🔗 **Live site:** [rio-antirrio-ferry.netlify.app](https://rio-antirrio-ferry.netlify.app/)

---

## ✨ Features

- **⏱ Live countdown** — Next departure from Rio & Antirrio independently
- **🗓 Full 2026 schedule** — Morning / Afternoon / Night per port
- **💶 Fare guide** — Fares, comparison & useful info in tabs
- **🚢 Live vessel tracking** — VesselFinder AIS map
- **🌬 Weather & Wind** — Open-Meteo API + Windfinder iframe
- **📍 Useful info** — Phone numbers, coordinates, links
- **🌐 Bilingual** — Greek / English
- **🔗 Hash routing** — Bookmarkable URLs (`#schedule`, `#prices`, `#weather`…)
- **📱 Responsive** — Mobile-first design

---

## 🗂 File structure

```
rio-antirrio-ferry/
├── index.html          # Main SPA
├── styles.css          # All styles
├── map.html            # Live vessel tracking page
├── sitemap.xml         # SEO sitemap
├── robots.txt          # SEO robots
└── google…html         # Google Search Console verification
```

---

## 🛠 Tech stack

| | |
|---|---|
| Frontend | Vanilla HTML / CSS / JavaScript |
| Hosting | [Netlify](https://netlify.com) |
| Weather | [Open-Meteo API](https://open-meteo.com) |
| Vessels | [VesselFinder](https://www.vesselfinder.com) |
| Wind | [Windfinder](https://www.windfinder.com) |
| Analytics | Google Analytics |
| Worker | Cloudflare Workers |

---

## 🚀 Deploy

Site auto-deploys via Netlify from the `master` branch.

```bash
git add .
git commit -m "your message"
git push
```

---

## 📄 License

Independent personal project. Schedules are indicative — always verify with port authorities.
