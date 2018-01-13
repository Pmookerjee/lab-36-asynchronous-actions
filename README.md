## Usage

1. `cd frontend` and create a .env file with `API_URL=http://localhost:3000`
2. `cd backend` and create a .env file with 
PORT=3000
DB_URL='mongodb://localhost:27017/costumes_prod'
3. In a terminal, `cd frontend`, then `npm run watch` to start webpack and react 
4. In a 2nd terminal, `cd backend`, type `mkdir db`, and then run `mongod --dbpath=./db` to run mongo 
5. In a 3rd terminal, `cd backend`, then `npm start` to start the server

