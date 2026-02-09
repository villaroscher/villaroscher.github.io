# Villa Roscher Website

Offizielle Website der Villa Roscher – Feriendomizil in Neugersdorf, Oberlausitz.

## Technologie

- **Static Site Generator:** Jekyll
- **Theme:** Minimal Mistakes
- **Hosting:** GitHub Pages

## Lokale Entwicklung

```bash
# Dependencies installieren
bundle install

# Lokalen Server starten
bundle exec jekyll serve
```

Die Website ist dann unter `http://localhost:4000` erreichbar.

## Struktur

```
├── _config.yml       # Jekyll Konfiguration
├── _data/            # Navigation und Daten
├── _pages/           # Seiteninhalte
├── assets/
│   ├── css/          # Custom Styles
│   └── images/       # Bilder
├── index.md          # Startseite
└── Gemfile           # Ruby Dependencies
```

## Bilder hinzufügen

Platzieren Sie Bilder in `assets/images/`:
- `hero-villa.jpg` - Hauptbild für die Startseite
- `feature-*.jpg` - Feature-Bilder
- `gallery/*.jpg` - Galerie-Bilder

## Adresse

**Villa Roscher**  
Käthe-Kollwitz-Straße 3  
02727 Neugersdorf  
Sachsen, Deutschland
