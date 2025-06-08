# Co2-Ampel-Projekt

Dieses Projekt überwacht die CO₂-Konzentration in einem Raum. Eine LED-Ampel zeigt die Luftqualität:

- **Grün**: Gute Luftqualität
- **Gelb**: Mittelmäßige Luftqualität
- **Rot**: Schlechte Luftqualität

## Ziele

- Messung per Sensor (z. B. MH-Z19 oder SCD30)
- Schwellenwerte definieren (in ppm)
- Ampel visualisiert aktuelle CO₂-Werte
- Projekt folgt EVA-Prinzip (Diagramme enthalten)

## Struktur

- dokumentation/
- bilder/
- code/# co2-ampel-projekt


## 📊 Visualisierungsmöglichkeiten der CO₂-Konzentration

Das System kann die CO₂-Werte auf verschiedene Arten anzeigen. Ziel ist eine einfache und schnelle Erkennung der Luftqualität im Raum.

### 🟢 1. LED-Ampel

- **Grün:** gute Luft (unter 800 ppm)
- **Gelb:** mittelmäßige Luft (800–1200 ppm)
- **Rot:** schlechte Luft (über 1200 ppm)

→ Diese Variante ist lokal, simpel und günstig. Perfekt für Räume ohne Display oder Internet.

---

### 🖥️ 2. Anzeige auf OLED-/LCD-Display

- Anzeige des aktuellen CO₂-Werts in ppm
- Optional: Temperatur & Luftfeuchtigkeit
- Farbige Textdarstellung je nach Luftqualität

→ Genauere Werte, direkt ablesbar am Gerät.

---

### 🌐 3. Online-Darstellung über Webbrowser

- Live-Anzeige per WLAN oder Bluetooth
- Web-App oder IoT-Plattform (z. B. Grafana, Thingspeak)
- Diagramme und Langzeitüberwachung möglich

→ Ideal für smarte Räume, Schulen, Büros.

