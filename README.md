# Bairytale Neo-Brutalist Website

Eine moderne Neo-Brutalist Website für Bairytale - Texte, die wirken.

## 🎨 Design-Konzept

Diese Website wurde im Neo-Brutalist Stil gestaltet, der rohe, ungeschönte Ästhetik mit digitaler Funktionalität verbindet. Das Design zeichnet sich aus durch:

- **Authentizität über Perfektion**: Handgemachte Optik ohne überpolierte Elemente
- **Starke Kontraste**: Extreme visuelle Hierarchien durch geometrische Formen
- **Funktionalität zuerst**: Jedes Element hat einen klaren Zweck
- **Digitale Rohheit**: Scharfe Kanten, harte Schatten, pixelige Elemente

## 🎨 Farbpalette

- **Primär**: #004D4D (Dunkles Petrol)
- **Sekundär**: #F5F5DC (Beige) 
- **Text**: #7A7A7A (Grau)
- **Dark Petrol**: #003333
- **Accent**: #D4AF37 (Gold)
- **Accent 2**: #FF6B6B (Koralle)

## 📝 Typografie

- **Headlines**: Alegreya (Serif)
- **Body Text**: Alegreya Sans (Sans-Serif)
- **Code/Technical**: JetBrains Mono (Monospace)

## 📁 Dateistruktur

```
bairytale-neo-brutalist/
├── index.html              # Hauptseite
├── dienstleistungen.html   # Dienstleistungsseite
├── portfolio.html          # Portfolio im Index-Listen-Stil
├── blog.html              # Blog-Übersicht
├── blog-post.html         # Blog-Post Template
├── ueber-mich.html        # Über mich Seite
├── impressum.html         # Impressum
├── datenschutz.html       # Datenschutzerklärung
├── css/
│   └── style.css          # Haupt-CSS-Datei
├── images/                # Bilder-Ordner (leer)
├── js/                    # JavaScript-Ordner (leer)
└── README.md              # Diese Datei
```

## 🚀 Deployment auf GitHub Pages

1. Erstelle ein neues Repository auf GitHub
2. Lade alle Dateien aus diesem Ordner hoch
3. Gehe zu Settings > Pages
4. Wähle "Deploy from a branch" und "main"
5. Die Website ist dann unter `https://username.github.io/repository-name` verfügbar

## 🔧 CloneWebX/Elementor Integration

Diese Website wurde speziell für die Integration mit CloneWebX und Elementor entwickelt:

- **Reines HTML/CSS**: Kein JavaScript für maximale Kompatibilität
- **Semantisches HTML**: Saubere Struktur für einfaches Kopieren
- **CSS Custom Properties**: Einfache Anpassung der Farben und Abstände
- **Responsive Design**: Mobile-first Ansatz
- **Modularer Aufbau**: Einzelne Komponenten können isoliert kopiert werden

## 📱 Responsive Design

Die Website ist vollständig responsive und optimiert für:

- **Mobile**: 320px - 767px
- **Tablet**: 768px - 1023px
- **Desktop**: 1024px+
- **Large Desktop**: 1400px+

## ♿ Accessibility

- WCAG AA konforme Kontrast-Verhältnisse
- Vollständige Keyboard-Navigation
- Screen Reader optimiert
- Focus States für alle interaktiven Elemente
- Respektiert `prefers-reduced-motion`

## 🎯 Besondere Features

### Portfolio-Index-Seite
- Terminal/Console-inspiriertes Design
- Projekt-Codes im Format "CW-001", "ST-002", etc.
- Kategorie-Filter mit farbcodierten Tags
- Hover-Effekte für bessere Interaktion

### Neo-Brutalist Elemente
- Harte Drop-Shadows (8px 8px 0px)
- Scharfe, rechteckige Formen
- Glitch-Animationen
- Pixelated Icons und Grafiken
- Monospace-Typography für technische Elemente

## 🛠️ Anpassungen

### Farben ändern
Alle Farben sind als CSS Custom Properties definiert in `:root`:
```css
:root {
  --primary: #004D4D;
  --secondary: #F5F5DC;
  --accent: #D4AF37;
  /* ... */
}
```

### Schriftarten ändern
```css
:root {
  --font-serif: 'Alegreya', serif;
  --font-sans: 'Alegreya Sans', sans-serif;
  --font-mono: 'JetBrains Mono', monospace;
}
```

## 📄 Lizenz

Dieses Projekt wurde für Bairytale erstellt. Alle Inhalte und Texte sind urheberrechtlich geschützt.

---

**Erstellt mit ❤️ im Neo-Brutalist Stil**

