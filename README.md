# ⚡ Hyperboloid Generator ⚡

Eine extrem futuristische Web-Anwendung zur Erstellung und Manipulation von Hyperboloiden mit Echtzeit-3D-Rendering.

## 🚀 Features

### 23+ Interaktive Steuerelemente

#### 🔷 Geometrie (6 Kontrollen)
- **Taille (Radius A)**: Steuert den Basisradius (0.1-5.0)
- **Höhe (Limit Z)**: Steuert die Höhe (1.0-10.0)
- **Krümmung (Koeff. C)**: Steuert die Krümmung (0.1-3.0)
- **Verdrehung (Twist)**: Fügt Drehung hinzu (0-6.28 rad)
- **Segmente (Auflösung)**: Steuert die Geometrieauflösung (8-140)
- **Dicke (Thickness)**: Steuert die Dicke der Form (0.1-2.0)

#### 🔄 Transformation (4 Kontrollen)
- **Rotation X/Y/Z**: Steuert die Rotation auf allen Achsen (0-6.28 rad)
- **Skalierung**: Universelle Skalierung (0.2-3.0)

#### 🎨 Material & Farben (7 Kontrollen)
- **Primärfarbe**: Hauptfarbe des Objekts
- **Sekundärfarbe**: Sekundäre/Emissionsfarbe
- **Akzentfarbe**: Partikelfarbe
- **Metallic**: Metallische Oberfläche (0-1)
- **Roughness**: Oberflächenrauheit (0-1)
- **Emissive**: Leuchtintensität (0-2)
- **Opacity**: Transparenz (0.1-1)

#### 🎬 Animation (3 Kontrollen)
- **Geschwindigkeit**: Rotationsgeschwindigkeit (0-5x)
- **Puls-Rate**: Pulsierende Skalierung (0-3 Hz)
- **Auto-Rotation**: Ein/Aus-Schalter

#### 🖥️ Anzeige (5 Kontrollen)
- **Anzeige-Modus**: Netz/Solid/Partikel
- **Grid**: Boden-Grid anzeigen
- **Nebel**: Nebel-Effekt ein/aus

#### 🎯 Presets (8 Kontrollen)
- **Default**: Standard-Einstellungen
- **Twisted**: Gedrehte Form
- **Dünn**: Dünne, hohe Form
- **Breit**: Breite, flache Form
- **Kristall**: Kristallines Aussehen
- **Neon**: Neon-Partikel-Effekt
- **Reset All**: Zurücksetzen auf Standard
- **Screenshot**: Bild speichern

## 🎨 Visuelle Effekte

- 🌟 **Scanline-Animation**: Retro-Futuristischer CRT-Effekt
- ✨ **Partikel-Hintergrund**: Animierte Hintergrundpartikel
- 🌈 **Gradient-Text**: Pulsierender Farbverlaufs-Text
- 💫 **Button-Ripple**: Interaktive Wellen-Effekte bei Hover
- 📂 **Collapsible Sections**: Klappbare Kontroll-Bereiche
- 🎨 **5 Neon-Farben**: Cyan, Pink, Purple, Green, Orange
- ✨ **Dynamische Beleuchtung**: Farben passen sich an Einstellungen an
- 📊 **Echtzeit-Statistiken**: FPS-Zähler und Vertex-Counter

## 🛠️ Technologie

- **Three.js**: WebGL 3D-Rendering
- **Vanilla JavaScript**: Keine zusätzlichen Frameworks
- **CSS3**: Moderne Animations- und Effekt-Techniken
- **Web Standards**: Keine Build-Tools erforderlich

## 🚀 Verwendung

1. Öffnen Sie `index.html` in einem modernen Webbrowser
2. Bei lokaler Verwendung: Starten Sie einen lokalen Server
   ```bash
   python -m http.server 8000
   # oder
   npx serve
   ```
3. Navigieren Sie zu `http://localhost:8000`
4. Experimentieren Sie mit den Steuerungen!

## 🎯 Browser-Anforderungen

- Moderne Browser mit WebGL-Unterstützung
- Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- JavaScript muss aktiviert sein
- WebGL muss aktiviert sein

## 📝 Hinweise

- Die Anwendung lädt Three.js von CDN (jsdelivr)
- Für Offline-Verwendung können Sie Three.js lokal hosten
- Beste Performance mit Hardware-Beschleunigung

## 🎨 Styling-Eigenschaften

```css
--neon-cyan: #00f3ff
--neon-pink: #ff0055
--neon-purple: #bc13fe
--neon-green: #39ff14
--neon-orange: #ff6b35
```

## 📸 Screenshots

Die Anwendung bietet eine integrierte Screenshot-Funktion.
Klicken Sie auf den "Screenshot"-Button, um das aktuelle Rendering zu speichern.

## 🤝 Beitragen

Dieses Projekt ist Open Source. Beiträge sind willkommen!

## 📄 Lizenz

MIT License - Frei verwendbar für persönliche und kommerzielle Projekte.

---

**Erstellt mit ⚡ und Three.js**
