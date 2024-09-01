# Real-Time Navigation Map with Leaflet, EJS, and Socket.io

This project is a real-time navigation map application built using [Leaflet](https://leafletjs.com/), [EJS](https://ejs.co/), and [Socket.io](https://socket.io/). It allows users to visualize real-time location data on a map, providing a dynamic experience as the data is updated in real-time via web sockets.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Real-time updates**: Location data is updated in real-time using Socket.io.
- **Interactive map**: The application uses Leaflet for an interactive and user-friendly map experience.
- **Templating with EJS**: EJS is used for rendering dynamic content on the server side.
- **Responsive design**: The map and interface are responsive and work well on both desktop and mobile devices.

## Technologies

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **EJS**: Embedded JavaScript templating.
- **Leaflet**: JavaScript library for interactive maps.
- **Socket.io**: Real-time bidirectional event-based communication.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/real-time-navigation-map.git
    cd real-time-navigation-map
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run the application:

    ```bash
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Open the application in your browser.
- The map will display real-time location data as it is received.
- Use the controls to interact with the map, such as zooming and panning.

## Folder Structure

