# GameStore Application

Welcome to the GameStore Application! This is a basic application designed to manage a collection of games. It allows users to browse, add, update, and delete games from the store.

## Features

Browse Games: View a list of available games in the store.

Add Games: Add new games to the store with details like name, genre, and price.

Update Games: Modify existing game details.

Delete Games: Remove games from the store.

## Technologies Used

Backend: .NET Core

Other Tools: Git, Visual Studio, etc.

## Getting Started

Follow these steps to set up and run the GameStore application on your local machine.

## Prerequisites

.NET Core SDK (version 6.0 or later)

(Optional) A code editor like Visual Studio or Visual Studio Code

## Installation

Clone the Repository:

git clone https://github.com/Subham-Bose/gamestore-application.git
cd gamestore-application
Restore Dependencies:

dotnet restore
Run the Application:

dotnet run
Access the Application:
Open your browser and navigate to http://localhost:5000 (or the port specified in the output).

## Project Structure

gamestore-application/
├── Controllers/ # API controllers
├── Models/ # Data models
├── Services/ # Business logic
├── Data/ # Database context and migrations
├── appsettings.json # Configuration file
├── Program.cs # Entry point
└── README.md # Project documentation
API Endpoints
Here are the available API endpoints for the GameStore application:

GET /api/games: Get a list of all games.

GET /api/games/{id}: Get details of a specific game by ID.

POST /api/games: Add a new game.

PUT /api/games/{id}: Update an existing game.

DELETE /api/games/{id}: Delete a game.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes.

Push your branch and submit a pull request.

## Acknowledgments

# Thanks to the .NET Core team for providing an excellent framework.

## Inspired by basic CRUD applications for learning purposes.
