# PaletteBuds

- This project provides an easy way to create and view stylish color palettes and also lets you have fun making them.

- You can create palettes which are stored in the browser in case you want to come back to them later.

- To get started, access the [site](https://palettebuds.netlify.app/) here.

## Usage

Access the [site](https://palettebuds.netlify.app/) here and get ready to make some palettes!

## Tech Stack

### Client

- The client is a TypeScript + React + Redux web application styled with Material UI Components hosted on Netlify.

- To store palettes for future use, the localStorage API is used to store them client side and React Router handles routing.

- ChromaJS and React Color are used for color conversion and generation and additional styles are in SASS modules.

### Server

- The server is built with TypeScript and Node and uses the Express framework to handle routes to create the API.

- The original palettes are hosted and fetched on a MongoDB Atlas Cluster with the Mongoose ORM and the server is hosted on a Heroku Dyno.

## Future Plans

- ⬜️ Integrate Redux into PaletteBuds (ongoing)

- ⬜️ Add user authentication and account based storage of palettes

- ⬜️ Allow users to publicly share certain palettes via a dynamic link
