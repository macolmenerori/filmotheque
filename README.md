# filmotheque

Simple movie collection management.

Check out [opensesame project](https://github.com/macolmenerori/opensesame) for the authentication part, [filmotheque-back](https://github.com/macolmenerori/filmotheque-back) for the API and [filmotheque-front](https://github.com/macolmenerori/filmotheque-front) for the front part, with a beatiful interface to manage the movies.

## Requirements

- [Docker](https://www.docker.com/products/docker-desktop/)
- [docker-compose](https://docs.docker.com/compose/install/)

## How to set up and run the full project

1. Clone this repo

```
git clone https://github.com/macolmenerori/filmotheque
```

2. Update `.example.env` file and rename it to `.env`. `TRAKT_CLIENT_ID` and `TRAKT_CLIENT_SECRET` can be obtained following [this instructions](https://trakt.docs.apiary.io/#reference/authentication-oauth).

3. Start the service

```
docker-compose up -d
```

4. Everything is ready now, go to `http://localhost:80` and sign in with default email and password

```
email: admin@admin.com
password: administrator
```
