<h1 align="center">
 <img alt="GamePlay" height="80" width="300" title="Plant Manager" src="./src/assets/images/logo.svg" />
</h1>

![cover](./src/assets/images/screencapture-letmeask.png)

## Aplicação

Aplicação desenvolvida na NLW Together da Rocketseat, um evento online feito com o propósito de disseminar conhecimento e despertar a curiosidade, para criação de salas de Q&A para ser usado em lives, onde os usuários podem dar likes na perguntas que gostariam que fossem respondidades pela pessoa que está fazendo a live.

## Features

- Autenticar com a conta do Google utilizando Firebase
- Obter informações usuário da conta Google (username e avatar)
- Usuário comum tem acesso a sala, podendo dar likes na própria pergunta e/ou de  outros usuários
- Usuário que cria a sala tem acesso como admin e pode dar destaque na pergunta para mostrar que está respondendo a mesma, marcar a pergunta como respondida e remover pergunta
- Na sala de perguntas caso o usuário ainda não estiver conectado, pode se autenticar e manter na sala
- Usuário admin pode encerrar a sala
- função de copiar código tanto para usuário admin quanto para usuário comum.

## Tecnologias

- React
- Typescript
- Firebase (Autenticação e Realtime Database)
- Context Api
- Sass
- Classnames

## Executando o projeto

Utilize o **yarn** ou o **npm install** para instalar as dependências do projeto. Em seguida, inicie o projeto.

```
yarn start
```

Lembre-se de obter as credencias no Firabase e renomeie o arquivo .env.example para .env.local.

```
REACT_APP_API_KEY = ""
REACT_APP_AUTH_DOMAIN = ""
REACT_APP_DATABASE_URL = ""
REACT_APP_PROJECT_ID = ""
REACT_APP_STORAGE_BUCKET = ""
REACT_APP_MESSAGING_SENDER_ID = ""
REACT_APP_APP_ID = ""
```

### Projeto desenvolvido por

[![Linkedin Badge](https://img.shields.io/badge/-Igor%20Saturnino-9466FF?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/igornascimentosaturnino/)](https://www.linkedin.com/in/igornascimentosaturnino/)

### Projeto original

[![Linkedin Badge](https://img.shields.io/badge/-Rocketseat-9466FF?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/school/rocketseat/)](https://www.linkedin.com/school/rocketseat/)

