<p align="center">
  <img src="https://i.imgur.com/X6bur7W.png" height='300'/>
</p>

# 🗂️ MySQL-Simple-Database 
> A simple database using MySQL

## 📜 Requirements
1. Docker 20.10 or newer
2. MySQL 8.0.30 for Linux on x86_64 or newer

## ⚙️ Installation
```
#instalando o repositorio docker no computador
docker pull mysql:latest

docker run --name db -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=123 mysql:latest

#importando o arquivo Dockerfile
cd Desktop
cat Dockerfile

#criando uma imagem
docker build -t simple-database .

#criando um container para a imagem acima
docker run --name db2 -p3306:3306 -d simple-database

```
## 📝 MySQL Commands
- use users;
- show tables;
- select * from users;
  
## 🌎 Locales
Currently available locales are:
- English (en)

<p align="center">
  Created on <br>
  12/09/2022
</p>
