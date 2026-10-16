BRANDABSCHOTTUNG – ERSTE TESTVERSION (PWA)

Inhalt: index.html, style.css, app.js, sw.js, manifest.webmanifest, icon.svg

Installation:
1. Alle Dateien gemeinsam auf einer HTTPS-Webadresse veröffentlichen (z. B. GitHub Pages).
2. Android: Seite in Chrome öffnen und „App installieren“/„Zum Startbildschirm hinzufügen“ wählen.
3. iPhone: Seite in Safari öffnen, Teilen -> „Zum Home-Bildschirm“.
4. Die App mindestens einmal online öffnen, damit sie für den Offlinebetrieb zwischengespeichert wird.

WICHTIG:
- Daten und Fotos werden lokal im Browser (IndexedDB) gespeichert. Kein Server erforderlich.
- Nach Löschen der Website-Daten oder Deinstallation können lokale Daten verloren gehen. Daher regelmäßig „Auftrag sichern (JSON)“ verwenden. Über „Sicherung importieren“ wiederherstellen.
- „Gesamt-PDF erstellen / drucken“ öffnet den Druckdialog. Dort als PDF sichern. Dies ist eine vorläufige PDF-Gestaltung, noch NICHT die exakte Eintragung in die ursprüngliche PDF-Vorlage.
- Vor PDF-Ausgabe jeden Schott mit „Schott speichern“ oder „Nächster Schott“ speichern.
- Kein automatischer E-Mail-Versand in dieser Version. Die PDF kann nach dem Speichern über das E-Mail-Programm geteilt werden (Internet erforderlich).
- Der Druckdialog des Geräts entscheidet über Seiteneinteilung. Bei sehr vielen Positionen kann eine Seite überlaufen; die endgültige Ein-Seite-pro-Schott-PDF-Erzeugung ist noch umzusetzen.
- Die App läuft nicht zuverlässig als PWA beim direkten Öffnen der HTML-Datei (file://). Verwende HTTPS oder zum Entwickeln einen lokalen Webserver.
