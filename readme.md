# GraphQL API with Prisma and SQLite - graphql-prisma

## Overview

This project is a GraphQL API built using Prisma and SQLite, designed for mastering GraphQL concepts. It provides a practical implementation of a GraphQL server with a SQLite database using Prisma as the data access layer.

## Features

1. **GraphQL Endpoint:** The API exposes a GraphQL endpoint for querying and mutating data.

2. **Prisma Integration:** Prisma is used as the GraphQL server's data access layer, providing a type-safe and auto-generated query builder for seamless database interactions.

3. **SQLite Database:** The project uses SQLite as the database engine, making it easy to set up and suitable for small to medium-sized applications.

## Prerequisites

Make sure you have the following installed before running the project:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Prisma CLI](https://www.prisma.io/docs/getting-started/installation)

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/bryan936M/graphql-prisma.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd graphql-prisma
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Set up the database:**

    ```bash
    npx prisma migrate dev
    ```

5. **Start the GraphQL server:**

    ```bash
    npm start
    ```

The GraphQL server should now be running at `http://localhost:4000`.

## Usage

- Open `http://localhost:4000` in your browser to access the GraphQL Playground.
- Explore the API using GraphQL queries and mutations.
- Refer to the generated Prisma client documentation for available models and queries.

## Project Structure

- **`prisma/`**: Contains Prisma configuration and migration files.
- **`src/`**: Holds the GraphQL server implementation.
  - **`schema/`**: GraphQL schema definition.
  - **`resolvers/`**: Resolver functions for handling GraphQL queries and mutations.

## Contributing

Feel free to contribute to the project by submitting issues or pull requests. Your feedback and improvements are highly appreciated!

## License

This project is licensed under the [MIT License](LICENSE).
