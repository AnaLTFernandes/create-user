# 👥 Create User

![Badge Finalizado](https://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=success&style=for-the-badge)

## Índice

- [Sobre](#Sobre)
- [Como rodar em desenvolvimento](#Como-rodar-em-desenvolvimento)

<br/>

## Sobre
Site simples para cadastrar usuários.

<br />

## :hammer_and_wrench: Como rodar em desenvolvimento

**Atenção:** para rodar o projeto é preciso ter o [Docker](https://docs.docker.com/engine/install/) e o [Docker Compose](https://docs.docker.com/compose/install/) instalado na sua máquina.

1. Clone esse repositório:

   > ```bash
   > git clone https://github.com/anatfernandes/create-user.git
   > ```

2. Configure o arquivo `.env` do front-end e do back-end utilizando como base seus respectivos arquivos `.env.example`

3. Inicie o projeto:

   > ```bash
   > docker-compose up --build
   > ```

4. Acesse http://localhost:8080 no seu navegador e aproveite <3

5. [*Opcional*] Acesse http://localhost:8080/api para usar somente o back-end
