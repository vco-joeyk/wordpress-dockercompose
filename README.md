# wordpress-dockercompose

## How to run:

**Tip:** draai zonder VPN, met VPN doet het bij mij heel raar, ben er nog niet achter waarom.
```
// clone deze repo naar een lokatie lokaal:
git clone git@github.com:vco-joeyk/wordpress-dockercompose.git

// cd naar de directory
cd wordpress-dockercompose

// maak een nieuw .env bestand aan:
// linux/macos:
touch .env

// windows:
ni .env

// open het .env bestand in een editor en voeg het volgende eraan toe:
MYSQL_ROOT_PASSWORD=<rootPassword>
MYSQL_USER=<userName>
MYSQL_PASSWORD=<userPassword>

// breng de containers omhoog:
// linux, niet rootless
sudo docker compose up -d

// de rest
docker compose up -d // laat -d weg als je de containers niet detached wilt runnen
```
