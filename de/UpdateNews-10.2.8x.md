# Update Hinweise zu byzz nxt (für Versionen 10.2.8x)

- [Neueste Änderungen](../README.md)

## 10.2.89
- Die Testbilderdarstellung innerhalb des Hauptfensters funktioniert wieder.
- Werden über den Dürr Scanner mehr Bilder geliefert als ursprünglich angefordert, werden diese nicht mehr verworfen, sondern mit den Einstellungen des letzten Bildes gespeichert.
- dentaleyepad wird jetzt unterstützt. Es kann jetzt innerhalb einer Serienansicht als Gerät ausgewählt und zur Live-Aufnahme verwendet werden. Weiterhin wurde ein Importdialog bereitgestellt, der den Import auch außerhalb der Serienaufnahme erlaubt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.88
- Die neue Funktionalität dentflow wurde eingefügt. Dieser geführte Workflow ermöglicht den verschlüsselten online-Datenaustausch von Modell- und Freecordervermessungsdaten zwischen Kunden und einem Labor.
- Röntgenkontrollbuch:
  - Die Spalte Ort zeigt wieder die Bezeichnungen DVT, OPG, Fernröntgen und Bissflügel an.
  - Patientenbilder einer anderen Praxis werden nicht mehr angezeigt.
- VDDS: Ein Fehler wurde behoben, bei dem jedes Mal eine Warnmeldung erschien, wenn der Behandler nicht mit übertragen wurde.
- Höhe und Breite von Kamerabildern werden jetzt in den Eigenschaften angezeigt.
- Die absolute Größe von Bildern (jedoch nicht bei DVTs) kann jetzt über das Systemmenü (über das Icon der linken oberen Ecke) des geöffneten Bildfensters zurückgesetzt werden.
- Bilder aus dem alten byzz können nach der Migration wieder an die PVS übertragen werden.
- Die Suche nach Dokumenten brachte trotz vorhandener Dokumente kein Ergebnis – dies wurde behoben.
- Weitere kleinere Fehler wurden behoben.

## 10.2.87
- Zwei Fehler beim Verwenden von Großbuchstaben in Datenbanknamen wurden behoben.
- Ein neues Gerät (PaX-i Plus) wurde hinzugefügt.
- Das neu hinzugefügte TransCrypt Modul bietet die Möglichkeit zum verschlüsselten Datenaustausch. Für diesen Vorgang wird eine Registrierung bei www.securesend.de benötigt. Beachten Sie bitte außerdem, dass Sie hierfür auch Ihre byzz nxt Lizenz aktualisieren müssen, um diese Funktionalität freizuschalten.
- Export-Brennen: Nach dem Erstellen einer ISO Datei konnten keine weiteren mehr erstellt werden – dies wurde behoben.
- Weitere kleinere Fehler wurden behoben.

## 10.2.86
- Fernwartung: Es wird jetzt eine englischsprachige Variante von TeamViewer mitgeliefert, die bei anderen Spracheinstellungen als deutsch gestartet wird.
- Weitere kleinere Fehler wurden behoben.

## 10.2.85
- VDDS: Das Geburtsdatum übergebener Patienten wird jetzt geprüft. Liegt das Datum vor dem 01.01.1900 oder in der Zukunft wird eine Meldung ausgegeben, die Daten zuerst zu korrigieren.
- Konstanzaufnahmen erscheinen jetzt nicht mehr im Röntgenkontrollbuch.
- Ein Fehler beim Erstellen von .iso Dateien wurde behoben.
- Annotationen: Es wurden Optimierungen bei der Darstellung von Pfeilspitzen und Schriften vorgenommen.
- Es wurden mehrere kleine Fehler im Zusammenhang mit Aufnahmen über die c-on nxt Kamera behoben.
- Ein Fehler bezüglich der Belichtungszeit wurde behoben.
- Ein Fehler während der Migration bezüglich der Anzahl von PayPerUse Aufnahmen wurde behoben.
- Erinnerung zur Konstanzprüfung:
  - Inaktive Röntgeneinrichtungen werden jetzt nicht mehr beachtet.
  - In manchen Fällen wurde ein falsches Datum angezeigt – dies wurde behoben.
- Optionen:
  - Praxisverwaltung:
  - Angemeldete Benutzer können ihre Benutzergruppe jetzt nicht mehr ändern.
  - Es stehen jetzt Felder für die Adress- und Kontaktdateneingabe von Praxen zur Verfügung.
  - Allgemein:
  - Es wurde ein Schalter eingebaut, der in der Patientenansicht einen Button zur Erstellung und Anzeige eines QR-Codes für die wichtigsten Patientendaten bereitstellt.
  - Es wurde ein Schalter eingebaut, der das Verstecken von Patientenna-men in den Hauptfenstern ermöglicht.
  - Buttons der pa-on Ansicht können jetzt ausgeblendet werden (auch wenn nicht mehr sichtbar, bleibt die 01-Ansicht derzeit die Standardansicht).
