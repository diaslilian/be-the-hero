<h1 align="center">
    <img src="https://user-images.githubusercontent.com/47895394/77856815-279da300-71d0-11ea-8823-23344010cc71.png" width="30%"></img> 
    <br>

<h4>Na semana OmniStack 11.0 foi desenvolvida a aplicação que liga pessoas com vontade de ajudar organizações não governamentais (ONGs).
</h4>

Como existem ONGs com baixa visibilidade, a ideia social para esta aplicação é tornar cada vez mais acessivel o conhecimento sobre as ONGs existentes, seja no bairro, cidade, estado ou país. Possíbilitando a interação entre pessoas comuns e as necessidades de cada ONG.

Stack utilizada **_NodeJS, ReactJS e React Native + Expo_**.

![bethehero](https://user-images.githubusercontent.com/47895394/77863381-5596dd80-71f8-11ea-8134-4767fad283ab.png)

### :books: Layout

Acessar o layout da aplicação utilizando a ferramenta - [Figma](https://www.figma.com/file/2C2yvw7jsCOGmaNUDftX9n/Be-The-Hero-OmniStack-11?node-id=0%3A1).

## :rocket: Tecnologias

### API

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [nodemon](http://nodemon.io)
- [knex](https://knexjs.org)
- [sqlite3](https://github.com/mapbox/node-sqlite3)
- [Jest](https://jestjs.io/)

### WEB

- [ReactJS](https://reactjs.org/)
- [schema-utils](https://github.com/webpack/schema-utils)
- [Axios](https://github.com/axios/axios)

### MOBILE

- [React Native](http://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [Axios](https://github.com/axios/axios)

## :information_source: COMO USAR:

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v10.16](nodejs) or higher + [Yarn v1.13](yarn) or higher installed on your computer. From your command line:

### **Clonar o repositório**

```bash
# Clone this repository
$ git clone https://github.com/diaslilian/be-the-hero

# Go into the repository
$ cd be-the-hero
```

### **API**

> Logo após clonar o repositório navegue ate a pasta backend e execute o comando yarn install ou npm install.

```bash
# Go into backend
$ cd backend

# Install dependencies
$ npm install

# Run Migrates
$ yarn knex migrate:latest

# Start the backend server
$ npm start
```

### WEB

> Após seguir os passos acima e o backend está funcionando vá para pasta web.

> Depois das dependências terminarem de instalar execute o comando yarn start ou npm run start.

```bash
# Go into frontend
$ cd frontend

# Install dependencies
$ yarn install

# Start the frontend
$ yarn start
```

### :eyes: **Visualizar no navegador**

The frontend will start on

> http://localhost:3333

### MOBILE

> Para executar o mobile entre na pasta do mobile logo após o backend estar funcionando execute yarn install ou npm install.

> Após as dependências terminarem de baixar execute yarn start ou npm start. O expo já estará funcionando para você ler o Qr Code e utilizar a aplicação.

```bash
# On another terminal, go to the mobile folder
$ cd mobile

# Install dependencies
$ yarn install

# Start the expo server
$ yarn start
```

<br><br>

<hr>

Created by Lilian Dias :wave: [Hi-5!](https://www.linkedin.com/in/dias-lilian/)
