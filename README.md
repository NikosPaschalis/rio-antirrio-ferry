# 🚢 Ρίο–Αντίρριο Πορθμείο Live

Ζωντανή πληροφοριακή εφαρμογή για το πορθμείο **Ρίο–Αντίρριο** (Κόλπος Πατραϊκός, Ελλάδα).

🔗 **Live site:** [rio-antirrio-ferry.netlify.app](https://rio-antirrio-ferry.netlify.app/)

---

## ✨ Χαρακτηριστικά

- **⏱ Live αντίστροφη μέτρηση** — Επόμενη αναχώρηση από Ρίο & Αντίρριο ανεξάρτητα
- **🗓 Πλήρη δρομολόγια 2026** — Πρωί / Απόγευμα / Βράδυ για κάθε λιμάνι
- **💶 Τιμοκατάλογος** — Ναύλοι, σύγκριση & χρήσιμες πληροφορίες σε tabs
- **🚢 Ζωντανή παρακολούθηση πλοίων** — VesselFinder AIS map
- **🌬 Καιρός & Άνεμος** — Open-Meteo API + Windfinder iframe
- **📍 Χρήσιμες πληροφορίες** — Τηλέφωνα, συντεταγμένες, σύνδεσμοι
- **🌐 Δίγλωσσο** — Ελληνικά / Αγγλικά
- **🔗 Hash routing** — Bookmarkable URLs (`#schedule`, `#prices`, `#weather`…)
- **📱 Responsive** — Mobile-first design

---

## 🗂 Δομή αρχείων

```
rio-antirrio-ferris/
├── index.html          # Κύρια SPA εφαρμογή
├── styles.css          # Όλα τα styles
├── map.html            # Σελίδα ζωντανής παρακολούθησης
├── sitemap.xml         # SEO sitemap
├── robots.txt          # SEO robots
└── google…html         # Google Search Console verification
```

---

## 🛠 Τεχνολογίες

| | |
|---|---|
| Frontend | Vanilla HTML / CSS / JavaScript |
| Hosting | [Netlify](https://netlify.com) |
| Καιρός | [Open-Meteo API](https://open-meteo.com) |
| Πλοία | [VesselFinder](https://www.vesselfinder.com) |
| Άνεμος | [Windfinder](https://www.windfinder.com) |
| Analytics | Google Analytics |
| Worker | Cloudflare Workers |

---

## 🚀 Deploy

Το site γίνεται deploy αυτόματα μέσω Netlify από το `main` branch.

```bash
git add .
git commit -m "your message"
git push
```

---

## 📄 Άδεια χρήσης

Ανεξάρτητο προσωπικό project. Τα δρομολόγια είναι ενδεικτικά — επαληθεύετε πάντα με τις λιμενικές αρχές.
