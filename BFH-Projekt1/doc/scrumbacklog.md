# Scrum backlog
## Project team
Name | GitHub Alias | Function
--- | --- | --- 
Thomas Baumann | lopof | Developer
Severin Thalmann | manfred00 | Developer

Gesamtzeit für Projekt 1: 494 <br>
Gesamtzeit für Anforerdungsspezifikationen im Modul Projektmanagement: 26

## Product Backlog
ID | Storyname | Description | Priority | Effort plan original | Effort plan updated | Effort acutal | Status
--- | --- | --- | --- | --- | --- | --- | ---
1 | Anforderungsspezifikation | Dokument Anforderungsspezifikation schreiben | High | 26 | - | - | Open
2 | Überflüssige Module entfernen | Module die momentan im Syncthing Projekt integriert sind und nicht relevant sind für unser Projekt sollen entfernt werden. Dazu gehören: Autoupdate auf die neuste Version von Syncthing, Optionen im GUI welche wir nicht brauchen. | High |140 | - | - | Open
3 | Versionisierung anpassen | Bei der momentanen Versionierung wird momentan im Dateinamen das Datum und die Uhrzeit gespeichert, zusätzlich soll im Dateinamen ersichtlich sein wer die Datei bearbeitet hat. | High | 100 | - | - | Open
4 | Konflikthandling testen | Das Konflikthandling ist momentan integriert. Diese muss getestet und auf ihre Funktionalität geprüft werden. | High | 10 | - | - | Open
5 | Log der Versionisierung | In einer Versionskonsole sollen alle Versionen verwaltet werden können. Der momentane Log zeigt nur die letzten x Aenderungen. | High | 110 | – | – | Open
6 | UPD eigenes Relay aufsetzen | Damit die Uebertragung über das Internet funktioniert braucht es Relays, weil nicht jedes Gerät eine eigene IP-Adresse besitzt. Diese Relays sind momentan Fremdgehostet. Ziel wäre ein eigenes Relay aufzusetzen und dem System dieses Relay anzugeben. | Low | 35 | - | - | Open
7 | Authentifikation mit Email/LDAP (Out of scope)
8 | Neue Releases mergen (Out of scope)
9 | Automatisierung der Distribution und Authentifizierung (Out of scope)
10 | Dokumentation für Benutzer | Handbuch erstellen für Administrator und Nutzer, falls nötig auch Schulungsunterlagen | Medium | 10 | - | - | Open
11 | Reserve | - | - | 89 | - | - | Open



## Backlog Sprint 1 (8.10.2018 - 21.10.2018)
ID | Name | Description | Components | Owner | Reviewer | Priority | Effort plan original | Effort plan updated | Effort actual | Status
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
2.0 | Syncthing und GO Einarbeitung | Da wir beide keine Erfahrung haben mit GO und noch nichts mit dem Open Source Projekt Syncthing zu tun hatten, ist eine gewisse Einarbeitungszeit nötig. | - | - | - | High | 20 | - | - | Open
2.1 | Autoupdate entfernen | Damit unser System nicht auf die ursprüngliche Version des Syncthing updatet müssen wir diese Funktion entfernen. | Modul Autoupdate | tbh | sth | High | 20 | - | - | Open
2.2 | Optionen im GUI anpassen/entfernen | Einige Optionen im WEb GUI sind gefährlich (kritisch für die korrekte Ausführung des Systems) und sollen für die Benutzer nicht ersichtlich sein. | Modul GUI | sth | tba| High | 20 | - | - | Open



## Retro Sprint 1
### Positiv

### Negativ

### Actions


## Final Retro
### Positiv

### Negativ

### Known issues
