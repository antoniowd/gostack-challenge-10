<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" style="width: 100%;"/>

<h3 align="center">
  Challenge 10: GoRestaurant Web
</h3>

<blockquote align="center">“The time it takes to realize your dreams will pass anyway!”</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/Rocketseat/bootcamp-gostack-desafios/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rocketseat/bootcamp-gostack-desafios?style=social">
  </a>
</p>

## :rocket: About the challenge

In this challenge, you will develop another application, the GoRestaurant. Now you will practice what you've learned so far on React.js along with TypeScript, practicing the concept of CRUD (Create, Read, Update, Delete).

This will be an application that will connect to a fake API, and display the food dishes created and allow the creation, removal and update of these dishes.

### Setup a fake API

First of all, so that you have the data to display on screen, we created a file that you can use as a fake API to provide you with this data.

To do this, we leave installed in your package.json a dependency called `json-server`, and a file called `server.json` that contains the data for a /foods route. To run this server you can execute the following command:

`yarn json-server server.json -p 3333`

### Layout

[GoRestaurant web](https://www.figma.com/file/1lK6AVCPybtWeBLCH8B08N/GoRestaurant?node-id=0%3A1)

### Application requirements

- **GET /foods | List the food dishes in your API**: Your Dashboard page should be able to display a list, with the `title`, `value`, and `description` field available of all the food dishes that are registered in your API.

- **POST /foods | Add new food dishes to your API**: In your Dashboard page you must open a modal by clicking the New Dish button in the Header. This modal must be responsible for registering a new food by passing the fields `image`, `name`, `description`, `value`. You must send the `available` field with a value true as default.

- **PUT /food/:id | Edit food dishes from your API**: In your Dashboard page you must open a modal by clicking the Edit Dish button. This modal must be responsible for editing a food by passing the fields `image`, `name`, `description`, `value`.

- **DELETE /foods/:id | Remove food plates from your API**: On your Dashboard page you must remove a plate of food by clicking on the garbage can icon button in the Food component.

- **Change availability of food dishes from your API**: On your Dashboard page you must change the availability of a food dish by clicking on the switch that is controlled by the value of available.

## :memo: Licence

This project is under license from MIT. See the archive [LICENSE](LICENSE) to more details.

---

Made with 💜 by Rocketseat :wave: [Join our community!](https://discordapp.com/invite/gCRAFhc)
