# Update Hinweise zu byzz nxt (für Versionen 10.2.7x)

- [Neueste Änderungen](../README.md)

## 10.2.78
- Eine neue Variante zum Anpassen der Programmoptik wurde implementiert. Hieraus ergibt sich ein einheitliches neues Design. Die Möglichkeit zur Anpassung durch den Benutzer wird zu einem späteren Zeitpunkt zur Verfügung gestellt.
- Die automatische Drehung bei Scannern ist jetzt standardmäßig ausgeschaltet.
- Mit der Log-Stufe „Ausführlich“ werden jetzt VDDS Log-Ausgaben detaillierter wieder-gegeben.
- VDDS: Es wurde die Option „Nur Indikationszahn über VDDS senden“ hinzugefügt.
- Annotationen:
  - Messwerte werden jetzt sofort aktualisiert, wenn die absolute Größe geändert wird.
  - Messstrecken werden jetzt hervorgehoben, wenn sich der Mauszeiger über einem bestimmten Streckenabschnitt in der Streckenabschnittsliste befindet.
  - InfoDots haben jetzt immer die korrekte Farbe.
  - Das Tool „Freie Drehung“ kann jetzt wieder aktiviert werden.
  - Das Tool „Relative Dichte“ kann jetzt wieder aktiviert werden.

## 10.2.77
- Zwei Fehler bezüglich des Stoppens und Abbrechens von Aufnahmen mit x-on nxt Sensoren wurde behoben.
- Control Center:
  - Die Vorschaubilder zeigen jetzt auch Annotationen.
  - Änderungen werden jetzt nach dem Schließen der Bildansicht sofort dargestellt.
- Mehrere kleine Probleme im Zusammenhang mit Annotationen und Schriften wurden behoben.
- Bilder können jetzt auf Wunsch ebenfalls mit Annotationen ausgedruckt werden.
- Ein Fokusproblem beim Schließen der Bildansicht wurde behoben.
- Ein VDDS-Login Problem im Zusammenhang mit einem neuen Behandler wurde behoben.

## 10.2.76
- Weitere kleine Fehler bezüglich Morita Geräten wurden behoben.
- In sehr seltenen Fällen, in denen auf einem Server bereits eine Zwischenversion von Postgres installiert war, wurde die Postgres Installation nicht korrekt erkannt – dies wurde behoben.
- byzz Maintenance: Sicherungsaufgaben können jetzt wieder erstellt werden.
- Das FrameViewer Tool enthält jetzt eine schematische Visualisierung (Fortschrittsbalken) der Bukkal-Lingual Position des aktuell sichtbaren Bildes.
- Ein Aktualisierungsproblem mit Thumbnails von neu aufgenommen Bilder wurde behoben.

## 10.2.75
- LiveVideo Vorschaubilder werden im Control Center wieder korrekt angezeigt.
- Bild-Ansicht und Annotationen:
  - Ein Fehler im Zusammenhang mit einer leeren Implantat Liste wurde behoben.
  - Annotations-Buttons werden jetzt deaktiviert, wenn die Annotations Anzeige ausgeschaltet wird.
  - Bilder werden jetzt nicht mehr mit gehaltener linker Maustaste verschoben – es muss jetzt zusätzlich die Steuerungstaste gehalten werden.
  - Mit gedrückter linker Maustaste wird jetzt eine Lasso-Funktion aktiviert, mit der mehrere Annotationen ausgewählt werden können. Hiermit ausgewählte Annotationen können nur gelöscht werden. Zum Aktivieren muss weiterhin jede Annotation einzeln angeklickt werden.
  - Es kann jetzt nicht mehr über die maximale Bildgröße hinaus rausgezoomt werden. Derzeitig gibt es hier noch ein paar Unschönheiten im Zusammenhang mit Änderungen der Fenstergröße. Falls das Bild aus dem Zoombereich verschwin-det oder anderweitige Probleme auftreten, kann das Bild über den Zoommonitor und dem dortigen „Home“-Button (dicker Pfeil nach oben) wieder in den sichtbaren Bereich geholt werden.
- Die FrameViewer Funktion wurde überarbeitet.
- Geräteeinstellungen-Kamera-Video: Die Einstellungen werden jetzt beim Betreten der jeweiligen Kameraansicht korrekt aktualisiert.
- In der Kameraansicht wird jetzt gespeichert, welche Kamera zuletzt verwendet wurde.
- Das automatische Ausloggen wird nur noch initiiert, wenn ausschließlich das Haupt-fenster und keine weiteren Fenster geöffnet sind.
- PayPerUse: Es wurden weiterhin Warnmeldungen mehr ausgegeben, wenn der Unlimited Status erreicht wurde – dies wurde behoben.
- Kopiervorgänge (von Bilddaten) über Steuerung-C aus Fremdprogrammen und Einfügen ins byzz zeigte leere Vorschaubilder an – dies wurde behoben.
- Um den Vorgang zu verdeutlichen erscheint die Hinweismeldung beim Öffnen von Patienten auf einem farblich abgesetzten Hintergrund.
- Veraltete Setup-Dateien die möglicherweise im Server-byzzSetup Ordner verblieben sind, führen nicht mehr zu einem Zustand, in dem byzz nicht mehr gestartet werden kann.
- Die Anzeige und Speicherung des Pfades zur VCapture Software funktioniert jetzt richtig.
- Drag & Drop in den Katalog funktioniert jetzt wieder korrekt.
- Der VDDS-Import kann jetzt bei geladenem Patienten aus jeder Ansicht heraus gestartet werden.
- Ein Fehler im Zusammenhang mit Morita-Geräten wurde behoben.
- Weitere kleinere Fehler wurden behoben.

