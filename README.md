# Compass - Atividade de Docker

## Instalação do Docker no Windows

## Instalação do WordPress & MySQL usando o Docker

### Instruções

1. crie uma pasta chamada `wp-docker`
2. abra o PowerShell e use o comando `cd` para que a pasta `wp-docker` se torne o *working directory*
3. faça o download do arquivo [`docker-compose.yml`](docker-compose.yml) e use o comando `move` para mover esse arquivo da pasta `Downloads` para a pasta `wp-docker`
4. execute o commando `docker compose up` para criar e inicializar os containers
5. aguarde os containers serem inicializados e quando a mensagem "ready for connections" aparecer, você poderá começar a usar o WordPress a partir desse [link](http://localhost:80)

### Por que escolhemos o **Docker Compose**?

- O Docker Compose é uma ferramenta que auxilia na declaração e no compartilhamento de aplicações que são compostas por múltiplos containers.
- E é por isso que optamos por usar o Docker Compose nessa atividade, pois uma aplicação de WordPress em Docker não precisa somente de um container para o WordPress, mas também de um outro container para o MySQL.
