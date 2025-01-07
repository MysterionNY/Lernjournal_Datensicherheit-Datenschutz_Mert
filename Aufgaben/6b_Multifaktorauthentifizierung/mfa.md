# MFA

## Zweck
In diesem Beitrag gehe ich darauf ein, welchen Zweck MFA hat. Darunter gehört die verallgemeinerte Multi-Faktor-Authentifizierung. Diese beinhaltet dementsprechend die 2FA und 3FA

## 2-Faktor-Authentisierung (2FA)
Die 2-Faktor-Authentisierung ist eine Sicherheitsmassnahme, bei der zwei unterschiedliche und unabhängige Faktoren verwendet werden, um die Identität eines Benutzers zu überprüfen. Ziel ist es, die Sicherheit zu erhöhen, indem ein zweiter Schritt hinzugefügt wird, der über das blosse Passwort hinausgeht. Die Faktoren kommen aus unterschiedlichen Kategorien:

### Die potenziellen Faktoren:
Wissen: Etwas, das der Benutzer weiss (z. B. Passwort, PIN).
Besitz: Etwas, das der Benutzer besitzt (z. B. Smartphone, Token, Karte).
Sein: Etwas, das der Benutzer ist (z. B. Fingerabdruck, Gesichtserkennung).

### Beispiel für 2FA:
Der Benutzer gibt sein Passwort (Wissen) ein.
Danach erhält er einen Code auf sein Smartphone (Besitz), den er zusätzlich eingeben muss.

### Szenario für 2FA:
Ein Benutzer meldet sich bei einem Online-Banking-System an. Nach Eingabe seines Passworts wird ein SMS-Code an sein Smartphone gesendet, den er eingeben muss, um Zugriff auf sein Konto zu erhalten.

## 3-Faktor-Authentisierung (3FA)
Die 3-Faktor-Authentisierung erweitert die Sicherheit, indem ein dritter Faktor hinzugefügt wird. Der Benutzer muss sich über alle drei Kategorien gleichzeitig authentifizieren. Dadurch wird die Sicherheit nochmals deutlich erhöht, da es unwahrscheinlicher ist, alle drei Faktoren zu kompromittieren.

### Die drei Faktoren umfassen:
Wissen: Etwas, das der Benutzer weiss (z. B. ein Passwort).
Besitz: Etwas, das der Benutzer besitzt (z. B. eine Chipkarte oder ein Token).
Sein: Etwas, das der Benutzer ist (z. B. Fingerabdruck, Iris-Scan).

### Beispiel für 3FA:
Der Benutzer gibt ein Passwort ein (Wissen).
Er nutzt einen physischen Token oder eine Smartcard (Besitz).
Zusätzlich wird sein Fingerabdruck gescannt (Sein).

### Szenario für 3FA:

Ein Mitarbeiter greift auf ein hochsicheres Firmensystem zu:

Er gibt seine PIN ein.
Er steckt einen Sicherheits-Token in einen Kartenleser.
Schliesslich wird sein Fingerabdruck gescannt, bevor der Zugang gewährt wird.