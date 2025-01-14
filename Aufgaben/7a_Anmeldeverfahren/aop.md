# Anmeldeverfahren ohne Passwörter

## Zweck
In diesem Beitrag gehe ich darauf ein wie ein Anmeldeverfahren ohne Passwörter funktioniert. Dieses Wissen basiert auf einer 12 Minütigen Audio, welches mir mein Lehrer zur Verfügung gestellt hat. Dabei gehe ich auf diverse Fragen ein, um unklarheiten zu klären.

## FIDO - Anmeldeverfahren ohne Passwörter
### Warum sind Passwörter unsicher?
Dadurch dass en Passwort nicht nur durch sich selbst gesichert werden muss, sondern auch durch den Provider, entsteht ein Risiko, sofern der Provider, welches das Passwort sichern musste, komprimiert wird. Ebenso müssen wir bei der Menge unserer Konten die wir besitzen, eine grosse Menge an Passwörtern uns merken und uns gegenfalls neue ausdenken, was dann wiederum dafür sorgt, dass wir diese irgendwo sichern müssen, ausserhalb von unserem Kopf.

### Wie geht ein passwortloses Anmeldeverfahren?
Es wird beim FIDO ein Device benötigt, womit die Erkennung nicht mehr durch ein Passwort geschieht, sondern durch die Erkennung des Gesichtes, Fingerscans oder ähnlichem. Sodurch wird die Authentifizierung erfolgreich durchgeführt.

### Warum ist eine Anmeldung mit einem PIN auch gut?
Den Pin kennt nur einer selbst, selbst ein Anbieter wie Twint, obwohl es dort verwendet wird, kennt den Pin nicht, da dieser über das Handy läuft. 

### Was sind die "Faktoren" für ein Anmeldeverfahren?
- Haben
- Wissen/Sein
  
Haben ist das vorhandensein des Geräts selbst.

Wissen/Sein ist das wissen des Pins oder das Sein, wie die Biometrischeerkennung

### Passkey - Wie kann man Passwörter ersetzen?
Durch Biometrischeerkennung oder durch einen Pin.

### Wie funktioniert das Public-/Private-Key-Verfahren
Mit dem Public-Key ist es möglich etwas zu verschlüsseln, es steht jedem zur Verfügung, den kann auch jedem gegeben werden. Wohingegen der Private-Key privat bleibt. Mit dem Privat-Key hat man dann sozusagen die Option, etwas verschlüsseltes wieder zu entschlüsseln.

### Wie geht das digitale unterschreiben?
![Digitales Unterschreiben][digitalU]

### Was ist der Vorteil dieses FIDO-Verfahrens?
Man muss kein Geheimnis mehr teilen. Es gibt keine Kopie beim Provider, es liegt sicher beim "Safe" des Users auf dem Rechner. Darauf kann nur mit einer Biometrischenerkennung oder einem Pin zugegriffen werden.

### Warum ist dieses System noch nicht so verbreitet?
Die Verbreitung ist das Problem, es gibt nicht genug Anbieter, welche die Möglichkeit bieten, um dieses System zu verbreiten und den Service anzubieten. Daher ist es auch schwieriger es an die User zu bringen, obwohl dies eine gute Möglichkeit bietet.

[digitalU]: /Aufgaben/7a_Anmeldeverfahren/Digitalesunterschreiben.png