- Ein Fehler verursachte eine zusätzliche Speicherung von Dokumenten in der Datenbank – dies wurde behoben.
- byzz Maintenance: Ein Fehler beim Wiederherstellen von Datenbanken deren Name Großbuchstaben enthielt wurde behoben.
- Suche:
  - Suchvorgänge erfordern jetzt immer mindestens ein Kriterium.
  - Werden mehr als 250 Bilder gefunden, werden nur die ersten 250 Ergebnisse angezeigt.
  - Suchvorgänge beziehen jetzt nicht mehr Ergebnisse aus Katalogen mit ein.
- Weitere kleine Fehler wurden behoben.

## 10.2.83
- Bildüberlagerung: Zusätzlich zur Möglichkeit per Doppelklick (links – Position; rechts – Skalierung) die Transformation zurückzusetzen, wurde ein Zurücksetzen-Button eingefügt.
- Ein Fehler wurde behoben, der beim Öffnen mehrerer Bilder gleichzeitig einige der Bilder in falscher Größe anzeigte.
byzz Constancy: Ein Fehler beim Ändern von Helligkeit und Kontrast wurde behoben.
- Aufnahmeparameter: Nach Eingabe eines Wertes öffnet sich das Eingabefenster des nächsten Parameters (dies gilt nicht für das DAP).
- Aufnahmebestätigungsfenster: Ein Tooltip erscheint jetzt, wenn sich der Mauszeiger über dem OK-Button befindet und dieser deaktiviert ist.
- Ein Fehler wurde behoben, der aus dem alten byzz migrierte Bilder verzerrt darstellte.
- Weitere kleinere Fehler wurden behoben.

##  10.2.82
- VDDS: Gleiche Patienten aus verschiedenen Praxen können jetzt übergeben werden.
- InfoDots können jetzt auch ohne Zahnbezug angelegt werden.
- Mehrere kleinere Fehler wurden behoben.

## 10.2.81
- Dokumente:
  - Ein Fehler beim Verschieben von Verzeichnissen wurde behoben.
  - Das Kontextmenü über die rechte Maustaste wird jetzt auch in der Kachelansicht angezeigt.
  - Umbenennen funktioniert jetzt auch in der Kachelansicht.
  - Aus Sicherheitsgründen kann das Anlegen, Umbenennen, Löschen und Verschieben von Ordnern nur noch von einem Administrator vorgenommen werden.
  - Die Dokumentenansichten unterstützen jetzt Mehrfachauswahl. Jedoch steht derzeit noch kein Auswahlrahmen zur Verfügung und wird in einer der nächsten Versionen bereitgestellt. Vorläufig können mehrere Elemente an- oder abgewählt werden, indem die Strg-Taste beim Linksklick verwendet wird.
  - Über Geräteeinstellungen-Dokumente-Twain stehen jetzt Optionen zur PDF Erstellung zur Verfügung, so dass bereits beim Einscannen einzelner oder mehrerer Bilder PDF-Dokumente erstellt werden können.
  - Sofern es sich ausschließlich um Bilder und PDF Dokumente handelt, können alle aktuell ausgewählten Elemente nach Eingabe eines Namens für die PDF Datei zu einem PDF Dokument zusammengefasst werden. Die Reihenfolge der Seiten entspricht hierbei der Reihenfolge der Auswahl der Dokumente. Das neue PDF Dokument wird unter folgenden Gesichtspunkten erstellt:
  - Ein Bild entspricht einer Seite.
  - Die Seitengröße und –Ausrichtung entspricht der des Bildes.
  - PDF Dokumente werden entsprechend der Auswahlreihenfolge einge-fügt.
  - Drag & Drop zu externen Anwendungen funktioniert jetzt wie vorgesehen.
- Export-Per Email verschicken: Als Passwort kann jetzt auch der Nachname des Patienten verwendet werden.
- Optionen-Kleinröntgen: Röntgenparameter für Einrichtungen können jetzt voreingestellt werden.
- Weitere kleine Fehler wurden behoben.

## 10.2.80
- Zahnauswahl mit Hilfe des Zahnschemas: Da sich für eine nicht unerhebliche Anzahl an Personen die korrekte Benutzung der Zahnauswahl nicht vollständig erschloss, wurde diese folgendermaßen angepasst:
  - Zahngruppen (Bissflügel, Quadranten, etc.) stehen weiterhin für sich alleine, d.h. diese können keine Nebenzähne haben oder selbst als Nebenzähne fungieren.
  - Die Zahnauswahl per Drag and Drop (aufziehen eines Rechtecks) über die Zähne wurde beibehalten. Dabei wird wie bisher versucht, den Hauptzahn (mit Orange markiert) über den Mittelpunkt des Rechtecks zu ermitteln.
  - Ein Linksklick auf einen bereits markierten Nebenzahn macht diesen zum Hauptzahn und den bisher markierten Hauptzahn zu einem Nebenzahn.
  - Ein Linksklick auf einen nicht markierten Zahn entfernt jedwede bisherige Markierungen und setzt den angeklickten Zahn als Hauptzahn.
  - Ein Rechtsklick auf einen markierten Nebenzahn hebt die Markierung des Nebenzahnes auf.
  - Ein Rechtsklick auf einen nicht markierten Zahn setzt die Markierung als Nebenzahn.
