# WorldWise

WorldWise is a React app that helps you track your travels and create a visual record of your adventures. Explore cities worldwide, mark your footsteps on a global map, and preserve your memories to share with friends.

---

## Deployed Version

Live demo of WorldWise (Feel free to visit) 👉🏻 : https://worldwise-2025.netlify.app/

---

## Key Features

- View a list of cities and their locations on a map.
- Click on a city marker to see detailed information about the city.
- Create a new city by providing its details.
- Delete a city from the list.

## Prerequisites

Before running the WorldWise application, ensure you have the following dependencies installed:

- [Node.js](https://nodejs.org) (version 14 or higher)

## Installation

1. Clone the repository:

```shell
git clone https://github.com/AhmedSalman1/WorldWise.git
```

2. Change into the project directory:

```shell
cd worldwise
```

3. Install the dependencies:

```shell
npm install
```

## Configuration

The WorldWise application uses a JSON server to provide city data. By default, the server is configured to run on `http://localhost:8000`. If you need to change the server URL, modify the `BASE_URL` constant in the `CitiesProvider` component located in `src/providers/CitiesProvider.js`.

## Usage

1. Start the JSON server to serve the city data:

```shell
npm run server
```

2. Start the development server:

```shell
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000` to access the WorldWise application.

## Authentication

The WorldWise application includes authentication functionality. You can log in using the following credentials:

- Email: `test@example.com`
- Password: `qwerty`

## Available Scripts

In the project directory, you can run the following scripts:

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the application for production.
- `npm run lint`: Runs the ESLint linter to check for code quality and style issues.
- `npm run preview`: Serves the production build locally for preview.
- `npm run server`: Starts the JSON server to serve city data.

## Acknowledgements

The WorldWise application uses the following open-source libraries:

- [React](https://reactjs.org)
- [React Router](https://reactrouter.com)
- [Leaflet](https://leafletjs.com)
- [React Leaflet](https://react-leaflet.js.org)
- [React DatePicker](https://github.com/Hacker0x01/react-datepicker)
- [JSON Server](https://github.com/typicode/json-server)
- [ESLint](https://eslint.org)


Thank you for using WorldWise!
