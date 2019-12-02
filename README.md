# Educational-System-Docker

A tudástár alkalmazás konténerizált környezete.

## Előfeltételek:
- [Docker](https://www.docker.com/)
- [NodeJs](https://nodejs.org/en/)

##  Backend beüzemelése

1. `git clone https://github.com/Xizi0n/Educational-System-Docker.git`

2. `cd Educational-System-Docker`

3. `docker-compose up --build`

**Ezután az alkalmazás szerverei az alábbi módon érhetőek el:**
- Fő backend szerver:   `localhost:4001`
- Képfeltöltő szerver:  `localhost:4002`
- PDF feltöltő szerver: `localhost:4003`

A konténerek leállítása: `docker-compose down`

## Frontend beüzemelése

1. `git clone https://github.com/Xizi0n/Educational-System-Docker.git`

2. `cd Educational-System-Docker/Angular7_Educational_System/Educational-System`

3. `npm install`

4. `node server.js`

5. A frontend alkalmazás itt érhető el: `localhost:4200`

Készítette: Nagy Ádám Richárd @ 2019

Elérhetőség: nagyadam9415"kukac"gmail.com
