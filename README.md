# Educational-System-Docker

A tudástár alkalmazás konténerizált környezete.

## Előfeltételek:
- [Docker](https://www.docker.com/)
- [NodeJs](https://nodejs.org/en/)

## Beüzemelés

1. `git clone https://github.com/Xizi0n/Educational-System-Docker.git`

2. `cd Educational-System-Docker`

3. `docker-compose up --build`

**Ezután az alkalmazás szerverei az alábbi módon érhetőek el:**
- Frontend alkalmazás:  `localhost:4200`
- Fő backend szerver:   `localhost:4001`
- Képfeltöltő szerver:  `localhost:4002`
- PDF feltöltő szerver: `localhost:4003`

A konténerek leállítása: `docker-compose down`
