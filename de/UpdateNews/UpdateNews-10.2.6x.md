# Update Hinweise zu byzz nxt (für Versionen 10.2.6x)

- [Neueste Änderungen](../README.md)

## 10.2.69
- Alle Hauptansichten außer Kleinröntgen erlauben jetzt das Verschieben von Vorschaubildern über den unteren Rand hinaus.
- Neu importierte oder aufgenommene Bilder werden beim Einfügen in die Ansicht speziell markiert, so dass diese jetzt besser zu identifizieren sind. Diese Markierung wird mit der ersten Selektionsänderung am jeweiligen Vorschaubild oder bei einem Ansichtswechsel wieder aufgehoben.
- MultiFrame Bilder werden jetzt unterstützt. Gleichzeitig wurde für diese und auch MultiSlice Bilder die Möglichkeit eingeführt über das Tool „Frame Viewer“ in einem mit der Maus verschiebbaren Bereich über die anderen Schichten zu scrollen.
- Das Neueinfügen von Bildern in Ansichten wurde überarbeitet.
- Es wird jetzt auch ein Hinweis angezeigt, wenn Dokumente und Modelldateien nicht gefunden werden können.
- Einige Fehler der Milchzahnansicht wurden behoben.
- Ein Exportfehler in byzz Constancy wurde behoben.
- Ein Anzeigefehler in den VDDS-Optionen wurde behoben.
- Ein kleinerer Fehler in den DVT-Optionen wurde behoben.

## 10.2.68
- Ein Fehler beim Speichern von Kleinröntgenaufnahmen (Drehung um 90°) wurde behoben.
- Bissflügel zeigen im Aufnahmemodus jetzt ihren Index in der Reihenfolge der Aufnahmen an.

## 10.2.67
- Control Center:
  - „Ansicht aktualisieren“ (F5) aktualisiert jetzt korrekt.
  - Ober- und Unterkiefer Platzierungen erscheinen jetzt in der richtigen Kachel.
- Ein Fehler der Trophy Implementierung wurde behoben.
- Morita wurde implementiert.
- Exportieren-Senden:
  - Ein Fehler in der Berechnung der Anzahl der zu verschickenden Dateien wurde behoben.
  - Verschicken an Partner erstellt jetzt immer eine zip-Datei.
- Die Patientenbildaufnahme in der Patientenmaske wurde wiederhergestellt. Mit Klick auf das Patientenbild, bzw. dessen Platzhalter wird die Aufnahme gestartet (Voraussetzung: In den Geräteeinstellungen-Video wurde bereits eine Kamera eingetragen).
- x-on nxt Treiber Dateien wurden neu signiert.
- Drucken aus der Bildansicht funktioniert jetzt wieder korrekt.
- Bei vielen Geräteeinstellungen wurde eine Option zum Verwenden der Bildausrichtung hinzugefügt.
- Brennvorgänge geben Statusmeldungen wieder korrekt aus.
- Gespeicherte Röntgenparameter werden jetzt bei Mehrfachaufnahmen korrekt gesetzt.
- Die erweiterte Suche sucht jetzt standardmäßig wieder als „Und“-Suche. Eine Option zum Abschalten wurde der Oberfläche hinzugefügt.
- Das Handbuch wurde aktualisiert.
- Die Hilfe wurde aktualisiert.

## 10.2.66
- Ein Absturz der erweiterten Suche bei Benutzung des Patientenkriteriums wurde behoben.
- Ein Fehler der im Zusammenhang mit einem Rechtsklick auf DVT Bildern auftrat wurde behoben.
- Das Kopieren von DVTs zu anderen Patienten kopiert jetzt auch nicht-Serien-Elemente korrekt.
- Ein Fehler bei der Datenübertragung im Zusammenhang mit Z1 wurde behoben.
- PayPerUse Einstellungen werden jetzt bei der Migration korrekt übernommen.
- pa-on Ansicht:
  - Die Konfiguration der Ansicht bietet unabhängig vom Hauptprogramm andere Sprachen als Auswahl an, jedoch zeigte eine Änderung nur bei den Sprachen Deutsch, Englisch und Englisch (USA) Wirkung. Dies wurde behoben (die Umstellung der Sprache zeigt nach wie vor jedoch keine Meldung und benötigt einen Neustart des Programms).
  - Ein Darstellungsfehler in verschiedenen Unteransichten wurde behoben.
