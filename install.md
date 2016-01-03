Cannot find module 'mongodb'

=Abhängigkeiten/bibliotheken=
*mongodb

=Install=
# mongodb
# nodejs / mongodb
# git
# lobbyradar clonen
# npm install
# npm update
# node lobbyradar.js 
## Fehlermeldung: config.js module nicht gefunden
## config.js.dist -> config.js & ggf. anpassen
## url starten nun müsste die website ohne css usw. sichtbar sein& node gibt keine fehlermeldungen auf der console aus
# nach /root/assets wechseln
# npm install bower -g (ist wichtig damits global installiert wird)
# bower install im asset-verzeichnis ausführen
# node lobbyradar.js
# website vollständig sichtbar(alle ressourcen werden angezeigt, bilder/css)
# Daten in DB importieren:
## mongorestore --db lobbyradar --collection entities dumps/entities.bson
## mongorestore --db lobbyradar --collection relations dumps/relations.bson
## verbindungssuche - rüstung sollte diagram anzeigen
# gesamtdiagram erstellen:
##graphicsmagick installieren (http://packages.ubuntu.com/search?keywords=graphicsmagick)
##in lobbynetwork-dir shell script starten
# im root verzeichnis node lobbyradar.js ausführen - nun müsste alles korrekt laufen
