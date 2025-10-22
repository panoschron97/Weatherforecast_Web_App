# Weatherforecast web app

## Project Description

The Weatherforecast Web App is a simple ASP.NET Core web application that provides a weather forecast API. It showcases a basic controller, model and configuration setup for a .NET web application. This project serves as a starting point for building more complex web services using .NET.

## Key Features

-   **Weather Forecast API**: Provides endpoints to retrieve sample weather forecasts.
-   **ASP.NET Core**: Utilizes the ASP.NET Core framework for building web applications.
-   **OpenAPI Support**: Includes OpenAPI (Swagger) integration for API documentation and testing.
-   **Configuration**: Demonstrates the use of `appsettings.json` for application configuration.

## Table of Contents

-   [Installation](#installation)
-   [Usage](#usage)
-   [Dependencies](#dependencies)

## Installation

1.  **Clone the Repository**

    ```bash
    git clone https://github.com/panoschron97/Weatherforecast_Web_App.git
    cd Weatherforecast_Web_App
    ```

2.  **Install .NET SDK**

    Ensure you have the .NET 9.0 SDK installed. You can download it from the [official .NET website](https://dotnet.microsoft.com/en-us/download).

## Usage

1.  **Navigate to the Project Directory**

    ```bash
    cd C#_ASP_NET_Web_App/C#_ASP_NET_Web_App
    ```

2.  **Run the Application**

    Use the `dotnet run` command to start the application.

    ```bash
    dotnet run
    ```

3.  **Access the API**

    The application will be accessible at `https://localhost:7111` or `http://localhost:5145`. You can access the weather forecast API endpoint at `/WeatherForecast`.

    Example:

    ```bash
    curl http://localhost:5145/WeatherForecast
    ```

## Dependencies

-   **.NET SDK 9.0**: Required for building and running the application.
-   **Microsoft.AspNetCore.OpenApi**: Used for integrating OpenAPI (Swagger) into the project.
