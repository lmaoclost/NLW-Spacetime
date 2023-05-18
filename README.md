# NextLevelWeek Spacetime

<div align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-191A1E">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>

  <a href="https://www.linkedin.com/in/renansmoliveira/">
    <img alt="Follow me Linkedin" src="https://img.shields.io/badge/Follow%20up-renansmoliveira-191A1E?style=social&logo=linkedin">
  </a>
</div>

Project for a [Course](https://github.com/rocketseat-education/nlw-12-spacetime-ignite) that has the purpose to code a project named Spacetime using Fastify, ReactJS, Next and React Native.

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

The Backend will be running in the http://localhost:3333. To test the routes, i'm leaving this [Insomnia file](https://github.com/lmaoclost/NextLevelWeek-3/blob/main/backend/Insomnia_2020-10-16). Make sure that you change the baseURL inside [images_view.ts](https://github.com/lmaoclost/NextLevelWeek-3/blob/main/backend/src/views/images_view.ts) so the images can be displayed correctly in mobile.

## Mobile

I'm using Expo, so make sure that you have it. Go to [Api.ts](https://github.com/lmaoclost/NextLevelWeek-3/blob/master/mobile/src/services/api.ts) and change the baseURL to the server IP. If you're running the backend on localhost, the IP has the one in the expo page.

```
$ cd /mobile
$ npm i
$ npm start
```

Go to the expo page and connect.

## Built With

- [Typescript](https://devdocs.io/typescript/) - Main Language
- [Node.js](https://nodejs.org/en/) - Backend framework
- [React.js](https://reactjs.org/) - JS framework for WEB
- [React Native](https://facebook.github.io/react-native/) - JS framework for APPs
- [TypeORM](https://typeorm.io/) - Typescript ORM
- [SQLite](https://www.sqlite.org/index.html) - Database
- [Expo](https://expo.io/) - Used to improve the app development

## Authors

- **Renan Oliveira** - [GitHub](https://github.com/lmaoclost), [LinkedIn](https://www.linkedin.com/in/renansmoliveira/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Made with ❤️ by Renan Oliveira.
