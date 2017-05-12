# Adopt A Kitten

AdoptAKitten is a school project about making a REST API to adopt poor little kittens !

Contributors : Poch & Maxime !!

## Requirements
- MongoDB

## installation
- clone repository
- install dependencies with `npm install`
- build app with `npm run build`
- duplicate `config/config_sample.json` to `config/config.json` and set your db infos

## Usage
- launch MongoDB

### Browser
- launch server with `npm start` and go to `http://localhost:3000`

### API
- get all kittens : GET `http://localhost:3000/kittens`
- get one kitten : GET `http://localhost:3000/kittens/:id`
- add a kitten : POST `http://localhost:3000/add`
- update a kitten : PUT `http://localhost:3000/kittens/:id`
- delete a kitten : DELETE `http://localhost:3000/kittens/:id`