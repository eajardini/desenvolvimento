# Instalar postgre via docker

- Com database externo:
``` sql    
docker run --name postgres16.3_aula -e POSTGRES_USER=postgres  -e POSTGRES_PASSWORD=p0stdbA1 -d -p 5432:5432 -v /opt/postgres/16/data:/var/lib/postgresql/data  postgres:16.3
```