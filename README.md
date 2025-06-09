# ZenColor
ZenColor Kit ein Farbsystem für Frontendentwickler

# ZenColor Kit

Ein flexibles und modernes SwiftUI ColorKit für individuelle Farbpalette mit JSON & HEX Export, Farbkreis, RGB-Slider und Schachbrett-Hintergrund.

---

## Features

- Intuitive Farbwahl per Farbkreis oder RGB-Slider
- Steuerung von Farbton (Hue), Sättigung (Saturation), Helligkeit (Brightness) und Alpha (Transparenz)
- Live Vorschau der aktuell ausgewählten Farbe mit Schachbrett-Hintergrund
- Verwaltung einer benutzerdefinierten Farbpalette mit Namen
- Farbpalette kann als JSON exportiert werden
- HEX-Wert per Klick kopierbar (Clipboard Support)
- Moderne UI mit monospaced Font und klarer Struktur
- Eingebetteter Footer mit persönlichem Logo und Social Media Links
- Unterstützung für hellen und dunklen Modus (Checkerboard-Hintergrund passt sich an)
- Fokus-Handling und UI-Feedback bei Farbänderungen

---

## Installation

Das ZenColor Kit ist als SwiftUI-View konzipiert und benötigt Swift 5+ mit macOS/iOS 14+.

Einbinden:

```swift
import SwiftUI
import BitterUIComponents // Voraussetzung: Eigene Komponentenbibliothek

struct ContentView: View {
    var body: some View {
        ColorKit_Preview()
    }
}



# ZenColor Kit

## Nutzung

### Farbwahl
- Schalte zwischen Farbkreis und RGB-Slider mit dem Button um.
- Farbton, Sättigung, Helligkeit und Alpha können individuell eingestellt werden.
- Neue Farben können mit einem Namen versehen und zur Palette hinzugefügt werden.

### Palette
- Gespeicherte Farben werden in der Liste angezeigt mit Vorschau, Namen, RGB-Werten und HEX-Code.
- HEX-Code kann durch Klick kopiert werden, mit Bestätigung "kopiert" als Feedback.
- Palette kann als JSON exportiert und z.B. in anderen Projekten verwendet werden.

## Komponentenübersicht

| Komponente              | Beschreibung                                                                 |
|-------------------------|------------------------------------------------------------------------------|
| `ColorCircle`           | Farbkreis zur intuitiven Farbwahl                                            |
| `MonoSlider`            | RGB-, Saturation-, Brightness- und Alpha-Slider mit farblicher Kennzeichnung |
| `CheckerboardView`      | Schachbrett-Hintergrund zur transparenten Farbdarstellung                    |
| `MonoButton`            | Stilisiert Buttons mit Icon und Text                                         |
| `NoFocusRingTextField`  | Eingabefeld ohne Fokus-Ring (sauberes UI)                                    |

## Technische Details

- Farbkonvertierung basiert auf `NSColor` mit kalibrierten Farbkomponenten.
- Synchronisation von Hue ↔ RGB erfolgt bidirektional mit State-Handling.
- Alpha-Komponente wird vollständig unterstützt.
- Dynamische Anpassung an Light/Dark Mode im Schachbrett-Hintergrund.
- Palette wird beim Start geladen, lokale Speicherung optional über `ColorKit.loadCustomPalette()`.

## Vorschau

*(Screenshot Beispiel einfügen)*

## Lizenz

MIT License – frei nutzbar und anpassbar.

## Kontakt & Support

- Webseite: [theoriginalbitter.de](https://www.theoriginalbitter.de)
- Instagram: [@theoriginalbitter](https://www.instagram.com/theoriginalbitter)
- LinkedIn: [theoriginalbitter](https://www.linkedin.com/in/theoriginalbitter)
- YouTube: [theoriginalbitter](https://www.youtube.com/@theoriginalbitter)

---

Danke für dein Interesse am ZenColor Kit!  
Viel Spaß beim Farbmischen 🎨

bitter. Lern Einfach. Authentisch

