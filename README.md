# My nextcloud suite


## Install

1. Install `docker-compose` [hier](https://docs.docker.com/compose/install/).
Ik raad zelf aan om linux te gebruiken maar als je gemakelijker ontwikkeld op windows kun je dat ook gebruiken, wellicht is WSL dan goed.
2. Open de terminal in je work directory
3. Clone deze repo `git clone https://github.com/WillemMe/nextcloud-suite.git'
4. `cd nextcloud-suite` of `dir nextcloud-suite` op windows.
5. Start docker `docker-compose -f local-docker-compose.yml up`
6. Zie je opgeving download en gebouwd worden
7. Ga naar `http://localhost` nu krijg je de admin config
8. Als je storag & database op moet geven kies dan MariaDB, geeft het wachtword uit de compose: `NotMyPassword`
9. Install de apps, rechts boven > + Apps:
	- Calander
	- Mail
	- Passwords
	- Survey
	- NextCloud Office (Kan niet lokaal gebruikt worden)
10. Kijk rond


Docker-compose tips:
- Met `docker-compose up -d` run je ze in de achtergrond
- Met `docker-compose ps` zie je alle draaiende containers
- Met `docker-compose down` sluit je alle containers
- Met `docker-compose restart` restart je de containers in `ps` staan
