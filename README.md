# Pokemon API coding exercise

### Task assignment

We have provided you with Pokemon data in a json file. Your mission is to create a database and expose the database to an API. Basically, you need to:

- Design the database to store information for the Pokemon data
- Load the database with the data
- Implement the API Interface with the following features:
  - Query pokemons with the options:
    - Pagination
    - Search by name
    - Filter by pokemon type
    - Filter by favorite
  - Query a pokemon by id
  - Query a pokemon by name
  - Query list of pokemon types
  - Mutation to mark/unmark pokemon as favorite
- Test are important and if time allows it, we'd like to see some test coverage

##### Technology

Remember that our technology stack is:

- Node.js (Typescript, Fastify)
- GraphQL (Nexus)
- PostgreSQL (Objection.js)

You can use the framework that you prefer, but please write the challenge in JS or TS. You can choose PostgreSQL / MongoDB like database, be free but take in consideration the best database to store the data.

### Getting started

You can run this project locally using docker: `docker compose -up`
