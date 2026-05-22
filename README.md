[README.md](https://github.com/user-attachments/files/28160211/README.md)
# LN# FundingMatch — KI-Förderanalyse Platform

Single-File App · Kein Backend · Kostenlos hostbar

## Kostenlose Hosting-Optionen

### Option A: GitHub Pages (empfohlen, 100% kostenlos)
1. GitHub Account erstellen (kostenlos)
2. Neues Repository erstellen: `fundingmatch`
3. `index.html` hochladen
4. Settings → Pages → Branch: `main` → Save
5. URL: `https://DEIN-USERNAME.github.io/fundingmatch`

### Option B: Netlify Drop (einfachste Option)
1. netlify.com → "Deploy manually"
2. `index.html` per Drag & Drop hochladen
3. Sofort live unter zufälliger URL

### Option C: Vercel
1. vercel.com → Import Project
2. Repository verbinden oder Datei hochladen
3. Kostenlos für private/personal Projects

## Nutzung

1. Seite öffnen
2. Anthropic API-Key eingeben (einmalig, wird im Browser gespeichert)
3. Optional: Unternehmensprofil anlegen
4. Förderanalyse starten

## API-Kosten

- Claude Sonnet 4: ~$3 per 1M Input-Tokens
- Typische Anfrage: ~500-1000 Tokens = $0.001-0.003 pro Chat
- Für private Nutzung: vernachlässigbar

## Architektur

```
index.html (Single File)
├── React 18 (CDN)
├── Anthropic API (direkter Browser-Zugriff)
├── localStorage (API-Key + Profil)
└── Keine externen Abhängigkeiten
```

## Geplante Erweiterungen (Roadmap)

- [ ] Pitch Deck Upload (PDF-Analyse)
- [ ] EU Funding Database API Integration
- [ ] Automatisches Scoring-Modell
- [ ] Bewerbungsassistent (Antragstext-Generator)
- [ ] Mehrsprachigkeit (EN/FR)
- [ ] Nutzer-Accounts (Supabase free tier)
- [ ] Crunchbase API Integration
