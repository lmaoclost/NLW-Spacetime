# NextLevelWeek Spacetime

<div align="center">
  <img alt="Happy" src="https://github.com/lmaoclost/NLW-Spacetime/blob/main/web/src/assets/nlw-spacetime-logo.svg" width="280"/>
</div>

<div align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-191A1E">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>

  <a href="https://www.linkedin.com/in/renansmoliveira/">
    <img alt="Follow me Linkedin" src="https://img.shields.io/badge/Follow%20up-renansmoliveira-191A1E?style=social&logo=linkedin">
  </a>
</div>

Project for a [Course](https://github.com/rocketseat-education/nlw-12-spacetime-ignite) that has the purpose to code a project named Spacetime using Fastify, ReactJS, NextJS and React Native.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

Node, npm or yarn and a text editor. I'm using VSCode.

## FrontEnd

Open a terminal.

```
$ cd /web
$ npm install
$ npm run dev
```

Go to http://localhost:3000 and the project is up and running! To use the backend, make sure that it is running.

## BackEnd

Go to another terminal.

```
$ cd /server
$ npm install
$ npx prisma migrate
$ npm run dev
```

The Backend will be running in the http://localhost:3333. To test the routes, i'm leaving this [Insomnia file](https://github.com/lmaoclost/NextLevelWeek-3/blob/main/backend/Insomnia_2020-10-16).

## Mobile

I'm using Expo, so make sure that you have it. Go to [Api.ts](https://github.com/lmaoclost/NLW-Spacetime/blob/main/mobile/src/lib/api.ts) and change the baseURL to the server IP. If you're running the backend on localhost, the IP has the one in the expo page.

```
$ cd /mobile
$ npm i
$ npm start
```

Go to the expo page and connect.

## Built With

- [Typescript](https://devdocs.io/typescript/) - Main Language
- [Fastify](https://www.fastify.io/) - Web framework for Node
- [Nextjs](https://nextjs.org/) - JS framework for WEB
- [React Native](https://facebook.github.io/react-native/) - JS framework for APPs
- [Prisma](https://www.prisma.io/) - Typescript ORM
- [SQLite](https://www.sqlite.org/index.html) - Database
- [Expo](https://expo.io/) - Used to improve the app development

## Authors

- **Renan Oliveira** - [GitHub](https://github.com/lmaoclost), [LinkedIn](https://www.linkedin.com/in/renansmoliveira/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Made with ❤️ by Renan Oliveira.
