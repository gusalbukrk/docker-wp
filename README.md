# Compass - Atividade de Docker

## Instalação do Docker no Windows

## Instalação do WordPress & MySQL usando o Docker

### Instruções

1. crie uma pasta com um nome qualquer (por example, `docker-wp`) e em uma localidade de fácil acesso
2. abra o PowerShell e use o comando `cd` para mudar de diretório e fazer com que a pasta criada no passo anterior se torne o *working directory*
3. faça o download do arquivo [`docker-compose.yml`](docker-compose.yml) e use o comando `move` para mover esse arquivo da pasta `Downloads` para o *working directory* configurado no passo anterior
4. execute o commando `docker compose up` para criar e inicializar os containers
5. aguarde os containers serem inicializados e quando o terminal ficar inativo por alguns segundos e o último log conter "ready for connections", você poderá começar a usar o WordPress a partir do [localhost:80](http://localhost:80)

### Por que escolhemos o **Docker Compose**?

O Docker Compose é uma ferramenta que auxilia na declaração, compartilhamento e execução de aplicações que são compostas por múltiplos containers. E é por isso que optamos por usar o Docker Compose nessa atividade, pois uma aplicação de WordPress em Docker não precisa somente de um container para o WordPress, mas também de um outro container para o MySQL.

## Referências

- [Quickstart: Compose and WordPress](https://docs.docker.com/samples/wordpress/)
- [Compose file version 3 reference](https://docs.docker.com/compose/compose-file/compose-file-v3/)
- [The Complete Guide to Docker Secrets](https://earthly.dev/blog/docker-secrets/)
