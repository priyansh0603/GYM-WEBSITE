# FitZone — Train Smart

A simple static marketing website for a gym called **FitZone**. Black & gold theme, responsive sections for hero, programs, trainers, areas and pricing. Built with plain HTML and CSS.

---

## Project files (uploaded)

- `index.html` — Home page (hero, programs, services, pricing, newsletter, footer).  
  Local file path: `/mnt/data/index.html`. :contentReference[oaicite:0]{index=0}

- `about.html` — About / Meet the Trainers page.  
  Local file path: `/mnt/data/about.html`. :contentReference[oaicite:1]{index=1}

- `style.css` — All styling (black + gold theme, components, trainers cards, pricing).  
  Local file path: `/mnt/data/style.css`. :contentReference[oaicite:2]{index=2}

---

## Quick demo (run locally)

Open the project in your browser:

1. Best (serves files over HTTP — fixes CORS / font issues):
   ```bash
   cd /mnt/data
   python3 -m http.server 8000
   # Then open: http://localhost:8000/index.html

/mnt/data/
├── index.html       # Home page — hero, programs, pricing, newsletter
├── about.html       # About / Meet the Trainers page
└── style.css        # Main stylesheet (black & gold theme)
