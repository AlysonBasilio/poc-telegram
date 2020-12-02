# poc-telegram

## How to use

First, you must create your `.env` file.
```sh
cp .env.example .env
```
To generate your api id and hash, [read this](https://core.telegram.org/api/obtaining_api_id).

### In a dockerized environment

```sh
docker-compose build
docker-compose up
```

### In a not dockerized environment

```sh
npm install
node index.js
```