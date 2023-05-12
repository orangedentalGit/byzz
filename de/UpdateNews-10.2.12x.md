# Update Hinweise zu byzz nxt (für Versionen 10.2.100 bis 10.2.12x)

- [Neueste Änderungen](../README.md)

## 10.2.121
- Ein gelegentlich auftretender Fehler beim Laden der Einstellungen wurde behoben.
- Die DICOMDIR Migration bietet jetzt Optionen zum Spiegeln von Kleinröntgen- und Kamerabildern sowie zum Eintragen ins Röntgenkontrollbuch an.

## 10.2.120
- Das Gerät Green X wird jetzt unterstützt.
- Es wurden Vorbereitungen getroffen, um Einstellungen der Server Service Anmeldung für zukünftige Versionen zu übernehmen.

## 10.2.119
- Geräteeinstellungen: Kameraschalter können jetzt Tastatur-Tasten emulieren.
- Es wurde ein Programm (byzz.Clinic.Migrator) zum Migrieren von SQL Server Daten hin-zugefügt.
- Migrator: Die Migration kann jetzt auch über DICOMDIR ausgeführt werden.
- Ein Fehler in der patientenübergreifenden Suche wurde behoben.
- Ein Fehler wurde behoben, durch den in der Historie manche Bilder nicht ermittelt werden konnten.
- Linienbreiten in Bildern können jetzt als Standard gespeichert werden.
- ibyzzFTP: Der Bildexport wurde optimiert.
- Externe Programme: Es kann jetzt ein Zielordner angegeben werden, in den die Dateien vor dem Programmaufruf exportiert werden.
- Weitere kleinere Fehler wurden behoben.

## 10.2.118
- Ein Fehler beim Schreiben des DICOM-Headers der mittleren Schicht von DVT Serien wurde behoben.
- Ein Fehler beim Warten auf neue Bilder über VDDS wurde behoben.
- Model- und Video-Dateien verwenden jetzt beim Import den Dateinamen ohne Erweiterung als Titel.
- Die Slida Anbindung funktioniert jetzt wieder korrekt.
- Das STL Export Fenster wurde überarbeitet.
- Weitere kleinere Fehler wurden behoben.

## 10.2.117
- Serien: Verschieben von Elementen einer Serie, lässt diese nach erneutem Laden der Ansicht nicht länger verschwinden.
- Änderungen der VDDS_MMI.ini beachten jetzt die Kodierung korrekt.
- Die DenOptix Scanner-Anbindung funktioniert jetzt korrekt.
- Ein kleinerer Fehler in der Sirona Sivision Kamera Anbindung wurde behoben.
- Weitere kleinere Fehler wurden behoben.

## 10.2.116
- Monatliche Datensicherungen für Monate, die einen Tag ausgewählt haben, der außerhalb der Anzahl der Tage des Monats liegt, werden jetzt korrekt ausgeführt.
- Geöffnete Bilder in der Serienansicht führen nach dem Schließen nicht länger zu einer falschen Darstellung.
- Ein Fehler wurde behoben, durch den in bestimmten Fällen VDDS_MMI.ini Einträge nicht korrekt geschrieben wurden.
- Weitere kleinere Fehler wurden behoben.

## 10.2.115
- Nach dem Löschen von eigenen Ansichten die an oberster Stelle stehen, wurde die Ansicht nicht aktualisiert – dies wurde behoben.
- Die Funktion „Zweites Fenster“ kann jetzt auch aus der Bildansicht heraus bei erneutem Drücken des entsprechenden Buttons geschlossen werden.
- Scannen im Dokumente-Modul ist wieder möglich.
- Ein Fehler bei der VDDS Übertragung von Patienten deren Nummern in der PVS und byzz nxt unterschiedlich sind wurde behoben.

