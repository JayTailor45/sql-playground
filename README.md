# SQL playground

A simple SQL playground which runs inside docker

## Commands:

- `docker compose up -d` :- run postgress db inside docker
- `docker compose down` :- stop postgress db inside docker
- `docker exec -it sql_db_1 sh` :- connect to running container
- `psql -U myuser -d mydatabase` :- start postgress shell

### More on shell commands

https://www.freecodecamp.org/news/manage-postgresql-with-psql/
