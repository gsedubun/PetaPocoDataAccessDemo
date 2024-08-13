to run docker container with sql server 2022
```bash
sudo docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=pass12345" -p 1433:1433 --hostname sql1 mcr.microsoft.com/mssql/server:2022-latest
```
to run docker container with mysql server 8.0
```bash
sudo docker run -e MYSQL_ROOT_PASSWORD=Del12345 -p 3306:3306 --hostname mysql1 mysql:8.0
```

to run docker container with postgresql server 13
```bash
sudo docker run -e POSTGRES_PASSWORD=pass12345 -p 5432:5432 --hostname pg1 postgres:13
```