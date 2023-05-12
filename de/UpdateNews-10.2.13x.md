# Update Hinweise zu byzz nxt (für Versionen 10.2.13x)

- [Neueste Änderungen](README.md)

## 10.2.139
- Die DVT-Abnahmeprüfung wurde in byzz Constancy hinzugefügt.
- Ein Fehler wurde behoben, durch den auf 32 Bit Systemen das mitgelieferte Postgres Setup nicht erkannt wurde.
- Weitere kleinere Fehler wurden behoben.

## 10.2.138
- Der VSP Folienscanner von Vatech wurde hinzugefügt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.137
- Die Ansicht der EzOrtho Einstellungen wurde überarbeitet.
- Ein Absturz wurde behoben, der auftrat, wenn in Netzwerken mit mehreren byzz Servern der Dialog zur Serverauswahl erscheinen sollte.
- Ein Absturz wurde behoben, der auftrat, wenn aus Serien heraus ein Bild per Drag and Drop auf den Desktop gezogen wurde.
- Die Darstellung von PLY-Modelldaten wurde überarbeitet.
- Weitere kleinere Fehler wurden behoben.

## 10.2.136
- Geräteeinstellungen – Kamera:
  - Für Tastenkombinationen wird jetzt zwischen langem und kurzen Drücken unterschieden.
  - Tastenkombinationen können jetzt zurückgesetzt werden.
- Bildbearbeitung: Es wurde ein neues Werkzeug bereitgestellt, mit dessen Hilfe der Knochenabbau gemessen werden kann.
- Parodontitis Klassifizierung (Staging/Grading): Es wurde eine neuer Dialog zur Unterstützung einer Parodontitis Therapie bereitgestellt, die den Knochenabbau aller gemessenen Zähne berücksichtigt.
- Multiframebilder vom Pax-i können jetzt gespeichert werden.
- Die GDT-Schnittstelle wurde erweitert, so dass Patienten auch anderen Programmen übergeben werden können.
- Scanvorgänge im Dokumentenmodul funktionieren jetzt wieder korrekt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.135
- Gelöschte Patienten können jetzt von Administratoren in der Patientenliste auf Wunsch (ohne Bilder) wiederhergestellt werden.
- Ein Fehler wurde behoben durch den im Dokumente-Modul keine Scanvorgänge mögliche waren.
- In byzz Constancy können jetzt Teilabnahmen durchgeführt werden.
- Setup: Über den Kommandozeilenschalter –qu (quiet uninstallation) kann jetzt auch die Deinstallation ohne Benutzerinteraktion durchgeführt werden.
- Weitere kleinere Fehler wurden behoben.

## 10.2.134
- Gelöschte Patienten können jetzt von Administratoren in der Patientenliste auf Wunsch angezeigt werden.
- Weitere kleinere Fehler wurden behoben.

## 10.2.133
- byzz Constancy:
  - Ein Fehler beim Import von Referenzaufnahmen wurde behoben.
  - Ein Fehler beim Abbruch von Uraufnahmen wurde behoben.
- Im Info Dialog wird jetzt angezeigt, wenn ein Patch durchgeführt wurde.
- Bildansicht: Notizen An-/Ausschalten funktioniert jetzt mit allen Anmerkungen.
- Weitere kleinere Fehler wurden behoben.

## 10.2.132
- Die Patch-Funktionalität funktioniert jetzt auch auf Einzelplatzsystemen korrekt.
- Konfigurator: Für die Multi-Praxen Unterstützung wurde die Option „Diesen Datenbankserver für Server in anderen Netzwerken verfügbar machen“ eingeführt, um ande-ren Server-Diensten den Datenbankzugang zu diesem Computer zu ermöglichen.
- Es wurde eine neue Bildanmerkung implementiert, mit deren Hilfe der Winkel zwischen zwei Geraden dargestellt werden kann.
- Weitere kleinere Fehler wurden behoben.

## 10.2.131
- Die Röntgenabnahme wurde an einigen Stellen stark überarbeitet und optimiert.
- Weitere kleinere Fehler wurden behoben.

