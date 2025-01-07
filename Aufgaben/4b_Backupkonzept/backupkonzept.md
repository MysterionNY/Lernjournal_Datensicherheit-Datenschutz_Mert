# Backupkonzept

## Zweck
In diesem Dokument gehe ich auf die Daten eines Backupkonzeptes ein.

Unter anderem erläutere ich auch, wann welche Dateien am besten gesichert werden sollten und welche noch warten könnten.

## Konzept
| Service        | Funktion                              | Betroffene Daten                | Backup                                     | Wiederherstellung                                      | Häufigkeit |
|----------------|---------------------------------------|----------------------------------|--------------------------------------------|--------------------------------------------------------|-----|
| WhatsApp       | Nachrichtenversand, mit Text, Bilder und Videos | Bilder, Text und Videos          | Daten werden, sofern eingestellt, lokal gebackupt oder in der Cloud gespeichert (z. B. Google Drive) | Bei Neuinstallation der Applikation, können die Daten zurückgeholt werden | Automatisch, in der Regel 1x die Woche |
| Google Drive   | Cloud-Speicher für Dateien und Dokumente | Dokumente, Bilder, Videos        | Automatische Synchronisierung und Sicherung in der Cloud | Zugriff über jeden angemeldeten Google-Account         | 1x Woche |
| iCloud         | Cloud-Speicher und Synchronisierung   | Fotos, Kontakte, Kalender, Notizen | Automatische Synchronisierung und Sicherung in der iCloud | Über Apple-ID und Wiederherstellungstool verfügbar     | 1x Woche |
| Dropbox        | Cloud-Speicher für Dateien            | Dokumente, Fotos, Videos         | Automatische Synchronisierung und Versionierung in der Cloud | Zugriff über Webinterface oder lokale App              | 1x Woche |
| Microsoft OneDrive | Cloud-Speicher und Synchronisierung | Office-Dokumente, Fotos, Videos   | Automatische Synchronisierung mit der Microsoft-Cloud   | Daten können direkt über den Microsoft-Account wiederhergestellt werden | 1 x Woche |
| Windows Backup | Systemabbild und Dateisicherung       | Betriebssystem, Programme, Dateien | Manuelles oder geplantes Systemabbild und Dateiversionen | Wiederherstellung über Windows-Wiederherstellungsoptionen | 6-12 Monate |
| Google Photos  | Speicherung und Synchronisierung von Bildern und Videos | Fotos und Videos                 | Automatische Sicherung in der Cloud                    | Zugriff über Google-Account, Wiederherstellung über App oder Browser | 1x Woche |
| GitHub/GitLab  | Versionskontrolle für Softwareprojekte | Quellcode, Dokumentationen       | Automatische Synchronisierung bei Pushes               | Klonen des Repositories, Zugriff über Account          | 1-3 Tage |

## Zusatzfrage
Um ein Backup zu automatisieren, beginnt man damit, die Zielsetzung und Strategie festzulegen. Es muss entschieden werden, welche Daten gesichert werden sollen, wie häufig dies geschehen soll und wo die Backups gespeichert werden. Dabei gibt es die Wahl zwischen lokalen Backups, beispielsweise auf einer externen Festplatte, und Cloud-Diensten wie Google Drive oder AWS.

Als nächstes wählt man eine geeignete Software oder Methode aus. Tools wie Rsync für Linux, die integrierte Windows-Backup-Funktion oder spezialisierte Software wie Acronis True Image bieten unterschiedliche Funktionen für automatische Sicherungen. Alternativ kann ein eigenes Skript erstellt werden, das die relevanten Dateien in den vorgesehenen Speicherort kopiert.

Die Automatisierung erfolgt durch die Nutzung von Systemwerkzeugen wie cron unter Linux oder der Aufgabenplanung in Windows, um das Backup-Skript regelmässig auszuführen. Gleichzeitig ist es wichtig, den Speicherplatz für Backups zu überwachen, um sicherzustellen, dass genügend Platz für neue Sicherungen vorhanden ist.
