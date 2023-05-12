# Update Hinweise zu byzz nxt (für Versionen 10.2.9x)

- [Neueste Änderungen](../README.md)

## 10.2.99
- Ein Fehler wurde behoben, durch den beim Drucken die zuschaltbaren Textinformationen wie beim Export in die Bilder gezeichnet wurden.
- Gendex VisualiX eHD Sensoren werden jetzt unterstützt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.98
- Aufnahmen, die über Aufnahmeaufträge erstellt werden, übernehmen jetzt anstatt des angemeldeten den ausführenden Arzt des Auftrages.
- byzz Constancy: Ist ein Benutzer der Gruppe Benutzer angemeldet, wird Konstanzaufnahmen jetzt anstatt des angemeldeten Benutzers immer ein Benutzer der Gruppe Arzt zugewiesen.

## 10.2.97
- Server Konfigurator - Wartung: Es können jetzt beliebig viele Sicherungsverzeichnisse angegeben und über einen Alias in byzz Maintenance zur Verfügung gestellt werden. Sicherungen können bei Bedarf somit wieder in verschiedenen Speicherorten abgelegt werden.
- byzz Maintenance:
  - Die Ablage der Sicherung wird jetzt über die Angabe eines Speicherortes (= ein Alias für ein Verzeichnis) definiert.
  - Sicherungen als auch die Wiederherstellung werden jetzt auch nach Speicher-orten getrennt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.96
- Im Login Dialog wird die Darstellung von zu langen Namen jetzt begrenzt.
- Geöffnete Bildparameter werden jetzt nicht mehr bei jedem Ansichtswechsel geschlossen, stattdessen bleiben diese geöffnet, sofern es sich bei der neuen Ansicht ebenfalls um eine Bildansicht handelt.
- Im Vollbildmodus konnte es vorkommen, dass das Fenster an den Rändern etwas abgeschnitten war – dies wurde behoben.
- Byzz Constancy: Die Zeiteinheiten im Hauptfenster werden jetzt wieder korrekt dargestellt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.95
- TransCrypt: Ein Fehler wurde behoben, durch den bestimmte Modell- und Dokumentendaten nicht versendet oder empfangen werden konnten.
- VDDS
  - Ein Fehler wurde behoben, durch den die Control Center Ansicht nicht aktualisiert wurde, nachdem ein neuer Patient übertragen wurde.
  - Ein Fehler wurde behoben, durch den ein Bild nicht angezeigt wurde.
  - Ein Fehler wurde behoben, durch den eine falsche Patientennummer angezeigt wurde.
- Ein Fehler wurde behoben, durch den die Konstanzprüfung Erinnerungseinstellung um einen Tag versetzt war.
- Waren noch keine Elemente im Katalog vorhanden, wurden falsche Wurzelknoten angezeigt – dies wurde behoben.
- Weitere kleinere Fehler wurden behoben.

## 10.2.94
- Der Aufnahmebestätigungsdialog kann jetzt in den Admin-Einstellungen deaktiviert werden.
- Geöffnete Bilder können jetzt in die Zwischenablage kopiert werden.
- Ein Fehler wurde behoben, der Dokumente immer mit einer Größe von 1KB anzeigte, wenn der Client nicht in derselben Domäne war, wie der Server.
- byzz Constancy
  - Uraufnahmen können unmittelbar nach der Erstellung wieder korrekt bearbei-tet werden.
  - Ein Fehler beim Kopieren einer Aufnahme der zur Unbedienbarkeit der Oberfläche führte wurde behoben.
  - Der Druckdialog zum Drucken der Konstanzliste wurde überarbeitet.
  - Ein Abbruch des Login Vorgangs führt jetzt nicht mehr zum Absturz.
- TransCrypt Benachrichtigungen funktionieren wieder wie vorgesehen.
- Die Implantatliste der Bildansicht wird jetzt nach erfolgter Bearbeitung korrekt aktualisiert.
- Die Lupenfunktion der Hauptansicht funktioniert jetzt auch mit ungewöhnlichen Monitorkonstellationen und Bildschirmskalierungen.
- Drucken:
  - Für die Textoptionen kann jetzt ein Schriftgrad (klein, mittel, groß) gewählt werden.
  - In der Kopfzeile wird jetzt die Praxisadresse angezeigt, sofern diese hinterlegt ist. Anderenfalls wird die Adresse aus den Lizenzdaten genommen, sofern auch diese hinterlegt ist.
