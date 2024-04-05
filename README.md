# React-Place-Picker

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![GitHub License](https://img.shields.io/github/license/MarcoBasileDev/React-Place-Picker?style=for-the-badge)

## Overview

The Place Picker Application is a web application built using React that allows users to choose their favorite locations from a predefined list and add them to a "want to visit" section.

This project consists of two versions:

- **Version without Backend**: A frontend-only implementation where user interactions and data management are handled within the client-side application.
- **Version with Backend**: A version that includes a backend server to manage data persistence and interactions with the client.

## Features

- Utilizes browser methods such as navigator and geolocation to sort locations based on their proximity to the user.
- Demonstrates the use of useEffect hook for managing side effects.
- Utilizes useRef hook for accessing DOM elements and maintaining mutable references.
- Incorporates a backend server to handle data storage and retrieval.
- Implements custom hooks for modularizing and reusing logic.
- Makes HTTP requests to the backend server for CRUD (Create, Read, Update, Delete) operations on location data.

## Setup and Installation

- clone the repository: git clone https://github.com/MarcoBasileDev/React-Place-Picker.git

- Navigate to the project directory.
- Install dependencies: npm install
- Run the development server using: npm run dev

### Backend version

- Before running the development server go inside the backend folder and install the dependencies: npm install
- Then run the backend server: node app.js

## Techonlogies Used

- **Frontend:** React, JavaScript, HTML, CSS
- **Backend:** Node.js, Express.js
- **Data Persistence:** Dummy JSON database

## Why Two versions?

The decision to create two versions of the Place Picker Application was driven by learning objectives and project scope:

- **Version without Backend:** This version was developed primarily for practicing client-side techniques and understanding browser APIs. It serves as a learning exercise for utilizing navigator, geolocation, and React hooks like useEffect and useRef for managing state and side effects without relying on a backend server.

- **Version with Backend:** By adding a backend server, the project expands to cover full-stack development concepts. This version allows for a deeper exploration of HTTP requests, data persistence, and server-client communication. It serves as a platform to practice integrating frontend and backend components seamlessly.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
