# Commander
A simple REST API for saving common command line commands | Using ASP.NET Core 3.1 Web API and SQLite

## Installation

1. Clone the repository
2. Open the project in the terminal/command line and enter "dotnet run".

## Usage

| METHOD   | URL               | Description           |
|----------|-------------------|-----------------------|
| GET      | /api/commands     | Return all commands   |
| GET      | /api/commands/:id | Return single command |
| POST     | /api/commands     | Create a command      |
| PUT      | /api/commands/:id | Update command        |
| PATCH    | /api/commands/:id | Update command        |
| DELETE   | /api/commands/:id | Delete command        |
