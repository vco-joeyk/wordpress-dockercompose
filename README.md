# wordpress-dockercompose

## How to run:
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
docker compose up -d // laat -d weg als je de containers niet detached wilt runnen
```
