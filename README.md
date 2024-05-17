# Apache + PHP 8 + MySQL + phpMyAdmin
> Ambiente local de desenvolvimento PHP com Docker

Este repositório contém configurações Docker para a montagem de ambiente de desenvolvimento PHP local com Apache, PHP 8, MySQL e phpMyAdmin.

**Pré requisitos:** Docker e Docker Compose

```bash
# Criar e levantar os containers
docker compose up -d

# Iniciar o container Docker
docker compose start

# Parar o container Docker
docker compose stop

# Parar e remover containers da máquina
docker compose down
```

**Acesso localhost**
```txt
http://localhost
```

**Acesso phpMyAdmin**
```txt
http://localhost:4500

login: docker
senha: docker
```