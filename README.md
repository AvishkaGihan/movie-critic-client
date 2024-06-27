# MovieCritic Client

This is the client-side application for MovieCritic, a web application that allows users to browse and review movies. The client is built using React.js and communicates with the server-side API to fetch and display movie data.

## Features

- Browse a list of movies
- View details of a specific movie, including its trailer, synopsis, and reviews
- Leave reviews for movies

## Technologies Used

- React.js
- React Router
- Axios (for API requests)
- Bootstrap (for styling)

## Getting Started

To run the client locally, follow these steps:

1. Clone the repository:

   ```sh
   git clone https://github.com/your-repo/movie-client.git
   ```

2. Navigate to the project directory:

   ```sh
   cd movie-client
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

4. Start the development server:
   ```sh
   npm start
   ```

The application should now be running at `http://localhost:3000`.

## Project Structure

- `src/components`: Contains reusable React components
- `src/api`: Contains the Axios configuration for making API requests
- `src/App.js`: The main entry point of the application
- `src/index.js`: Renders the React application

## Environment Variables

The client application expects the following environment variable to be set:

- `REACT_APP_API_BASE_URL`: The base URL of the server-side API

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
