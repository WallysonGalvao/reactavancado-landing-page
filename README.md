<h1 align="center">
    <a href="https://reactavancado.com.br/" target="_blank">
      <img alt="Logo React Avançado" title="#reactavancado" src=".github/logo.svg" width="250px" />
    </a>
</h1>

<h4 align="center">
  🚀 React Avançado Landing Page
</h4>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/WallysonGalvao/reactavancado-landing-page">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/WallysonGalvao/reactavancado-landing-page">

  <a href="https://github.com/WallysonGalvao/reactavancado-landing-page/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/WallysonGalvao/reactavancado-landing-page">
  </a>

  <a href="https://github.com/WallysonGalvao/reactavancado-landing-page/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/WallysonGalvao/reactavancado-landing-page">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-executando">Executando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>
<br>

## 💻 Projeto

Esse projeto foi dado como conteúdo extra no curso [React Avançado](https://reactavancado.com.br/), a inenção era ter um primeiro contato com o Strapi. O projeto é a própria landing page do curso.

## 🎨 Layout

Você pode encontrar o layout nesse link: https://reactavancado.com.br/

## :rocket: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Typescript](https://www.typescriptlang.org/)
- [ReactJS](https://pt-br.reactjs.org/)
- [NextJS](https://nextjs.org/)
- [GraphQL](https://graphql.org/)
- [Strapi](https://strapi.io/)

## :notebook: Executando

### Backend

```bash
# Clone este repositório
$ git clone https://github.com/WallysonGalvao/reactavancado-landing-page.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd backend

# Instale as dependências
$ yarn install

# Execute a aplicação
$ yarn develop

# Será disponibilizado o endereço: http://localhost:1337/
```

### Database

Esse projeto foi configurado com o banco PostgresSQL, dentro da pasta **reactavancado-landing-page/backend** há um arquivo **strapi.sql**, é um script/dump, utilze ele para popular o banco de dados. Abaixo alguns possiveis comandos:

```bash
# Caso tenha uma imagem em docker com o PostgresSQL
$ docker exec -i <postgres_container_name> psql -U <database_user_name> -d <database_name> < strapi.sql

# Caso tenha instaldo o PostgresSQL diretamente na máquina
$ psql -h 127.0.0.1 -U <database_user_name> -d <database_name> -W < strapi.sql
```

### Frontend

```bash
# Clone este repositório
$ git clone https://github.com/WallysonGalvao/reactavancado-landing-page.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd frontend

# Instale as dependências
$ yarn install

# Execute a aplicação
$ yarn dev

# Será disponibilizado o endereço: http://localhost:3000/
```

Se desejar, pode rodar os testes do projeto:

```bash
$ yarn test
```

---

Feito com horas em frente ao :computer: por [Wallyson Galvão](https://www.linkedin.com/in/wallyson-galvao/)
