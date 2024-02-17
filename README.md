# Pokemon Explorer (Web Application)

Welcome to the Pokedex Web Application repository! This application allows users to browse through a list of Pokémon, view details about each Pokémon, and search for specific Pokémon by name.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Pokémon List**: Browse through a list of Pokémon.
- **Pokémon Details**: View detailed information about each Pokémon, including their image, height, weight, and types.
- **Search Functionality**: Search for Pokémon by name.
- **Pagination**: Navigate through pages of Pokémon.

## Installation

To run this application locally, follow these steps:

1. Clone this repository to your local machine using `git clone https://github.com/SwapnilVG/Pokemon-Explorer.git`.
2. Navigate into the project directory: `cd pokedex`.
3. Install dependencies by running `npm install`.
4. Start the development server with `npm start`.
5. Open your browser and visit `http://localhost:3000` to view the application.

## Usage

Once the application is running, you can:

- Browse through the list of Pokémon.
- Click on a Pokémon to view its details.
- Use the search bar to search for specific Pokémon by name.
- Navigate through pages of Pokémon using the pagination controls.

## Folder Structure

The project structure is organized as follows:
    ```bash
        pokedex-web-app/
        ├── src/
        │ ├── components/
        │ │ ├── Pokedex/
        │ │ │ ├── Pokedex.js
        │ │ │ ├── Pokedex.css
        │ │ ├── PokemonList/
        │ │ │ ├── PokemonList.js
        │ │ │ ├── PokemonList.css
        │ │ ├── PokemonDetails/
        │ │ │ ├── PokemonDetails.js
        │ │ │ ├── PokemonDetails.css
        │ │ ├── Pokemon/
        │ │ │ ├── Pokemon.js
        │ │ │ ├── Pokemon.css
        │ │ ├── Search/
        │ │ │ ├── Search.js
        │ │ │ ├── Search.css
        │ ├── hooks/
        │ │ ├── usePokemonList.js
        │ │ ├── usePokemonDetails.js
        │ │ ├── useDebounce.js
        │ ├── routes/
        │ │ ├── CustomRoutes.js
        │ ├── App.js
        ├── package.json
        ├── README.md



## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
