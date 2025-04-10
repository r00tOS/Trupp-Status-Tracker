
# 🚑 Trupp Status Tracker

## Projektbeschreibung
Der Trupp Status Tracker ist eine webbasierte Anwendung zur Überwachung und Dokumentation von Einsatzkräften bei Veranstaltungen oder Einsätzen.

> Einsatzbereiche:  
Sanitätsdienste, Feuerwehr, Sicherheitsdienste, Event-Management

---

## 🛠 Features

### ✅ Truppverwaltung
- Anlegen und Bearbeiten von Trupps
- Verschiedene Status:
  - `Nicht Einsatzbereit`  
  - `Einsatzbereit in UHS`  
  - `Einsatzbereit unterwegs`  
  - `Einsatzbereit in Rückhaltung`  
  - `Streife` (mit Einsatzort)  
  - `Patient` (mit Patientennummer)  
  - `Spielfeldrand`  
- Automatische Zeiterfassung (Einsatzzeit & Pausenzeit)
- Historie der Einsatzorte und Patienten

---

### 🔢 Automatische Patientennummerierung
- Automatische Vergabe der nächsten freien Patientennummer beim Statuswechsel auf `Patient`
- Manuelle Korrektur der nächsten Nummer möglich
- Speicherung der Nummer im Browser (`LocalStorage`)
- Rücksetzen der Nummer über "Alle Trupps löschen"

---

### 📄 PDF-Export
- Erstellung eines übersichtlichen Einsatz-Reports als PDF
- Enthält:
  - Truppname
  - Gesamte Pausenzeit
  - Historie Einsatzorte
  - Historie Patienten
- Optimierte Seitenumbrüche

---

### 🌙 Darkmode
- Darkmode zur Augenschonung bei Nachteinsätzen
- Umschaltbar per Button
- Farben der Truppkarten bleiben unverändert für klare Erkennbarkeit

---

### 🖥 Bedienkomfort
- Automatische Speicherung der Daten im Browser
- Kein ungewolltes Scrollen bei Statusänderung
- Responsive Design
- Animationen bei Statuswechsel und Truppänderungen

---

## 📦 Verwendete Technologien
- HTML5  
- CSS3  
- Vanilla JavaScript  
- jsPDF (für PDF-Export)  
- LocalStorage (lokale Datenspeicherung)

---

## 💾 Struktur

```bash
/
├── index.html            # Hauptdatei
├── styles.css            # Styles (optional ausgelagert)
├── trupp_status_report.pdf  # Generiertes PDF-Export Dokument
└── README.md             # Projektdokumentation
```

---

## 🚀 Nutzung / Installation

1. Projekt-Dateien herunterladen oder klonen.
2. Lokal im Browser öffnen (Chrome, Firefox empfohlen).
3. Trupps anlegen und verwalten.
4. PDF-Report generieren.

---

## 🔮 Zukünftige Erweiterungen

- Anbindung an MySQL-Datenbank (für Mehrplatzfähigkeit & Serverbetrieb)
- Realtime-Synchronisation (mehrere Benutzer gleichzeitig)
- Benutzerverwaltung (Admin / Beobachter)
- Export als CSV / Excel
- Statistiken und Auswertung

---

## 👨‍💻 Entwickler

Projektleitung & Umsetzung:  
Chris Rossol
