# typescript_graphQL_client
A little client application that reads data from graphQL server with a complete data typization. Realized following this tutorial on Prisma blog: https://www.prisma.io/blog/e2e-type-safety-graphql-react-1-I2GxIfxkSZ

GraphQL Codegen will generate TypeScript types and query helpers in your React project based off of your GraphQL schema and the queries you write in your frontend application.

So the entire flow of types across your application will be as follows:

    Prisma will generate types based off of your database schema.
    Pothos will use those types to expose GraphQL types via an API.
    GraphQL Codegen will read your GraphQL schema and generate types for your frontend codebase representing what is available via the API and how to interact with it.

# How to run

Clone the project in a specific folder, then run the commands "npm install" and "npm run dev" to run the application.
NOTE: if you don't run the server app no data will displayed in the index page served by this client.
