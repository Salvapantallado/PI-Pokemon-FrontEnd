# PI-Pokemon-FrontEnd

FrontEnd of my personal project for coding bootcamp SoyHenry. I had to use the following technologies:

- Sequelize
- Express.js
- PostgreSQL (which is allocated at Heroku's database plugin)

Also, all the dogs' information had to come from <a href="https://pokeapi.com/">PokeAPI</a> and store in database the necessary information (such as all the pokemon types and custom pokemons created by the user)

# How to start on local

1- Open your bash terminal

2- Write "npm install"

3- Wait for completation, then write "npm start"

This must be done for the <a href="https://github.com/Salvapantallado/PI-Pokemon-BackEnd">BackEnd</a> of this project as well

# Front End Known Issues

- When realoading in a dog detail route, the component does not recieve the information needed and crashes the app
- Filter options not showing as intended (Temporally fixed with reset button)

# What to do at this app

- You can search for pokemon along their types and find information about them!
- Filters by name and types are available (It was a requirement for approval not to use API endpoints).
- Sorting by origin, strength and alphabetically (It was a requirement for approval not to use API endpoints).
