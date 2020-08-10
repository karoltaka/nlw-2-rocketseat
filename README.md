<p align="center">
   <img src=".github/logo.png" alt="Proffy" width="280"/>
</p>

<p align="center">	
  <a href="https://www.linkedin.com/in/karoline-takahagassi-b9ba4b1ab/">
    <img alt="Karoline Costa" src="https://img.shields.io/badge/-KarolineTakahagassi-8257E5?style=flat&logo=Linkedin&logoColor=white" />
  </a>

  <a href="mailto:takahagassi.dev@gmail.com">
    <img alt="Karoline Costa" src="https://img.shields.io/badge/-takahagassi.dev@gmail.com-8257E5?style=flat-square&logo=Gmail&logoColor=white" />
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/karoltaka/nlw-2-rocketseat?color=774DD6">

  <a aria-label="Completed" href="https://nextlevelweek.com/episodios/omnistack/edicao/2">
    <img src="https://img.shields.io/badge/Proffy-NLW 2.0-8257E5?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAALVBMVEVHcExxWsF0XMJzXMJxWcFsUsD///9jRrzY0u6Xh9Gsn9n39fyMecy0qd2bjNJWBT0WAAAABHRSTlMA2Do606wF2QAAAGlJREFUGJVdj1cWwCAIBLEsRU3uf9xobDH8+GZwUYi8i6ucJwrxKE+7D0G9Q4vlYqtmCSjndr4CgCgzlyFgfKfKCVO0LrPKjmiqMxGXkJwNnXskqWG+1oSM+BSwD8f29YLNjvx/OQrn+g99oQSoNmt3PgAAAABJRU5ErkJggg=="></img>
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-8257E5">
</p>

<div align="center">
   Projeto feito na Next Level Week 2 @Rocketseat
</div>

<p align="center">
  <img alt="mockup" src=".github/proffy.png" width="100%">
</p>

<p align="center">
  <a href="#clipboard-sobre-o-projeto">Sobre o Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#art-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-tecnologias-utilizadas">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-como-rodar-o-projeto">Como rodar o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#closed-book-licença">Licença</a>
</p>

## :clipboard: Sobre o Projeto

Criação do Proffy, uma plataforma para conexão entre professores e alunos.

## :art: Layout

Você pode duplicar o layout do projeto no Figma, ele está dividido em duas versões:

- <div style="display:flex;align-items:center;">
      Layout do projeto web <a href="https://www.figma.com/file/GHGS126t7WYjnPZdRKChJF/Proffy-Web/duplicate"> <img src="https://img.shields.io/badge/-Figma-rebeccapurple?&logo=Figma&logoColor=white&link" style="margin-left:8px;"/> </a>
  </div>

- <div style="display:flex;align-items:center;margin-top:12px;">
      Layout do projeto mobile <a href="https://www.figma.com/file/e33KvgUpFdunXxJjHnK7CG/Proffy-Mobile/duplicate"> <img src="https://img.shields.io/badge/-Figma-purple?&logo=Figma&logoColor=white&link" style="margin-left:8px;"/> </a>
  </div>

## :computer: Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- ReactJS
- React Native
- TypeScript
- Expo
- Express

## :rocket: Como rodar o projeto

Este projeto foi dividido em três partes:

1. Back End (pasta [backend](https://github.com/karoltaka/nlw-2-rocketseat/tree/master/backend))
2. Front End (pasta [web](https://github.com/karoltaka/nlw-2-rocketseat/tree/master/web))
3. Mobile (pasta [mobile](https://github.com/karoltaka/nlw-2-rocketseat/tree/master/mobile))

💡Tanto o Front End quanto o Mobile precisam que o Back End esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

- [Git](https://git-scm.com);
- [Node.js](https://nodejs.org/en/);
- [Editor de código](https://code.visualstudio.com/)

## Clonando o projeto

Comece realizando um clone deste projeto.

```bash
# Clone este repositório
$ git clone https://github.com/karoltaka/nlw-2-rocketseat.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd nlw-2-rocketseat
```

## Rodando o back end (servidor)

```bash
# Vá para a pasta da aplicação Back-End
$ cd backend

# Instale as dependências
$ yarn
# Ou use NPM se preferir
$ npm install

# Rode as migrations do banco de dados
$ yarn knex:migrate
# Ou use NPM
$ npm run knex:migrate

# Execute a aplicação em modo de desenvolvimento
$ yarn start
# Ou use NPM se preferir
$ npm run start

# A aplicação será aberta na porta:3333
```

### Rodando a aplicação web (Front End)

```bash
# Vá para a pasta da aplicação Front-End
$ cd web

# Instale as dependências
$ yarn
# Ou use NPM se preferir
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ yarn start
# Ou use NPM se preferir
$ npm run start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

### Rodando a aplicação mobile

```bash
# Vá para a pasta da aplicação Mobile
$ cd mobile

# Instale as dependências
$ yarn
# Ou use NPM se preferir
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ yarn start
# Ou use NPM se preferir
$ npm run start

# Instale o aplicativo Expo no seu celular
# Escaneie o QrCode para abrir a aplicação
```

## :closed_book: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/karoltaka/nlw-2-rocketseat/blob/master/LICENSE) para mais detalhes.
