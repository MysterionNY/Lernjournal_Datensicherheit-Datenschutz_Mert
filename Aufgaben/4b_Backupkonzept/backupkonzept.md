# Backupkonzept

## Zweck
In diesem Dokument gehe ich auf die Daten eines Backupkonzeptes ein.

Unter anderem erläutere ich auch, wann welche Dateien am besten gesichert werden sollten und welche noch warten könnten.

## Konzept
| Service        | Funktion                              | Betroffene Daten                | Backup                                     | Wiederherstellung                                      | Häufigkeit |
|----------------|---------------------------------------|----------------------------------|--------------------------------------------|--------------------------------------------------------|
| WhatsApp       | Nachrichtenversand, mit Text, Bilder und Videos | Bilder, Text und Videos          | Daten werden, sofern eingestellt, lokal gebackupt oder in der Cloud gespeichert (z. B. Google Drive) | Bei Neuinstallation der Applikation, können die Daten zurückgeholt werden | Automatisch, in der Regel 1x die Woche |
| Google Drive   | Cloud-Speicher für Dateien und Dokumente | Dokumente, Bilder, Videos        | Automatische Synchronisierung und Sicherung in der Cloud | Zugriff über jeden angemeldeten Google-Account         | 1x Woche |
| iCloud         | Cloud-Speicher und Synchronisierung   | Fotos, Kontakte, Kalender, Notizen | Automatische Synchronisierung und Sicherung in der iCloud | Über Apple-ID und Wiederherstellungstool verfügbar     | 1x Woche |
| Dropbox        | Cloud-Speicher für Dateien            | Dokumente, Fotos, Videos         | Automatische Synchronisierung und Versionierung in der Cloud | Zugriff über Webinterface oder lokale App              | 1x Woche |
| Microsoft OneDrive | Cloud-Speicher und Synchronisierung | Office-Dokumente, Fotos, Videos   | Automatische Synchronisierung mit der Microsoft-Cloud   | Daten können direkt über den Microsoft-Account wiederhergestellt werden | 1 x Woche |
| Windows Backup | Systemabbild und Dateisicherung       | Betriebssystem, Programme, Dateien | Manuelles oder geplantes Systemabbild und Dateiversionen | Wiederherstellung über Windows-Wiederherstellungsoptionen | 6-12 Monate |
| Google Photos  | Speicherung und Synchronisierung von Bildern und Videos | Fotos und Videos                 | Automatische Sicherung in der Cloud                    | Zugriff über Google-Account, Wiederherstellung über App oder Browser | 1x Woche |
| GitHub/GitLab  | Versionskontrolle für Softwareprojekte | Quellcode, Dokumentationen       | Automatische Synchronisierung bei Pushes               | Klonen des Repositories, Zugriff über Account          | 1-3 Tage |