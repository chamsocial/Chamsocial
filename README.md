# [Chamsocial](https://www.chamsocial.com)

### Requirements
* Nodejs 7.10
* MySQL 5.7
* Redis

### Installation
* `cp .env.example ../.env` and add custom config
* `npm install`
* `cd site`
* *  `npm install`
* *  `npm run init` *(Installs bower dependencies and runs gulp)*
* *  *Optional* New tab `npm run watch` *(gulp watch for file changes)*
* `cd ../`
* New tab `docker-compose up` *(Starts mysql and redis containters)*
* `node scripts/init-db.js` *(Create db tables and a dummy user & post)*
* `npm run dev`
