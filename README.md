## SQL Server Workspace

- Iniciar a imagem docker:
```sh
docker-compose up -d
```

- Desligar a imagem docker:
```sh
docker-compose down
```

- Verificar logs:
```sh
docker-compose logs sql-server-db
```

- Conectar no terminal do container:
```sh
docker exec -it sql-server-db "bash"
```

- Conectar no SQL Server dentro do container:
```sh
opt/mssql-tools/bin/sqlcmd -S localhost -U usuario -P senha
```