- Änderungen hinsichtlich der kommenden DSGVO:
Da Administratoren jegliche Rechte haben, können ab sofort Benutzer der Benutzergruppe Administrator nicht mehr für den Standard Login verwendet werden. Ist dies der Fall, gilt folgendes:
  - Normaler Start: Der Standard Login wird zurückgesetzt und das Login Fenster erscheint.
  - Start über VDDS: Der Benutzer wird auf die Benutzergruppe Arzt heruntergestuft und das Programm startet normal. Handelt es sich hierbei um den Administrator (was normalerweise nie der Fall sein sollte), muss der Benutzer in der PVS angepasst werden, ansonsten wird das Fenster jedes Mal erscheinen und im Anschluss das Login Fenster angezeigt.
In allen Fällen wird zusätzlich ein Hinweis angezeigt.
- Einstellungen:
  - Admin: Die Option „Kleinröntgenaufnahmen benötigen Aufnahmeparameter“ wurde hinzugefügt. Ist diese aktiviert, müssen nach der Aufnahme im Aufnahmebestätigungsfenster die Werte Spannung, Strom, Belichtungszeit sowie die Röntgeneinrichtung gesetzt sein, anderenfalls kann das Fenster nicht geschlos-sen werden (ein entsprechender Hinweis wird angezeigt, wenn versucht wird, das Fenster mit X zu schließen).
  - Export: Dateinamen können jetzt angepasst werden. Eine genaue Beschreibung der zur Verfügung stehenden Optionen finden Sie ebenfalls hier.
  - Allgemein: Logdateien können jetzt über den Button „Log Dateien exportieren“ als Zip-Datei exportiert werden.
  - Kamera - Live Import: Die Option „Nicht importierte Bilder nach Importvorgang löschen“ wurde hinzugefügt. Ist diese aktiviert werden nach dem Importvorgang alle angezeigten Elemente des Import-Fensters gelöscht, sofern diese nicht für den Import markiert wurden.
- FrameViewer: Wird während der Benutzung des FrameViewer-Tools die rechte Maustaste gedrückt, wird ein Auswahldialog angezeigt, der Optionen zum Speichern des gesamten Bildes inklusive der sichtbaren FrameViewer Elemente, oder lediglich des In-halts des FrameViewers anbietet.
- Wurde byzz nxt während einer Serienbearbeitung geschlossen, kam es zu einem Absturz – dies wurde behoben.
- byzz Maintenance:
  - Die Wiederherstellung verwendet jetzt die aktuellen Standard-Verbindungseinstellungen und nicht mehr generell den Namen „byzz“ als Da-tenbank.
  - Zwei Fehler, die automatische Inkrementelle und vollständige Backups verhinderten wurden behoben.
- Die innerhalb von byzz nxt vorgenommenen Druckereinstellungen überschreiben jetzt nicht mehr die Windows-Druckereinstellungen des aktuellen Benutzers.
- Die Länderauswahl in der Patientenmaske zeigt die Länder jetzt korrekt an.
- 3D Datensätze werden jetzt korrekt von Ez3D-i geöffnet.
- Annotationen:
  - Annotationen bei gespiegelten OPGs werden jetzt korrekt in der Bildvorschau angezeigt.
  - Unter bestimmten Umständen arbeitete die Skalierung von Schriften nicht wie vorgesehen – dies wurde behoben.
- Patientenauswahl: Ein selten auftretender Fehler beim gleichzeitigen Doppelklicken der Maus und Drücken der Steuerungstaste wurde behoben.
- Werden Vorschaubilder nicht durch Aufziehen eines Rahmens sondern einzeln nachei-nander markiert, wird jetzt bei Aktivierung des Bildvergleichs die Reihenfolge der Bilder beachtet.
- Bildparameter: Die Uhrzeit kann jetzt ebenfalls angepasst werden.
- Modelldaten: Wurden keinerlei Änderungen vorgenommen, wird das Vorschaubild nicht mehr neu erzeugt.
- Röntgenkontrollbuch: Die Option OPG/Fernröntgen wurde separiert in zwei einzelne Optionen.
- Die Möglichkeiten zum Im- und Export des Katalogs wurden hinzugefügt.
- Die Vorschaubildinformation zeigt jetzt bei DVT Aufnahmen unter FoV nicht mehr die Bild- sondern die Volumengröße an.
- Das „Relative Dichte“ Werkzeug arbeitet jetzt auch bei gedrehten Bildern korrekt.
- Das Kontextmenu der Bildbearbeitung wurde neu arrangiert und bietet jetzt ebenfalls die Möglichkeit die Arbeitsposition zu speichern.
- Weitere kleine Fehler wurden behoben.

## Ältere Versionen
- [Versionen 10.2.7x](UpdateNews-10.2.7x.md)