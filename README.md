# Superheroes API

Superheroes API is a powerful Flask-based RESTful API designed to manage superhero profiles and their superpowers. This API integrates seamlessly with a React frontend, providing an intuitive interface for users to interact with superhero data.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Features](#features)
- [Models](#models)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Overview

This API serves as the backend for a superhero management system. It provides a structured way to create, retrieve, update, and delete superhero and superpower records. The API is designed with flexibility and extensibility in mind, making it suitable for a wide range of superhero-themed applications.

## Getting Started

To set up Superheroes API and start working on your superhero project, follow these steps:

1. **Install Dependencies**: Begin by installing the necessary dependencies for both the frontend and backend. Run the following command:

    ```bash
    npm install
    ```

2. **Database Models**: Generate the database models required for your application using the provided database migration tools.

3. **Sample Data**: Create sample data to test your application using the `app/seed.py` file.

4. **Run the Backend**: Launch the Flask API locally by executing the following command:

    ```bash
    flask run
    ```

5. **Run the Frontend**: Start the React app on your localhost by running:

    ```bash
    npm start
    ```

## Features

Superheroes API offers a variety of features to help you manage your superhero data efficiently:

- **Retrieve Superheroes**: Use `GET /heroes` to fetch a list of all superheroes.
- **Get Hero Details**: Access specific superhero details with `GET /heroes/:id`.
- **List Superpowers**: Retrieve a list of all available superpowers using `GET /powers`.
- **Superpower Details**: Get detailed information about a specific superpower with `GET /powers/:id`.
- **Associate Heroes and Powers**: Create associations between superheroes and superpowers with `POST /hero_powers`.

## Models

The application is built around the following key data models:

- **Hero**: Represents a superhero with attributes `name` and `super_name`.
- **Power**: Represents a superpower with attributes `name` and `description`.
- **HeroPower**: Represents the association between a superhero and a superpower, including a `strength` level.

## Testing

You can verify your progress and ensure code quality with the following testing methods:

- **Automated Tests**: Execute `pytest -x` to run automated tests and check if your code meets the required criteria.
- **Frontend Testing**: Open the React application in your web browser and interact with the API through the frontend.
- **API Testing**: Run the Flask server and use tools like Postman to make API requests and validate the responses.

## Contributing

Contributions to Superheroes API are welcome! To contribute, follow these steps:

1. Fork the repository to your GitHub account.
2. Create a new branch for your contributions.
3. Make changes and improvements.
4. Commit your changes with clear and descriptive messages.
5. Push your changes to your branch.
6. Create a pull request to submit your contributions for review.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as needed for your superhero-themed applications.

Happy coding, superhero enthusiasts! 🚀
