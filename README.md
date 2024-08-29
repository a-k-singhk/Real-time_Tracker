# Real-Time Location Tracker
This is a simple real-time location tracking web application that uses the Geolocation API, Leaflet.js for mapping, and Socket.io for real-time communication between the client and server.

## Features
Real-Time Location Tracking: The application captures the user's location using the browser's Geolocation API and sends it to the server.
Live Map Updates: The user's location is displayed on an interactive map, which updates in real-time as the user moves.
Multiple Users: The app supports tracking the location of multiple users simultaneously.
Technologies Used
Socket.io: Enables real-time, bidirectional communication between web clients and servers.
Leaflet.js: A leading open-source JavaScript library for mobile-friendly interactive maps.
Geolocation API: Allows the app to obtain the geographical position of the user's device.
Prerequisites
Before running the application, ensure you have the following installed:

Node.js (version 14.x or higher)
npm (Node Package Manager)

## Installation
Clone the repository:

git clone https://github.com/your-username/realtime-location-tracker.git
cd realtime-location-tracker
Install the dependencies:
npm install
Start the server:
node index.js
Open the application:

Open your browser and navigate to http://localhost:3000.
