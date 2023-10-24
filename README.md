## SQL Server Workspace

- Iniciar o container:
```sh
docker-compose up -d
```

- Desligar o container:
```sh
docker-compose stop
```

- Desativar e Remover o container:
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
/opt/mssql-tools/bin/sqlcmd -S localhost -U usuario -P senha
```

- Importante:
É necessário alterar a variável de senha dentro do docker-compose com a senha que você quiser.