- Dokumente können jetzt ebenfalls per VDDS übertragen werden.
- Die Hintergrund-Einstellungen der Historie arbeiten jetzt korrekt.
- Die Control Center-Einstellungen enthalten jetzt eine Option zur (De-)Aktivierung der exakten Bildzuweisung zu entsprechenden Zahn-Elementen.

## 10.2.65
- Das unmittelbare Einloggen nach einer Neuinstallation in den in der neuen Lizenz angelegten Benutzer konnte zu einem Absturz führen – dies wurde behoben (dieser Fehler betrifft nur die Versionen 10.2.62 und neuer).
- Das Fehlen der Standard Ausrichtung des Milchzahnes 75 wurde behoben.
- Ein Anzeigefehler in der PayPerUse Geräte-Lizenzierung wurde behoben.
- Die Anwendung des „Entsprenkeln“ Filters führt nicht mehr zu einem Absturz. Die Funktionsweise ist derzeitig jedoch für bestimmte Farbbilder noch fehlerhaft – dies wird zu einem späteren Zeitpunkt behoben.

## 10.2.64
- Ein Fehler beim Migrieren von Bildern, die den „Entsprenkeln“-Filter verwenden wurde behoben.
- Aufnahmen von Milchzähnen in den Quadranten 3 und 4 konnten einen Absturz verursachen. Dies wurde behoben.
- Ein Ansichten Fehler bei per VDDS übertragenen Patienten wurde behoben.
- Die Felder Anrede und Status in der Patientenansicht funktionieren wieder korrekt.

## 10.2.63
- Die Einheitenanzeige im Messfenster funktioniert jetzt korrekt.
- Ein Fehler beim Ändern der Hintergrund-Einstellungen der Ansichten wurde behoben.
- Vorschaubilder können unmittelbar nach dem Import wieder verschoben werden.

## 10.2.62
- Es wurde eine veraltete Kernkomponente gegen eine aktuelle ausgetauscht. Hierdurch ergeben sich u.a. auch einige optische Änderungen. Die Themes-Funktionalität wurde deswegen vorübergehend entfernt und wird zu einem späteren Zeitpunkt wieder hinzugefügt.
- Die Vorschaubildgrößen verhalten sich jetzt innerhalb einer Ansicht einheitlich und können über einen Regler in der Statusleiste am unteren Bildschirmrand in Echtzeit angepasst werden.
- Die Sichtbarkeit der folgenden Bereiche kann jetzt über das Ansichtmenü und die Buttons der Statusleiste geschalten werden: Menüleiste, Werkzeugleiste, Navigationsbe-reich auf der linken Seite.
- Exportdialog:
  - Größere Videodateien können jetzt gebrannt werden.
  - Die Option der Brenngeschwindigkeit wird jetzt automatisch (de-)aktiviert, je nachdem, ob sich ein Medium im Laufwerk befindet, eingelegt oder entfernt wird.
  - Der E-Mail Versand bietet jetzt die Option E-Mails als .zip Datei zu verschicken und diese mit einem Passwort zu versehen. Der Versand ist dabei standardmäßig auf 10 MB und maximal 10 Dateien pro Email limitiert. Dies kann über die Einstellungen im Reiter Export angepasst werden.
  - Es wurde eine weitere Option „Mit Cryptshare verschicken“ hinzugefügt.
  - Der Versand per E-Mail als auch mit Cryptshare bietet die Möglichkeit einen Partner auszuwählen, der über die Praxiseinstellungen (s.u.) definiert werden kann.
- Praxiseinstellungen:
  - Das Bearbeiten von Praxen und Benutzern entfernt nicht mehr die letzte Aus-wahl von Praxen und Benutzern.
  - Als Benutzer können jetzt auch Partner ausgewählt werden (und müssen auch wie jeder andere Benutzer erst Praxen zugewiesen werden). Partner werden im Exportdialog mit gewähltem E-Mail Versand als Zielpartner angeboten. Hierbei wird die in den Benutzer Einstellungen festgelegte E-Mail Adresse sowie das Passwort verwendet.
  - Das Bearbeiten von Praxen und Benutzern wurde in modale Dialoge ausgelagert.
