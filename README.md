## Usage

1. `cd frontend` and create a .env file with `API_URL=http://localhost:3000/api` and 
`NODE_ENV=dev`
Do an `npm i` from this directory, and then run `npm run watch` to start webpack and react 
2. `cd backend` and create a .env file with 
PORT=3000
DB_URL='mongodb://localhost:27017/costumes_prod' 
run `npm i` from this directory
3. In a 2nd terminal, `cd backend`, type `mkdir db`, and then run `mongod --dbpath=./db` to run mongo 
4. In a 3rd terminal, `cd backend`, then `npm start` to start the server

