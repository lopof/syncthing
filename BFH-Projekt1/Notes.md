# Notizen zum Projektstart

## TODO

### Erstellen

* Scrum Projektdateien
* Termin mit Auftraggeber und Projektbetreuer

### Abklären

* Thomas   | Versionierungsmöglichkeiten ergründen
* Severin  | Gerätekennung mit Emailadresse - LDAP
* Thomas   | Kann der Code bei Windows, MAC und (Linux) gleichermassen verwendet werden -> Ja, sogar cross-compiling möglich
* Severin  | Konfliktlösungsansatz (Gleichzeitige verwendung einer Datei von verschiedenen User)
* Thomas   | Was wird bei Syncthing verwendet (Webserver etc...)
* Team     | Wird die Versionierung gemacht, wenn Syncthing nicht gestartet ist?
* Team     | Data security, wie werden die Daten übertragen

### Herausforderungen

* Mit go klarkommen
* Neue Releases von Syncthing mergen mit eigener Version von Syncthing? -> Was ist am besten, fork oder eigene Repo?
* Handeln falls neue Releases in der App erscheinen. Sollte natürlich nur Updates von uns anzeigen

### TODO

* Eigenes Relay aufbauen
* Eigener Upgrade Server
* Eigener Discovery Server


### Probleme

* Bei lokalem verschieben/umbennenen vom Ordner könnte die synchronisation nicht mehr funktionieren. Die Daten werden wahrscheinlich sogar gelöscht auf den synchronisierten Geräten.
