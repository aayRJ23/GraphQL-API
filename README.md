# GraphQL API Repository

This repository hosts a GraphQL API server implemented with Express and Apollo Server, along with a client-side application built with React and Apollo Client.

## Features

- Implements a GraphQL API server with Express and Apollo Server to handle queries for todos and users.
- Provides a client-side application built with React and Apollo Client to interact with the GraphQL API and display todo information.
- Allows users to fetch todos along with associated user information and display them in a table format.
- Incorporates loading indicators to provide feedback while data is being fetched.

## Usage

1. Clone the repository or download the source code.
2. Navigate to the server folder and install server dependencies using `npm install`.
3. Start the server using `npm start` or the appropriate command.
4. Navigate to the client folder and install client dependencies using `npm install`.
5. Start the client application using `npm start` or the appropriate command.
6. Access the client application in your web browser to interact with the GraphQL API and view todo information.

## File Structure

- `server/`: Contains server-side files including the GraphQL API implementation with Express and Apollo Server.
  - `index.js`: Entry point for the GraphQL server setup.
  - `todo.js`: Defines type definitions and resolvers for querying todos.
  - `user.js`: Defines type definitions and resolvers for querying users.

- `client/`: Contains client-side files including the React application with Apollo Client integration.
  - `App.js`: Main component responsible for fetching and displaying todos with associated user information.

## Technologies Used

### Server
- Express
- Apollo Server
- GraphQL

### Client
- React
- Apollo Client
- GraphQL
