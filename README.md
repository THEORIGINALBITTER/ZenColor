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
