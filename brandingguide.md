# 🚕 Brandingguide – Taxi-Unternehmen

**Kunde:** Oma Beck (Vermittlung)  
**Projekt:** Taxi-Unternehmen Website  
**Zielgruppe:** Kurgäste, Touristen, Ortsunkundige  
**Erstellt:** 2026-03-19

---

## 1. Farbkonzept

### Primary Colors
| Farbe | Hex | Verwendung |
|-------|-----|------------|
| **Taxi Gelb** | `#F4C430` | Akzente, CTA-Buttons, Highlights |
| **Tiefes Schwarz** | `#1A1A1A` | Haupttext, Footer, Kontrastflächen |

### Secondary Colors
| Farbe | Hex | Verwendung |
|-------|-----|------------|
| **Warmes Grau** | `#6B7280` | Sekundärtext, Subheadlines |
| **Helles Creme** | `#FDF8F3` | Hintergründe, Karten |
| **Sattes Grün** | `#10B981` | Erfolgsmeldungen, Verfügbarkeit |

### Accent Colors
| Farbe | Hex | Verwendung |
|-------|-----|------------|
| **Signalrot** | `#EF4444` | Fehlermeldungen, Pflichtfelder |
| **Sonniges Orange** | `#F97316` | Hover-States, kleine Akzente |

---

## 2. Typografie

### Headlines
- **Font:** Inter (Google Fonts)
- **Weights:** 700 (Bold), 800 (ExtraBold)
- **H1:** 48px / 1.1 line-height
- **H2:** 36px / 1.2 line-height
- **H3:** 24px / 1.3 line-height

### Body Text
- **Font:** Inter
- **Weight:** 400 (Regular), 500 (Medium)
- **Size:** 16px / 1.6 line-height
- **Paragraph spacing:** 1.5rem

### Spezial
- **Preise/Nummern:** Inter 600, 32px
- **Kontaktinfos:** Inter 500, 18px

---

## 3. Layout-Prinzipien

### Grid
- **Container max-width:** 1200px
- **Padding:** 1.5rem (mobile), 3rem (desktop)
- **Grid:** 12-Spalten, Gap 24px

### Spacing Scale
```
4px  → 0.25rem  → xs
8px  → 0.5rem   → sm
16px → 1rem     → base
24px → 1.5rem   → md
32px → 2rem     → lg
48px → 3rem     → xl
64px → 4rem     → 2xl
```

### Sections
- **Hero:** 100vh oder min 600px
- **Content Sections:** Padding 80px vertical
- **Footer:** Dunkler Hintergrund, kompaktes Layout

---

## 4. Visuelle Elemente

### Buttons

**Primary Button**
- Background: `#F4C430`
- Text: `#1A1A1A`
- Padding: 16px 32px
- Border-radius: 8px
- Font-weight: 600
- Hover: Dunkleres Gelb (`#E5B526`)

**Secondary Button**
- Background: transparent
- Border: 2px solid `#1A1A1A`
- Text: `#1A1A1A`
- Hover: `#1A1A1A` bg, white text

### Formulare (Kontaktformular)

**Input Fields**
- Border: 1px solid `#E5E7EB`
- Border-radius: 8px
- Padding: 12px 16px
- Focus: Border `#F4C430`, Shadow 0 0 0 3px rgba(244,196,48,0.2)

**Pflichtfelder**
- Markierung: Roter Asterisk `*`
- Fehlermeldung: `#EF4444` mit Icon

**Submit Button**
- Full-width auf Mobile
- Primary Button Style

### Cards
- Background: White oder `#FDF8F3`
- Border-radius: 12px
- Shadow: 0 4px 6px rgba(0,0,0,0.05)
- Padding: 24px

### Icons
- **Style:** Outline, 2px stroke
- **Size:** 24px (Standard), 48px (Hero)
- **Library:** Lucide oder Heroicons

---

## 5. Stimmung & Moodboard

### Keywords
1. **Verlässlich** – Pünktlich, professionell, vertrauenswürdig
2. **Ortskenntig** – Lokaler Experte, Insider-Wissen
3. **Herzlich** – Persönlich, familiär, gastfreundlich
4. **Modern** – Aktuell, technisch auf dem neuesten Stand
5. **Zugänglich** – Einfache Buchung, klare Kommunikation

### Visuelle Richtung
- **Fotografie:** Echte Taxi-Fotos (nicht Stock), freundliche Fahrer, lokale Sehenswürdigkeiten
- **Illustrationen:** Minimal, nur wenn nötig
- **Atmosphäre:** Aufgeräumt, einladend, professionell ohne steif zu wirken

### Bildsprache
- Menschen in Bewegung (nicht statisch)
- Lokale Landmarken im Hintergrund
- Warme, natürliche Farbtemperatur
- Authentisch, nicht überproduziert

---

## 6. Seitenstruktur (4-5 Seiten)

1. **Home** – Hero mit Buchungs-CTA, Leistungen, Kurz-Über-uns
2. **Leistungen** – Flughafen, Kurorte, Stadttouren, Preise
3. **Über uns** – Team, Erfahrung, Ortskenntnis
4. **Kontakt** – Formular MIT Pflichtfeldern, Telefon, Adresse
5. **(Optional) FAQ** – Häufige Fragen, Gepäck, Haustiere

---

## 7. Responsive Breakpoints

- **Mobile:** < 640px
- **Tablet:** 640px – 1024px
- **Desktop:** > 1024px

**Mobile-First Approach:**
- Hamburger-Menü
- Stacked Layouts
- Touch-friendly Buttons (min 44px)
- Click-to-Call Telefonnummer

---

## 8. SEO-Notizen

- Lokale Keywords: "Taxi [Ort]", "Flughafentransfer [Ort]"
- Google Business Profil verlinken
- Schema.org LocalBusiness Markup
- Schnelle Ladezeit (wichtig für mobile Suche)

---

**Status:** 🎨 Bereit zur Freigabe durch Philipp
**Nächster Schritt:** Nach Freigabe → Entwicklung durch UWE
