# Backupkonzept

## Zweck
In diesem Dokument gehe ich auf die Daten eines Backupkonzeptes ein.

Unter anderem erläutere ich auch, wann welche Dateien am besten gesichert werden sollten und welche noch warten könnten.

## Konzept
| Service        | Funktion                              | Betroffene Daten                | Backup                                     | Wiederherstellung                                      |
|----------------|---------------------------------------|----------------------------------|--------------------------------------------|--------------------------------------------------------|
| WhatsApp       | Nachrichtenversand, mit Text, Bilder und Videos | Bilder, Text und Videos          | Daten werden, sofern eingestellt, lokal gebackupt oder in der Cloud gespeichert (z. B. Google Drive) | Bei Neuinstallation der Applikation, können die Daten zurückgeholt werden |
| Google Drive   | Cloud-Speicher für Dateien und Dokumente | Dokumente, Bilder, Videos        | Automatische Synchronisierung und Sicherung in der Cloud | Zugriff über jeden angemeldeten Google-Account         |
| iCloud         | Cloud-Speicher und Synchronisierung   | Fotos, Kontakte, Kalender, Notizen | Automatische Synchronisierung und Sicherung in der iCloud | Über Apple-ID und Wiederherstellungstool verfügbar     |
| Dropbox        | Cloud-Speicher für Dateien            | Dokumente, Fotos, Videos         | Automatische Synchronisierung und Versionierung in der Cloud | Zugriff über Webinterface oder lokale App              |
| Microsoft OneDrive | Cloud-Speicher und Synchronisierung | Office-Dokumente, Fotos, Videos   | Automatische Synchronisierung mit der Microsoft-Cloud   | Daten können direkt über den Microsoft-Account wiederhergestellt werden |
| Windows Backup | Systemabbild und Dateisicherung       | Betriebssystem, Programme, Dateien | Manuelles oder geplantes Systemabbild und Dateiversionen | Wiederherstellung über Windows-Wiederherstellungsoptionen |
| Google Photos  | Speicherung und Synchronisierung von Bildern und Videos | Fotos und Videos                 | Automatische Sicherung in der Cloud                    | Zugriff über Google-Account, Wiederherstellung über App oder Browser |
| GitHub/GitLab  | Versionskontrolle für Softwareprojekte | Quellcode, Dokumentationen       | Automatische Synchronisierung bei Pushes               | Klonen des Repositories, Zugriff über Account          |