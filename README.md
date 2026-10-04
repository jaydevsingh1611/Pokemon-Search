# Pokémon Search

A responsive Pokémon search application built with React and Vite. The application fetches Pokémon data from the PokéAPI and displays detailed information in reusable Pokémon cards.

## Features

- Fetches Pokémon data from the PokéAPI
- Displays Pokémon in a responsive card layout
- Search Pokémon by name
- Shows Pokémon images and types
- Displays Pokémon height and weight
- Displays Pokémon speed, experience, and attack
- Shows Pokémon abilities
- Loading state while data is being fetched
- Error handling for failed API requests
- Interactive card hover effects
- Responsive grid-based layout

## Page Sections

### Header

The application includes a simple heading:

**Let's Catch Pokémon**

### Search

A search input allows users to filter the loaded Pokémon by name.

The search is case-insensitive and updates the displayed results as the user types.

### Pokémon Cards

Each Pokémon is displayed using a reusable card component.

The cards include:

- Pokémon image
- Pokémon name
- Pokémon type
- Height
- Weight
- Speed
- Base experience
- Attack
- Ability

## API

This project uses the PokéAPI to retrieve Pokémon data.

The application initially fetches 24 Pokémon and then retrieves detailed information for each Pokémon.

API endpoint:

```text
https://pokeapi.co/api/v2/pokemon?limit=24 
```
## Technologies Used

- React
- JavaScript
- Vite
- CSS3
- CSS Grid
- PokéAPI

## Project Structure

```text
pokemon/
├── public/
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── App.jsx
│   ├── App.css
│   ├── Pokemon.jsx
│   ├── PokemonCards.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
└── README.md
```
## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/jaydevsingh1611/Pokemon-Search.git
```
### 2. Open the Project
```bash
cd pokemon
```
### 3. Install Dependencies
```bash
npm install
```
### 4. Run the Development Server
```bash
npm run dev
```
Open the local URL shown in your terminal to view the application.
## Build for Production
To create a production build:
```bash
npm run build
```
To preview the production build:
```bash
npm run preview
```
## Search Functionality
The application stores the search input using React state and filters the fetched Pokémon based on their names.
For example:
```bash
Search: pikachu
Result: Pikachu
```
## Responsive Design
The application uses CSS Grid and responsive layouts to organize Pokémon cards across different screen sizes.
The interface includes:
- Multi-column card layout
- Flexible spacing
- Responsive content
- Interactive hover effects
- Scalable Pokémon images
## Components

### `Pokemon.jsx`

Responsible for:

- Fetching Pokémon data
- Managing loading and error states
- Managing the search input
- Filtering Pokémon
- Rendering Pokémon cards

### `PokemonCards.jsx`

A reusable component responsible for displaying individual Pokémon information.

### `App.jsx`

The main application component that renders the Pokémon application.

### `main.jsx`

The React entry point that mounts the application using `createRoot`.

## Author

**Jaydev Singh Chahar**

B.Tech — NIT Patna

- GitHub: [🐙 jaydevsingh1611](https://github.com/jaydevsingh1611)

## License

This project is intended for educational and portfolio purposes.