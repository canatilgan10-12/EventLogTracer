# EventLog Tracer

Windows-Anwendung zur **lokalen Analyse und Überwachung von Windows-Ereignisprotokollen**. Der Event Log Tracer (ELT) macht die Ereignisanzeige übersichtlicher, findet Auffälligkeiten automatisch und löst bei bestimmten Ereignissen Alerts aus.

> Entwickelt während meines Praktikums. Die Screenshots zeigen Beispieldaten.

## Was das Tool macht

- **Ereignisse durchsuchen und filtern:** nach Kanal, Level, Text, Event-IDs (auch Ausschluss), Quelle und Zeitraum. Der Folgen-Modus zeigt neue Ereignisse live.
- **Details auf einen Blick:** Detailansicht, XML und ein Wissensbereich zum ausgewählten Ereignis.
- **Volltextsuche** mit speicherbaren Suchen.
- **Statistik:** Ereignisse über Zeit, Verteilung nach Level, häufigste Event-IDs und Quellen.
- **Auffälligkeiten:** Erkennt zum Beispiel seltene Event-IDs, erhöhte Fehlerraten im Vergleich zur Baseline und Security-Signale wie einen neu installierten Dienst. Bürotage und Bürozeiten sind konfigurierbar.
- **Alerts:** Regeln mit Bedingung und Aktion (Übersicht, Webhook) samt Verlauf.
- **Lesezeichen** mit Farbe und Kommentar, zum Beispiel für Ticket-Verweise.
- **Export und Bericht**, mehrere Tabs, Split View, helles und dunkles Design sowie Tastenkürzel.

## Screenshots

### Hauptfenster (hell und dunkel)

<img src="screenshots/01-hauptfenster-hell.png" alt="Hauptfenster hell" width="800">

<img src="screenshots/02-hauptfenster-dunkel.png" alt="Hauptfenster dunkel" width="800">

### Statistik

<img src="screenshots/03-statistik.png" alt="Statistik" width="800">

### Suche

<img src="screenshots/04-suche.png" alt="Suche" width="800">

### Auffälligkeiten

<img src="screenshots/05-auffaelligkeiten.png" alt="Auffälligkeiten" width="800">

### Alerts

<img src="screenshots/06-alerts.png" alt="Alerts" width="800">

### Lesezeichen

<img src="screenshots/07-lesezeichen.png" alt="Lesezeichen" width="800">

### Einstellungen

<img src="screenshots/08-einstellungen-allgemein.png" alt="Einstellungen: Allgemein" width="400">
<img src="screenshots/09-einstellungen-kanaele.png" alt="Einstellungen: Kanäle" width="400">
<img src="screenshots/10-einstellungen-auffaelligkeiten.png" alt="Einstellungen: Auffälligkeiten" width="400">

### Tastenkürzel

<img src="screenshots/11-tastenkuerzel.png" alt="Tastenkürzel" width="250">