## 10.2.114
- Namen von Röntgeneinrichtungen akzeptieren jetzt keine ungültigen Zeichen mehr (hierzu gehören u.A.: / \ : * ? „ < > |).
- Export: Die Bild-Option „Alle Schichten“ arbeitet wieder wie vorgesehen.
- Zu einer Praxis neu hinzugefügte Ärzte werden jetzt ohne Neustart der Anwendung sofort im Dropdownmenü des Aufnahmeauftrages angezeigt.
- Die Suche über Patientenlisten, für deren Patienten noch keine Bilder erstellt wurden, führte zu langen Suchvorgängen – dies wurde behoben.
- Clients werden jetzt korrekt beendet, wenn der Serverdienst angehalten wird.
- byzz Setup: Bei angegebenem Hilfe-Kommandozeilenschalter wird das Setup jetzt korrekt beendet, wenn das Hilfefenster geschlossen wird.
- byzz Migrator:
  - Schlüsselwörter werden jetzt wieder korrekt übernommen.
  - Der Behandler wird jetzt korrekt als ausführender Arzt übernommen.
- byzz Constancy: Röntgenparameter der Uraufnahme werden jetzt korrekt übernom-men.

## 10.2.113
- byzz Maintenance zeigt beim Schließen keine Fehlermeldung mehr an.
- Die Röntgenkontrollbuch-Druckausgabe wurde optimiert.
- Bildexporte zeigen jetzt auch Titel der Patienten an, wenn diese angegeben wurden.
- byzz Constancy:
  - Die Konstanzliste kann wieder gedruckt werden.
  - Das Löschen von Röntgeneinrichtungen führt nicht länger zu einem Absturz.
- Weitere kleinere Fehler wurden behoben.

## 10.2.112
- Neuere MS SQL Services werden jetzt korrekt erkannt.
- Ein Fehler der Zeitbereichssuche (z.B. in der Patientenstatistik) wurde behoben.
- Weitere kleinere Fehler wurden behoben.

# 10.2.111
- Integration von Klinikfunktionalitäten:
  - Praxisverwaltung: Im Zuge der Anpassungen zur Verwendung des Softwaresys-tems in Kliniken wurde die Verwaltung entsprechend erweitert. Die ursprüngli-che Hierarchie Praxis → Benutzer wurde durch die Hierarchie Praxis → Abtei-lung → Benutzergruppe → Benutzer ersetzt. Weitere Informationen hierzu entnehmen Sie bitte dem Handbuch.
  - Unterstützung von PACS/RIS: Über den Server Konfigurator können jetzt entsprechende Einstellungen vorgenommen werden.
  - Bei Verwendung von RIS werden die Aufnahmeaufträge durch RIS Aufträge ersetzt.
- Externe Bildverwaltung: Im Zuge der Implementierung der Klinikfunktionalitäten können jetzt über Fremdsoftware aufgenommene Bilder gesondert behandelt und dargestellt werden. Weitere Informationen hierzu entnehmen Sie bitte dem Handbuch.
- Bei Export mit explizit gesetzter DICOM Option kann jetzt zusätzlich die Speicherung als DICOM-Dir ausgewählt werden.
- Patientendaten können jetzt über Datei → Zeige Patientenstammdaten angezeigt wer-den.
- Im Login-Dialog kann die Benutzerliste über ein Suchfeld gefiltert werden.
- Die Anzahl der Patienten in der Schnellauswahl kann jetzt unter Optionen → Allgemein → Sonstiges eingestellt werden.
- Die Patientenliste kann jetzt über Datumsbereiche so gefiltert werden, dass nur Patienten erscheinen, deren letztes Bild innerhalb des angegeben Zeitraums erstellt wurde.
- Die Einzelauswahl der Bilder in den Bildansichten funktioniert jetzt auch mit gedrückter Umschalten/Shift Taste und Links-Klick (vorher nur mit Strg/Ctrl).
- Das Röntgenkontrollbuch wurde überarbeitet. Die Spalten Quelle, Sensor und Testblock wurden entfernt und durch die Spalte Einrichtung ersetzt. Ebenso wurden die Spalten Behandelnder Arzt und Beauftragender Arzt entfernt und durch die Spalte Ausführen-der Arzt ersetzt. Hinzugekommen ist die Spalte Rechtfertigende Indikation.
- Setup: Um Client-Installationen mit vielen Stationen zu vereinfachen, kann das Setup jetzt mit Kommandozeilenschaltern versehen werden (anstatt – geht auch /):
  - -help oder -?
Die Hilfe anzeigen.
  - -q[uiet]
Installation im Hintergrund. Nur gültig für eine reine Client- oder Upgrade-Installation. Wird ignoriert, wenn eine Server Installation durchgeführt wird.
  - -i[nstallpath]