## 10.2.74
- Es wurden leichte Performanceoptimierungen in den Bildansichten und im Control Center vorgenommen.
- Einige Controls wurden überarbeitet.
- Mit als Bildtyp Fernröntgen markierte Bilder werden jetzt bei der Migration korrekt übernommen.
- Das Laden von Bildern ist jetzt vorerst auf eine Bildgröße von maximal 32 Megapixeln beschränkt (entspricht maximalen Auflösungen von z.B. 7000 * 4793 oder 6000 * 5592). Beim Versuch größere Bilder zu importieren, wird ein entsprechender Hinweis angezeigt.
- Benutzer können sich jetzt von byzz nxt ausloggen (Datei → Ausloggen). Zusätzlich wurde in den Admin Einstellungen die Möglichkeit hinzugefügt, dass byzz nxt bei länge-rer Untätigkeit den aktuellen Benutzer automatisch ausloggt (nach einer bis max. 720 Minuten).
- Es wurde ein Informationssystem eingebaut, dass in der Statusleiste Meldungen von byzz nxt einsehbar macht (erscheint als „i“ in der Statusleiste). Es wird hierbei in permanente und löschbare Meldungen unterschieden, wobei die Anzahl der löschbaren Meldungen auf 10 beschränkt ist. Derzeit gibt es nur eine permanente Meldung, wenn in einer Ansicht versteckte Bilder existieren. Löschbare Meldungen sind Beispielsweise Informationen, dass Bilder kopiert, verschoben, gelöscht oder importiert wurden. Diese Meldungen sind derzeit sehr einfach gehalten und werden zu einem späteren Zeitpunkt präzisiert.
- Es wurden Abnahme Protokolle für Vatech Geräte hinzugefügt. Diese sind aus byzz nxt heraus aufrufbar (Hilfe → Protokolle → Abnahme xxx).
- Der Start des Scanvorgangs aus der Dokumentenansicht funktioniert jetzt wieder korrekt.
- Die Übernahme der Lizenzen bei Migrationsstart funktioniert jetzt wieder korrekt.
- Implantatgrößen können jetzt mit der Maus verändert werden.
- Ist beim Import die externe Speicherung aktiviert, wird jetzt überprüft, ob der Speicherpfad korrekt gesetzt ist.
- Neue DVTs werden in der Ansicht nicht mehr hinter bereits vorhandenen platziert.
- Die Sortierung der Patientenliste wird jetzt korrekt gespeichert.
- Brennen in byzz nxt 3D führte in einigen Fällen zu einem Absturz, wenn die Option „Auswerfen nach dem Brennen“ aktiviert war – dies wurde behoben.
- Ein Fehler beim Aktivieren des Scanvorgangs in der Dokumentenansicht wurde behoben.
- Es wird jetzt eine Option zum Drehen von x-on Scan Aufnahmen angeboten.
- Schrift- und Liniengrößen von Messungen werden jetzt richtig skaliert.
- byzz Constancy: Aufnahmeparameter werden jetzt auch für Konstanzaufnahmen angezeigt.
- Alle Zähne inklusive Bissflügel (nicht nur der Hauptzahn) werden jetzt per VDDS übergeben.
- Die Datenpfade für neue Vatech Geräte wurden aktualisiert.

## 10.2.73
- Der Druckvorgang für die Patientenstatistik wurde überarbeitet.
- Der Ausdruck des Röntgenkontrollbuches enthält jetzt nicht mehr die Spalten Testblock, behandelnder Arzt und beauftragender Arzt.
- Die Anzeige der Nachkommastellen in den Aufnahmeparametern wurde überarbeitet.
- MultiFrame Bilder haben jetzt dasselbe Icon Overlay wie MultiFile Bilder.
- Die x-on Scan Treiber wurden aktualisiert.
- In den Geräteeinstellungen wurde vielen Geräten die Option zur Durchführung der Konstanzprüfung hinzugefügt.

## 10.2.72
- Der Druckvorgang für das Röntgenkontrollbuch und die Patientenliste wurde überarbeitet.
- MultiFrame Bilder beginnen über den FrameViewer jetzt mit einem Bild aus der Mitte der Bildserie.
- Es wurde eine konfigurierbare Erinnerungsfunktion für die Konstanzprüfung eingebaut.
- Weitere kleinere Fehler wurden behoben.

## 10.2.71
- VDDS:
  - Ein Fehler bei der Patientenübergabe wurde behoben.
  - Der Absturz bei der Bildübergabe, wenn ein Bild nicht vorhanden ist, wurde behoben.
- Der Kaufdatumstext im PayPerUse Protokoll wurde korrigiert.

## 10.2.70
- MultiFrame Bilder können jetzt aufgenommen und importiert werden.
- Ein Fehler bei der Anzeige und Bearbeitung der Notizen wurde behoben.

## Ältere Versionen
- [Versionen 10.2.6x](UpdateNews-10.2.6x.md)