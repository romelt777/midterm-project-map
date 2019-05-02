# Luno Maps

Users able to create maps. Create/edit/delete pins. Maps where users contributed are saved to their profile. Users are also able to favorite a map.

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

## Photos of Project

- Home Page
![](https://github.com/romelt777/midterm-project-map/blob/master/docs/Homepage.png)

- Explore Page
![](https://github.com/romelt777/midterm-project-map/blob/master/docs/ExplorePage.png)

- Viewing Map
![](https://github.com/romelt777/midterm-project-map/blob/master/docs/ViewMap.png)

- Profile Page
![](https://github.com/romelt777/midterm-project-map/blob/master/docs/wholeProfile.png)
