# Travel Buddy App

Travel Buddy is a web application designed to help users discover nearby places to travel. It utilizes geolocation to find the nearest places and allows users to add them to their favorites list.

## Features

- **Nearby Places**: Displays a list of nearby places based on the user's current location.
- **Favorites List**: Users can add places to their favorites list for quick access.
- **Simple Interface**: Clean and intuitive user interface designed for ease of use.

## Technologies Used

- **Frontend**:

  - Vite
  - Vanilla React
  - HTML5/CSS3

- **Backend**:
  - Node.js
  - Express.js

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/enesctnn/Travel_Buddy
   ```

2. Navigate to the project directory:

   ```bash
   cd Travel_Buddy
   ```

3. Install dependencies for frontend:

   ```bash
   npm install
   ```

4. Install dependencies for backend:

   ```bash
   cd backend
   npm install
   ```

## Usage

1. Start the backend server:

   ```bash
   cd backend
   node app.js
   ```

   The backend server will start running on `http://localhost:3000`.

2. Start the frontend development server:

   ```bash
   npm run dev
   ```

   The frontend development server will start running on `http://localhost:5173`.

3. Open your web browser and go to `http://localhost:5173` to access the Travel Buddy app.

Sure, here's a simplified version with just the dependencies and devDependencies:

---

## Dependencies

- **react**: [![npm](https://img.shields.io/npm/v/react)](https://www.npmjs.com/package/react)
- **react-dom**: [![npm](https://img.shields.io/npm/v/react-dom)](https://www.npmjs.com/package/react-dom)

## Dev Dependencies

- **@types/react**: [![npm](https://img.shields.io/npm/v/@types/react)](https://www.npmjs.com/package/@types/react)
- **@types/react-dom**: [![npm](https://img.shields.io/npm/v/@types/react-dom)](https://www.npmjs.com/package/@types/react-dom)
- **@vitejs/plugin-react**: [![npm](https://img.shields.io/npm/v/@vitejs/plugin-react)](https://www.npmjs.com/package/@vitejs/plugin-react)
- **eslint**: [![npm](https://img.shields.io/npm/v/eslint)](https://www.npmjs.com/package/eslint)
- **eslint-plugin-react**: [![npm](https://img.shields.io/npm/v/eslint-plugin-react)](https://www.npmjs.com/package/eslint-plugin-react)
- **eslint-plugin-react-hooks**: [![npm](https://img.shields.io/npm/v/eslint-plugin-react-hooks)](https://www.npmjs.com/package/eslint-plugin-react-hooks)
- **eslint-plugin-react-refresh**: [![npm](https://img.shields.io/npm/v/eslint-plugin-react-refresh)](https://www.npmjs.com/package/eslint-plugin-react-refresh)
- **vite**: [![npm](https://img.shields.io/npm/v/vite)](https://www.npmjs.com/package/vite)

## API Endpoints

- **GET /places**: Retrieves a list of places with their details including id, title, image, latitude, and longitude.
- **GET /user-places**: Retrieves the user's favorites list.
- **PUT /user-places**: Adds a place to the user's favorites list.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## Acknowledgements

- This project was inspired by the desire to help travelers find interesting places nearby.
- Thanks to [Vite](https://vitejs.dev/), [React](https://reactjs.org/), [Node.js](https://nodejs.org/), and [Express.js](https://expressjs.com/) for making development easier.
