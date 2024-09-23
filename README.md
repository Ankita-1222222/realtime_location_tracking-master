# Real-Time Location Tracking

## Overview

This project is a web application designed for real-time location tracking and monitoring. It utilizes WebSocket technology to provide real-time updates, displaying the location of tracked entities on a map. All connected users can view everyone's location on the map in real-time.

## Features

- Real-time location updates using WebSocket technology
- Display locations on an interactive map using OpenStreetMap and Leaflet.js
- Supports multiple connected users viewing locations simultaneously

## Technologies Used

- **JavaScript**
- **Node.js**
- **Express.js**
- **Socket.IO**
- **OpenStreetMap**
- **Leaflet.js**

## Installation

1. Clone the repository:
    ```bash
   https://github.com/Ankita-1222222/realtime_location_tracking-master
    ```
2. Navigate to the project directory:
    ```bash
    cd realtime_location_tracking
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the server:
    ```bash
    node server.js
    ```
2. Open your web browser and go to `http://localhost:3000` to view the application.

## Project Structure

- `server.js` - Main server file that sets up the Express server and WebSocket.
- `public/` - Directory containing the client-side code.
  - `index.html` - Main HTML file.
  - `style.css` - CSS file for styling.
  - `app.js` - JavaScript file that handles the client-side WebSocket and map functionality.

