# Welcome to Flight service 

## Project Setup
- clone the project on your local
- Execute `npm install` on the same path as of your root direcrtory of the downloaded project
- create a `.env` file in the root direcotry and add the following environment variable

     - `PORT=4000`
- INSIDE THE `src/config` folder create a new file `config.json` and then add the following piece of json
```json
{
  "development": {
    "username": <YOUR_DB_LOGIN_NAME>,
    "password": <your_DB_PASSWORD>,
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}
```
- Once you've added your db config as listed above, go to the src folder from your terminal and execute `npx 
sequelize db:create`