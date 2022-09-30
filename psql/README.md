# Postgre SQL

## Cara Login ke Docker Postgres 

```
    docker exec -it [container name] psql -U [username] [database name]
```

contoh
```
    docker exec -it my-pg psql -U user database
```