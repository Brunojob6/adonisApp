# Description

Clone AirBnB com AdonisJS, React Native e ReactJS, onde iremos construir do zero uma aplicação tanto web quando mobile com dados servidos através de uma API REST feita com NodeJS utilizando o framework AdonisJS.

# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
