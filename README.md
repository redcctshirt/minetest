# Minetest

* https://www.minetest.net/
* [Server-Liste](http://servers.minetest.net/)

## Minetest-Server

### Ubuntu Server 16.04

#### Installation

* `sudo apt-get install minetest-server` - Minetestserver installieren

#### Kontrolle

* `sudo systemctl minetest-server status` - Status anzeigen
* `sudo systemctl minetest-server stop` - Minetestserver stoppen
* `sudo systemctl minetest-server start` - Minetestserver starten
* `sudo systemctl minetest-server restart` - Minetestserver Neustart

#### Konfiguration

/etc/minetest/minetest.conf

```
# Portnummer (UDP)
port = 30000 
# Servername
server_name = Mein Minetest-Server
# Beschreibung
server_description = kurze Beschreibung
# Serverdomain
server_address = mein-minetest-server.de
# Homepage
server_url = http://www.mein-minetest-server.de
# Aufnahme in die Serverliste servers.minetest.net
server_announce = true
# URL der Serverliste
serverlist_url = servers.minetest.net
# Standard-Game wenn eine neue Welt erstellt wird
default_game = minetest
# Datenverzeichnis für eine Welt
map-dir = /var/games/minetest-server/.minetest/worlds/world
# Willkommensnachricht
motd = Willkommen auf diesem Server !
# Maximale Anzahl der Spieler
max_users = 15
# Gegenseitiges 'zum Schweigen bringen' aktivieren
enable_pvp = false
# Kreativmodus aktivieren
creative_mode = true
# Schaden zufügen aktivieren
enable_damage = false
# Privilegien aktivieren: interact, shout, teleport, settime, privs, usw., siehe /privs
default_privs = interact, shout

```


## Lizenz

Lizenz: https://creativecommons.org/publicdomain/zero/1.0/deed.de