- Setup:
  - Das Erscheinungsbild des Setups wurde überarbeitet.
  - Adobe Acrobat Reader kann jetzt am Ende des Setup-Vorgangs installiert werden, wenn dieser auf dem Zielsystem nicht gefunden wurde.
  - Die byzz Deinstallation bietet jetzt am Ende die Option zum Löschen aller Einstellungen. Dies betrifft jedoch nicht die mit byzz Maintenance gemachten Sicherungseinstellungen.
- Patientenmaske:
  - Der Darstellungsfehler des Kalenders wurde behoben.
  - Ein händisch eingegebenes Geburtsdatum kann jetzt nicht mehr weiter in der Vergangenheit als 01.01.1900 oder in der Zukunft liegen.
- Die Bildparameter können nur noch in bestimmten Ansichten angezeigt werden.
- Control Center:
  - Die Speicherung der Beschreibung der Kacheln wurde überarbeitet. Änderungen in der Logik benötigen jetzt kein Zurücksetzen der Oberfläche mehr.
  - In den Einstellungen wurde ebenfalls der Punkt Control Center eingeführt. Hier werden alle möglichen Kacheln aufgelistet sowie die Möglichkeit bereitgestellt, Prozess-Kacheln zu erzeugen, die einen bestimmten Prozess überwachen und dessen Hauptfenster anzeigen. Hierzu kann einfach per Drag and Drop eine .exe Datei auf die Oberfläche gezogen und fallen gelassen werden (das zugehörige Programm muss dazu jedoch bereits laufen!). Zum jetzigen Zeitpunkt wird nur die Neuerzeugung angeboten. Eine Änderung ist nicht möglich, man kann jedoch erzeugte Prozess Kacheln löschen und neu anlegen. Weitere Optionen werden im Laufe der Zeit hinzugefügt.
  - Die Dokumente-Kachel zeigt jetzt Elemente an. Handelt es sich um darstellbare Bilder, werden diese angezeigt. Nicht darstellbare Dokumente werden mit ei-nem Platzhaltersymbol angezeigt.
- Zahnschema:
  - Die Anzeige des Schemas für Kleinröntgenbilder wurde um Bissflügelbuttons erweitert.
  - Für Videobilder werden außerdem zusätzliche Auswahlbuttons für Quadranten, Kiefer sowie für En face und Smile angeboten.
  - Nachträgliche Zahnänderungen für Kleinröntgen und Kamera erfordern jetzt die Angabe eines Hauptzahnes (= Ortsbezeichnung). Dieser wird beim Setzen der Bissflügel-, Quadranten-, Kiefer-, Smile- und En face – Buttons automatisch gesetzt. Explizite Zahnzuweisungen erlauben beliebig viele Zähne und benötigen zusätzlich den Hauptzahn. Dieser wird hierbei mit Klick über die rechte Maustaste gesetzt.
- Um den Speicher etwas weniger zu belasten, werden die Vorschaubilder mit steigender Anzahl im Importdialog stufenweise in der Auflösung verringert.
- Die Serienübersicht erstellt jetzt beim ersten Aktivieren Vorschaubilder aller vorhandenen Serienansichten. Jedes weitere Aktivieren sollte danach deutlich schneller reagieren.
- Die Darstellungsoptionen für die Hintergründe der jeweiligen Ansichten wurden überarbeitet und funktionieren jetzt korrekt.
- Auf zweitem Bildschirm anzeigen („Duplikatfenster“):
  - Diese Funktionalität wurde überarbeitet und kann jetzt jedes geöffnete Bild abhängig von der Auswahl anzeigen. Außerdem kann der Katalog ebenfalls als Quellfenster verwendet werden.
  - Ist kein Bild geöffnet, wird die Hauptansicht angezeigt.
  - Wird die Maus auf dem Fenster an den oberen Bildschirmrand bewegt, erscheint ein Menü, das die folgenden Optionen anbietet:
  - Anzeigen einer Liste aller möglichen Quellfenster.
  - Vollbildmodus umschalten.
  - Fenster schließen.
  - Geöffnete Bilder können jetzt in der Werkzeugleiste mit einem weiteren Button „Auf zweitem Bildschirm anzeigen“ versehen werden (standardmäßig nicht gesetzt – muss erst über die Toolbareinstellung hinzugefügt werden). Mit Klick auf den Button wird das Duplikatfenster gestartet (sofern es nicht schon sichtbar ist) und das Bild angezeigt.
