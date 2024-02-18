# GraphQL-API

This repository hosts a full-stack application consisting of a GraphQL API and a client-side application for interacting with the API. The API provides endpoints for querying todos and users, while the client application consumes these endpoints to display todo information along with user details.

## Features

### GraphQL API
- Implements a GraphQL API using Express and Apollo Server.
- Defines type definitions and resolvers for querying todos and users.
- Listens on port 8000 for incoming requests.
- Provides a flexible and efficient way to fetch data from the server.
- Supports only a single endpoint for data retrieval, reducing network overhead.

### Client Application
- Utilizes Apollo Client to interact with the GraphQL API.
- Queries todos with associated user information using the `useQuery` hook.
- Displays a table of todos with their titles and respective user names.
- Provides a "Loading..." message while data is being fetched.

## GraphQL Features
- **Declarative Data Fetching:** Clients can specify exactly what data they need from the server, reducing over-fetching and under-fetching of data.
- **Strongly Typed Schema:** GraphQL APIs are defined using a strong type system, allowing clients to understand the shape of the data they are receiving.
- **Single Endpoint:** GraphQL APIs typically expose a single endpoint, simplifying network requests and reducing overhead.
- **Real-time Updates:** GraphQL subscriptions enable real-time data updates, allowing clients to receive updates as soon as they occur on the server.

## Usage

1. Clone the repository or download the source code.
2. Install dependencies for both the server and client using `npm install`.
3. Start the server using `npm start` in the server folder.
4. Start the client application using `npm start` in the client folder.
5. Access the client application in your web browser to interact with the GraphQL API.

## File Structure

- `server/`: Folder containing server-side code for the GraphQL API.
  - `index.js`: Entry point for the GraphQL server setup.
  - `todo.js`: File containing todos data and resolvers.
  - `user.js`: File containing user data and resolvers.
- `client/`: Folder containing client-side code for interacting with the GraphQL API.
  - `App.js`: Main component for fetching and displaying todos with associated user information.

## Technologies Used

- Server: Express, Apollo Server
- Client: React, Apollo Client
- GraphQL: Declarative Query Language for APIs
