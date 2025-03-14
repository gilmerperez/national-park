# National Park API

## Project Overview

This project is a web application that allows users to search for national parks and events based on a state they input. When a user enters the name of a state, the application makes a request to the National Park Service API to fetch a list of national parks and events in that state. The fetched data is then displayed on the page for the user to view.

Additionally, the application keeps track of the user's previous searches, displaying them as clickable buttons. When a user clicks on a previous search, the parks and events for that state are displayed again. Users can also remove a state from their search history by clicking the trash can icon next to it.

The application is built using Express for the server-side logic and uses the Fetch API to make asynchronous requests to the National Park Service API. The application also relies on environment variables to securely store the API key needed to make requests to the National Park Service API.

By working with the Fetch API, server-side routes, and dynamic data management, this project helps users interact with real-time national park information while providing a smooth and dynamic user experience.

## Table of Contents

- [Usage](#usage)
- [Instructions](#instructions)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Additional Resources](#additional-resources)

## Usage

The application is invoked by using the following commands:

```bash
npm install
npm run build
npm run start:dev
```

## Instructions

1. Clone the repository to your local machine.
2. Navigate to the project folder in your terminal.
3. Run `npm install` to install all required dependencies.
4. Make sure to add your API KEy to the `.env` file from the [National Park Service API](https://www.nps.gov/subjects/developer/get-started.htm) as the `API_KEY` value.
5. Start the application by running `npm run start:dev`.
6. Visit the application in your browser, input a state, and see national parks and events displayed on the page.
7. View and click on previously searched states to see their national parks and events.

## Key Features

- Display previous search history as clickable buttons.
- Fetch national parks and events based on user-provided state.
- Remove previously searched states from history with a trash can icon.

## Technology Stack:

This application needs the following tools and technologies to operate:
- **dotenv**: To manage environment variables securely.
- **HTML/CSS**: To structure and style the application interface.
- **Node.js**: The runtime environment for running JavaScript on the server.
- **JavaScript**: For handling the client-side functionality and dynamic content.
- **Fetch API**: For making asynchronous requests to fetch national parks and event data.
- **Express**: The server-side framework used to handle requests and manage API communication.


## Additional Resources

API Documentation to get your [National Park Service API Key](https://www.nps.gov/subjects/developer/get-started.htm)

Documentation For understanding and using [The Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)