- Aufnahmeparameter werden jetzt pro Gerätetyp und Zahn gespeichert.
- Der Aufnahmebestätigungsdialog wurde überarbeitet und zeigt jetzt nicht nur die Bildparameter, sondern eine Liste aller gemachten Aufnahmen. Jede Aufnahme muss dabei zumindest einmal angeklickt worden sein, um die Aufnahme zu bestätigen. Ansonsten kann das Fenster nur mit X geschlossen werden (entspricht keiner Änderung).
- Bildvergleich:
  - Der Bildvergleich wird jetzt in einem extra Fenster angezeigt (bietet ansonsten jedoch noch keine weiteren Neuerungen – dies erfolgt zu einem späteren Zeitpunkt).
  - Es wurde zusätzlich eine weitere Variante des Vergleichs hinzugefügt. Im Vergleichsfenster können mehrere Bilder ausgewählt werden. Werden hierbei genau zwei Bilder ausgewählt, wird im Fenstermenü (erscheint, wenn sich die Maus im oberen Bereich des Fensters befindet) der Überlagerungsbutton aktiv. Mit Klick auf diesen wird der Überlagerungsmodus aktiviert, in welchem die Transparenz des oberen Bildes über einen Regler am rechten Bildschirmrand stufenlos angepasst werden kann. Zusätzlich kann auf der linken Seite jeweils ein Bild als aktiv ausgewählt werden. Das aktive Bild kann im Überlagerungsbereich des Fensters mit gedrückter linker Maustaste verschoben und mit dem Mausrad gezoomt werden. Ein Doppelklick mit linker Maustaste setzt die Verschiebung zurück. Ein Doppelklick mit rechter Maustaste setzt den Zoom zu-rück.
Mit einem Klick auf den Vergleichsbutton im Fenstermenü kann wieder zum Bildvergleich gewechselt werden.
- Die Optik einiger Dialoge wurde angepasst.
- Es wurde eine kontextsensitive Hilfe implementiert. Je nachdem welches Fenster, bzw. welches Eingabefeld oder Bereich einer Ansicht fokussiert ist (d.h. mit dem Mauszeiger angeklickt wurde), erscheint mit Tastendruck auf F1 der korrespondierende Hilfe-Eintrag der Hilfedatei.
- Nicht unterstützte Sprachen werden in den Einstellungen nicht mehr angezeigt.
- Die Patientenmaske wird jetzt korrekt aktualisiert, wenn kein Patient geöffnet war und ein anderer Benutzer angemeldet wird.
- Escape schließt ein Bildfenster nicht mehr, wenn dieses nicht im Vollbildmodus ist. Stattdessen wurde diese Funktion so angepasst, dass Fenster im Vollbild bzw. maximiert nun zurück in den Fenstermodus wechseln.
- Dokumentenansicht:
  - Dokumente können jetzt ebenfalls zu anderen Patienten kopiert und verschoben werden.
  - Analog wie im Control Center werden auch hier in der Kachelansicht entsprechend dem Dateityp Vorschaubilder angezeigt.
  - Die Kachelansicht erlaubt jetzt ebenfalls die Größeneinstellung über den Slider in der Statusbar am unteren Bildschirmrand.
- byzz Maintenance, byzz Migrator und byzz Constancy zeigen jetzt einen Button, von dem aus der TeamViewer direkt gestartet werden kann.
- byzz Constancy:
  - Der Ausdruck der Konstanzliste enthält jetzt alle Werte.
  - Nicht mehr aktive Röntgeneinrichtungen können jetzt ausgeblendet werden.
- Das Röntgenkontrollbuch enthält jetzt einen Button zum Filtern auf Elemente mit leeren Einträgen, d.h. wenn entweder die Spannung, der Strom oder die Belichtungszeit 0 ist.
- Die Bildparameter für den Import enthalten in der Datumsauswahl jetzt ein Element für das heutige Datum.
- Drag & Drop funktioniert jetzt für neuere Microsoft Word Versionen.
- DICOM Bilder ohne Signatur werden jetzt importiert( z.B. Morita Aufnahmen)
- Weitere kleine Fehlerbehebungen.