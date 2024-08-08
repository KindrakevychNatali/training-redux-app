
# Training Redux App

### Overview

**`Redux App`** is a simple React application designed to demonstrate the usage of React along with Redux for state management. The application is bootstrapped with `create-react-app` and includes basic testing utilities provided by the `@testing-library`.

### Features

- **`React 18`**: The app is built using the latest version of React, taking advantage of its new features.
- **`Testing`**: Includes testing utilities like `@testing-library/react` and `@testing-library/jest-dom` for unit testing.
- **`Fast Development`**: Integrated with `react-scripts` for zero-config setup, making it easy to start coding right away.

### Getting Started

### Prerequisites

Ensure that you have [Node.js](https://nodejs.org/) installed on your local machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/KindrakevychNatali/training-redux-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd training-redux-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

### Running the App

To start the development server:

```bash
npm start
```

This will open the app in your default web browser at `http://localhost:3000`.

### Building the App

To create a production build of the app:

```bash
npm run build
```

The build will be optimized for production and output to the `build` directory.

### Running Tests

To run the tests:

```bash
npm test
```

This will run all the unit tests using Jest and React Testing Library.

## Project Structure

The project structure is as follows:

```
training-redux-app/
├── public/                # Public assets
├── src/                   # Source files
│   ├── components/        # React components
│   ├── store/             # Redux store and slices
│   ├── App.js             # Main App component
│   ├── index.js           # Entry point
│   └── ...                # Other files
├── .gitignore             # Git ignore file
├── package.json           # NPM dependencies and scripts
└── README.md              # Project documentation
```

## Available Scripts

In the project directory, you can run:

- **`npm start`**: Runs the app in development mode.
- **`npm run build`**: Builds the app for production.
- **`npm test`**: Runs the test suite.
- **`npm run eject`**: Ejects the app, exposing the configuration files.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Create React App](https://github.com/facebook/create-react-app)

---
```
