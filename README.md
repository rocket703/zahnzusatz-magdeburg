# Zahnzusatz Microsite – Zahnzusatzversicherung Magdeburg

Eine moderne, responsive Onepage-Microsite für die **Zahnzusatzversicherung in Magdeburg & Umgebung**.  
Ziel: Interessenten verständlich informieren und eine **DSGVO-konforme Kontaktaufnahme** ermöglichen.

---

## Projektüberblick

**Live-Demo:** [https://zahnzusatzversicherung-magdeburg.de](https://zahnzusatzversicherung-magdeburg.de)

**Technologien**
- HTML5, CSS3, Vanilla JavaScript  
- Mobile-first Responsive Design  
- Accessibility & On-Page-SEO  
- Formularversand über **Web3Forms** (kein eigenes Backend)  
- Hosting via **GitHub Pages** / Netlify

---

## Verzeichnisstruktur

```
/
├─ assets/
│  ├─ css/
│  │  └─ style.css                # Hauptstylesheet
│  ├─ js/
│  │  └─ main.js                  # Navigation, kleine Interaktionen
│  └─ img/                        # Bilder, Favicons, OG-Images
│
├─ kontakt/
│  └─ index.html                  # Kontaktformular (Web3Forms-Integration)
│
├─ impressum/
│  └─ index.html                  # Anbieterkennzeichnung (TMG)
│
├─ datenschutz/
│  └─ index.html                  # Datenschutzhinweise (DSGVO)
│
├─ robots.txt                     # Crawling-Regeln + Sitemap-Hinweis
├─ sitemap.xml                    # XML-Sitemap der Seiten
├─ 404.html                       # Fehlerseite mit Vollbild-Hero
└─ index.html                     # Startseite (Hero, Nutzen, CTAs)
```

---

## Features

### Design
- Reduziertes, vertrauenswürdiges Layout in warmen Erdtönen  
- Typografie mit *Inter* & *Sora*  
- Hero-Bereich mit CTA, sanfte Scroll-Reveals (`.reveal`)

### Responsive
- Mobile-first Grids (`.grid-2`, `.process`, `.kpi`)  
- Sticky Header + Burger-Navigation  

### Kontaktformular (Web3Forms)
- DSGVO-konformer Versand **ohne eigenes Backend**  
- **hCaptcha**-Validierung vor dem Absenden (Anti-Bot)  
- Honeypot-Feld gegen Spam (`.hp`)  
- Asynchrones `fetch()` + Live-Statusmeldungen   

---

## Rechtliches
- Impressum & Datenschutz unter `/impressum/` und `/datenschutz/`  
- Inhalte gemäß § 5 TMG / DSGVO  
- © **Torsten Römer / Dustin Rose**  

---

## Entwicklung
**r³webdesign – Dustin Rose**  
Fokus auf Performance, Barrierefreiheit und einfache Wartung.

---

## Lizenz
Dieses Projekt ist urheberrechtlich geschützt und **nicht zur kommerziellen Weiterverwendung freigegeben.**  
Für Rebrandings oder Weiterverwendung bitte vorher Kontakt aufnehmen.

---