## 10.2.130
- **Änderung der Speicherung der Patientendaten**
> Verzeichnisse der Patientendaten werden nicht länger über die Nummern der Patienten sondern basierend auf dem Datum zum Zeitpunkt der ersten Speicherung erstellt.
- Die Kontextsensitive Hilfe (F1) wurde überarbeitet.
- In der Fernröntgen-Ansicht können jetzt auch Demo-Bilder aufgenommen werden.
- Für Untermenüs, die Aktionen auf einem Zielbildschirm anbieten (z.B. Bildvergleich), wurde die „Zeige Bildschirminformationen“ Option hinzugefügt, um die aktuellen Monitorreihenfolge anzuzeigen.
- Für Vorschaubilder kann jetzt über das Menü Ansicht - Zeige Thumbnail Erstellungsdatum und –zeit das Erstellungsdatum angezeigt werden.
- Für bekannte Dateitypen wird jetzt in der Dokumentenansicht ein Vorschaubild angezeigt.
- Import:
  - Im Verzeichnisbaum kann jetzt auch über die Tastatur navigiert werden.
  - Dateien aus DICOM-DIR können jetzt importiert werden.
- Export:
  - Es wurde eine Option hinzugefügt durch die jetzt entschieden werden kann, ob die Exportverzeichnisse wie bisher nach Behandlungsdatum oder mit dem Datum zum Zeitpunkt des Exports angelegt werden.
  - Die Metadaten-Option „Patientendaten anonymisieren“ deaktiviert jetzt auch die Optionen „Patientenname“ und „Geburtstag“ der Ansichtsoptionen, sowie das Geburtsdatum der Zip-Optionen.
- Bildeigenschaften:
  - Die Option zum Anzeigen der Bildparameter wird jetzt beibehalten und nicht mehr deaktiviert, wenn keine Bildanzeigen (wie z.B. die Patientenliste oder die Einstellungen) aktiv sind. In diesen Fällen werden die Bildparameter zwar nicht angezeigt, sie werden jedoch wieder aktiv, sobald eine Bildansicht betreten wird.
  - Rechtfertigende Indikationen werden jetzt unabhängig der Stichwörter als eigener Punkt zur Verfügung gestellt.
- Bildansicht:
  - Für gleichartige wiederkehrende Filteranwendungen können jetzt alle angewendeten Filter über das Kontextmenü als Standardfilter gespeichert werden (Ansicht übergreifend). Bereits gespeicherte Standardfilter werden hierbei überschrieben. Die Anwendung der Standardfilter kann auch über ein Symbol in der Werkzeugleiste durchgeführt werden.
  - Für Anmerkungen können jetzt die Linienfarbe und –breite als Standardeinstellung gespeichert werden.
- Datensicherung:
  - Die Einstellungen zur Datensicherung können jetzt auch im Configurator vorgenommen werden.
  - Im Configurator wurde die Löschautomation hinzugefügt, die die Löschung von Datensicherungen an den angegebenen Speicherorten basierend auf den Kriterien Anzahl und Alter vornimmt.
  - Es werden jetzt automatische Datenbanksicherungen im Verzeichnis C:\ProgramData\<Programmname>\AutoBackups\<Verbindungsname> abgelegt. Die Anzahl ist hierbei beschränkt. Sicherungen werden gelöscht, wenn diese älter als 7 Tage sind, wobei jedoch mindestens 3 behalten werden.
- Multi-Praxen Unterstützung:
Server-Dienste können jetzt über den Konfigurator als „Remote Server“ miteinander verbunden werden. Näheres hierzu entnehmen Sie bitte dem Handbuch.
- Änderung der Lizenzierung:
Lizenzierungen basieren nicht länger auf konkreten Geräten, sondern auf den erworbenen Modulen. Geräte einer Modul-zugehörigen Kategorie (z.B. OPG) können hierdurch nach Belieben de-/aktiviert werden, ohne das hierzu die Lizenz geändert werden muss.
- Es wurde eine Abnahmeprüfung für Röntgengeräte implementiert.
- Eine Funktionalität zum Einspielen von Patches wurde implementiert.
- Es wurde ein Fehler behoben, durch den Screenshots in die DVT-Ansicht importiert werden konnten.
- Es wurde ein Fehler behoben, durch den die Navigation mit Pfeiltasten in der Patientenansicht nicht wie vorgesehen funktionierte.
- Weitere kleinere Fehler wurden behoben.

## Ältere Versionen
- [Versionen 10.2.100 bis 10.2.12x](UpdateNews-10.2.12x.md)
