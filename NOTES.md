# Notes on useful docker-compose commands

## MS Sql
docker-compose -f docker-compose.mssql.yml up -d

## Postgres
docker-compose -f docker-compose.postgres.yml up -d

## MS Sql + Postgres
docker-compose -f docker-compose.mssql.yml -f docker-compose.postgres.yml up -d