- Wenn das Programm lief und über eine Remotedesktopverbindung zugegriffen oder Bildschirmkonfigurationen (z.B. Ändern der Auflösung) vorgenommen wurden, konnte ein Fehler der Oberfläche zum Absturz führen – dies wurde behoben.
- Weitere kleinere Fehler wurden behoben.

## 10.2.93
- In der Bildansicht wurde links oben eine Schaltfläche hinzugefügt, die das Bild in die Ursprungsposition zoomen lässt, ohne dass der Zoommonitor geöffnet werden muss.
- Dokumentenansicht: Bei Doppelklick auf Bilder, Videos und Modelle wird jetzt der interne Viewer (ohne Zoomfunktion) geöffnet.
- Eine Schaltfläche für das Control Center wurde in der Werkzeugleiste der Hauptansicht hinzugefügt.
- Röntgenkontrollbuch:
  - Die Patientennummer kann jetzt optional hinzugeschaltet werden.
  - Beim Drucken wird jetzt die aktuelle Spaltensortierung beachtet.
- DVT Daten ohne entsprechende Datei-Endung werden jetzt korrekt importiert und korrigiert.
- Im Login-Dialog wird jetzt zusätzlich hinter jedem Namen die Benutzergruppe angezeigt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.92
- Es wurden einige Datei-Zugriffsprobleme bei außerhalb von Domänen befindlichen Rechnern behoben.
- Dokumente: Umbenennen funktioniert jetzt wieder korrekt.
- Brennen: Ein Fehler bei der Erstellung von Abbildern im Dateisystem wurde behoben.
- Die Patientenliste wird jetzt natürlicher sortiert, so dass insbesondere die Sortierung nach Nummer ein besseres Ergebnis liefert.
- In der Patientenmaske wurde ein Fehler behoben, der in manchen Fällend verhinderte, dass die korrekte Praxis bzw. der korrekte Behandler gesetzt wird.
- Aktualisierung des Setups
  - Installation und Update: Falls vorhanden werden jetzt alle Datenbankverbindungen beachtet und alle zugreifbaren Datenbanken aktualisiert. Hierbei findet eine Validierung statt, die online überprüft, ob ein Wartungsvertrag vorliegt oder nicht. Falls dies nicht der Fall ist oder keine Internetverbindung möglich ist, muss für jede zu aktualisierende Datenbank (außer Demo Datenbanken) ein Aktualisierungscode eingegeben werden. Für die zur jeweiligen Datenbank zugehörige Postgres Administrationsdatenbank kann jetzt bei Bedarf das Passwort angegeben werden.
  - Deinstallation: Anmeldeinformationen für den Server Dienst werden jetzt korrekt aus dem System entfernt.
- byzz Constancy
  - Ein Fehler wurde behoben durch den Abweichungen zwischen Aufnahme und Zulassungsaufnahme trotzdem als gültig angenommen wurden.
  - Eine nachträgliche Gerätetypänderung ist jetzt nach Eingabe des Kennworts möglich.
- Erinnerungen zur Konstanzprüfung für inaktive Einrichtungen werden nicht länger angezeigt.
- Die Abschaltung der automatischen Drehung für Scanner funktioniert jetzt korrekt.
- Notizen: Der Cursor zur Texteingabe funktioniert jetzt korrekt.
- Export: Falls aus irgendwelchen Gründen Dateien nicht korrekt gelesen werden können, wird bereits der Start des Exportvorganges mit einer Meldung abgebrochen.
- Drucken: Es wird jetzt eine Schaltfläche angeboten über den Systemdialog zu drucken, der weitere Einstellungen erlaubt.
- Metadaten: In den Einstellungen können jetzt beliebige Schlüsselwortlisten für die Rechtfertigende Indikation verwendet werden. Ist keine Liste hierfür gesetzt, ist eine Schaltfläche sichtbar, die das Laden einer mitgelieferten Vorlage erlaubt.
- Weitere kleinere Fehler wurden behoben.

