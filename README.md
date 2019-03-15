# Luno Maps

Web app using Google Maps API, to create custom maps with personalized  pins. 

## Getting Started

1. Set up postgresql database
2. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
3. Update the .env file with your correct local information
4. Install dependencies: `npm i`
5. Run migrations: `npm run knex migrate:latest`
6. Run the seed: `npm run knex seed:run`
7. Run the server: `npm run local`
8. Visit `http://localhost:8080/`

## Dependencies

- cookie-session
- ejs
- express
- knex
- dotenv
- node-sass-middleware