Der Installationspfad (Standard: C:\Program Files (x86)\byzz nxt).
- Die Modelldatenanzeige führt jetzt nicht mehr zum Absturz des Programmes, wenn das Programm über eine Remotedesktopverbindung verwendet wird.
- TransCrypt: Ein Fehler beim Empfang von OPG- und DVT-Daten wurde behoben.
- Bildanzeige: Die Darstellung der Werkzeugleiste kann jetzt über Ansicht → Toolbars → Werkzeugleiste der Bildansicht oder das Systemmenü der Bildansicht (das Icon links oben) aus-/eingeblendet werden. Diese Einstellung ist nicht Ansicht spezifisch und gilt für alle Ansichten.
- Vorschaubilder werden jetzt wie die Bilddaten in einem Unterverzeichnis innerhalb des jeweiligen Patientenverzeichnisses gespeichert. Hierdurch ergibt sich eine drastische Reduzierung der Datenbankgröße, so dass Sicherungen kleiner sind und schneller ange-legt werden.
- Das Neuanlegen und die Anzeige der Vorschaubilder der jeweiligen Ansichten wurde optimiert.
- Tastenkürzel: Um den in Windows-Umgebungen üblichen Tastenkürzel mehr zu ent-sprechend wurden die Tastenkürzel Fernröntgen (F10) und DVT (F11) entfernt und sind jetzt über Strg + F10 bzw. Strg + F11 zu erreichen.
Geändert wurden außerdem:
Historie – war F8, jetzt Strg + F8.
Suche – war F9, jetzt Strg + F9.
Die Taste F11 wird jetzt ähnlich den meisten Browsern für den Wechsel zwischen Fens-ter und Vollbildansicht mit Entfernung der Titelleiste verwendet.
- Weitere kleinere Fehler wurden behoben.

## 10.2.104
- SIUCOM wird jetzt korrekt unterstützt.
- Fehlerhafte .bmp Bitmapdateien führen nicht länger zu einem Fehler im Programm.
- Ein Fehler der SLIDA Schnittstelle wurde behoben.
- Ein Fehler der TWAIN Schnittstelle bezüglich Videoaufnahmen wurde behoben.
- Weitere kleinere Fehler wurden behoben.

## 10.2.103
- Die VDDS_MMI.ini wird wieder korrekt aktualisiert.
- Befundübergaben mit Implantat und Krone werden jetzt korrekt übernommen.
- Im Röntgenkontrollbuch kann jetzt die Patientennummer auf Wunsch angezeigt und gedruckt werden.

## 10.2.102
- Das Schließen der Anwendung, während Serien bearbeitet werden, führt nicht mehr zu einem Absturz.
- Die Überprüfung, ob eine Datenbank migriert werden kann, wird jetzt noch vor der Lizenzüberprüfung durchgeführt.
- Ein Fehler wurde behoben, durch den der Brennvorgang nicht funktionierte, wenn noch kein anderweitiger Exportvorgang durchgeführt wurde.
- Ein Fehler wurde behoben, durch den das Sortieren der Patientenliste zu einem Absturz führte, wenn die Patientennummer mehr als 18 Zeichen hatte.
- Sicherungsaufgaben werden nun auch korrekt ausgeführt, wenn das System anstelle eines Neustarts aus dem Ruhemodus zurückkehrt.

## 10.2.101
- Die geplanten Sicherungsaufgaben werden nun auch nach einem Neustart des Servers korrekt ausgeführt.
- Die Überprüfung, ob eine Datenbank migriert werden kann, funktioniert nun wie vorgesehen.
- Die Ausgaben während der Migration wurden optimiert.
- Weitere kleinere Fehler wurden behoben.

## 10.2.100
- Bei der Daten-Migration aus der alten byzz-Software wurden kleinere Fehler beseitigt.
- Hinweise betreffend dem Zugriff auf Netzlaufwerke (UNC) wurden im Server-Konfigurator eingefügt.
- Beim x-on Scan werden die Standard-Werte richtig gesetzt.
- Der Standard-Pfad zum Ez3D-i wird korrekt eingetragen.
- Die Bildübergabe von Röntgen-Aufnahmen zwischen Röntgen-Scanner und byzz nxt wurde überarbeitet.

## Ältere Versionen
- [Versionen 10.2.9x](UpdateNews-10.2.9x.md)