## 10.2.91
- Umstellung der Softwarearchitektur:
  - byzz nxt Server arbeiten jetzt als Hintergrunddienst mit alleinigem Zugriff auf die Datenbank und dienen als zentrale Verbindungsstelle aller Clients.
  - byzz nxt Clients verbinden sich nur noch mit dem Server Dienst und benötigen nicht länger Kenntnis der Datenbank.
  - Bei Neuinstallationen wird PostgreSQL in einer aktuellen Version verwendet.
  - Neues Konfigurationstool: byzz nxt Server Konfigurator
Serverseitige administrative Aufgaben wie Server Adresse und Port, Freigabe im Netzwerk, Datenbankverwaltung sowie die Festlegung des Sicherungsverzeichnisses werden hier durchgeführt. Zum Starten des Programms werden gehobe-ne Rechte benötigt.
  - byzz Maintenance
  - Durch die Bereitstellung des Konfigurationstools entfällt die Angabe des Sicherungsverzeichnisses.
  - Für die Wiederherstellung werden jetzt alle gefundenen bisherigen Sicherungen in einer Liste angeboten.
- Im Zuge der Architekturumstellung wurden viele Oberflächenaktualisierungen und -anpassungen vorgenommen. Auf manchen Dialogen (z.B. Export) befinden sich daher Schaltflächen möglicherweise an einer anderen Position.
- Fensterpositionen und -größen beachten jetzt auch Monitorkonfigurationen mit unkonventionellen Auflösungen und Skalierungen.
- Es können jetzt Aufnahmeaufträge angelegt und an andere Arbeitsstationen gesendet werden. Genauere Informationen hierzu finden Sie im Handbuch.
- Administratoren können jetzt im Control Center eine Vorlage erstellen, die von jedem Benutzer verwendet werden kann.
- Auf Multimonitorsystemen kann jetzt für die Funktionen Bilder vergleichen, Lichttisch und Testbild der Zielmonitor angegeben werden.
- Die geöffnete Patientenschnellauswahl zeigt jetzt beim Überfahren mit der Maus dieselben Informationen, wie in der Patientenliste.
- byzz Constancy: Ein Fehler wurde behoben, durch den beim Drucken der Konstanzliste der Monat als nicht bestanden markiert wurde, obwohl die Aufnahmen als bestanden gekennzeichnet waren.
- x-on Scan Einstellungen: Es wurde eine Auswahl der Sensorauflösung zwischen 600 und 1200 DPI bereitgestellt.
- Änderungen der Logout Einstelllungen werden jetzt ohne Neustart übernommen.
- Export:
  - Die interne Verarbeitung wurde überarbeitet, so dass deutlich weniger Speicherplatz der C-Platte benötigt wird.
  - Zip Optionen werden jetzt für alle Export Typen (außer TransCrypt) angeboten. Als Passwort kann das Geburtsdatum des Patienten gewählt oder ein eigenes angegeben werden. Eigene Passwörter werden dabei auf Gültigkeit überprüft.
  - Jeder Export Typ verwendet jetzt seine eigenen Einstellungen. Beim Wechsel des Export Typs werden somit die zuletzt gemachten Optionen für diesen Typ gesetzt.
- Ein Absturz wurden behoben, der auftrat, wenn versucht wurde Dokumente zu öffnen, die im System keiner Anwendung zugeordnet werden.
- Ein Absturz wurde behoben, der auftrat, wenn versucht wurde auf Dateien zuzugreifen, auf die nicht länger zugegriffen werden darf (z.B. durch geänderte Netzwerkeinstellungen oder versehentlich geänderte Zugriffsrechte des Datenverzeichnisses auf dem Server).
- Weitere kleinere Fehler wurden behoben.

## 10.2.90
- Das Importverhalten für dentaleyepad wurde angepasst, so dass auch Bilder importiert werden, die zwar einer Ansicht, nicht jedoch einem Template zugeordnet werden können.

## Ältere Versionen
- [10.2.8x](UpdateNews-10.2.8x.md)