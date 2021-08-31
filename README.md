# PaletteBuds

- This project provides an easy way to create and view stylish color palettes and also lets you have fun making them.

- You can create palettes which are stored in the browser in case you want to come back to them later.

- To get started, access the [site](https://palettebuds.netlify.app/) here.

## Usage

Access the [site](https://palettebuds.netlify.app/) here and get ready to make some palettes!

## Tech Stack

### Client

- The client is a [TypeScript](https://www.typescriptlang.org/) + [React](https://reactjs.org/) + [Redux](https://redux.js.org/) web application styled with [Material UI Components](https://material-ui.com/) hosted on [Netlify](https://www.netlify.com/).

- To store palettes for future use, the [localStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) is used to store them client side and [React Router](https://reactrouter.com/) handles routing.

- [ChromaJS](https://gka.github.io/chroma.js/) and [React Color](https://casesandberg.github.io/react-color/) are used for color conversion and generation and additional styles are in SASS modules.

### Server

- The server is built with [TypeScript](https://www.typescriptlang.org/) and [Node](https://nodejs.org/en/) and uses the [Express](https://expressjs.com/) framework to handle routes to create the API.

- The original palettes are hosted and fetched on a [MongoDB Atlas Cluster](https://www.mongodb.com/cloud/atlas) with the [Mongoose ORM](https://mongoosejs.com/) and the server is hosted on a [Heroku Dyno](https://www.heroku.com/dynos).

## Future Plans

- ⬜️ Integrate Redux into PaletteBuds (ongoing)

- ⬜️ Add user authentication and account based storage of palettes

- ⬜️ Allow users to publicly share certain palettes via a dynamic link
