# Spotify Clone Project

This is a full-stack Spotify Clone project with three main parts:
1. **Frontend**: Built with modern web technologies.
2. **Admin Panel**: For managing the backend.
3. **Backend**: The server-side API for handling data and logic.

## Project Structure

- **Frontend**: [Spotify Frontend](https://github.com/sithuminikaushalya/Spotify-Clone)
- **Admin Panel**: [Spotify Admin Panel](https://github.com/sithuminikaushalya/Spotify-Admin)
- **Backend**: [Spotify Backend](https://github.com/sithuminikaushalya/Spotify-Backend)

---

## Features

- **Frontend**:
  - User-friendly interface resembling Spotify.
  - Integration with the backend to fetch and display data.
  
- **Admin Panel**:
  - Allows administrators to manage data.
  
- **Backend**:
  - Node.js and Express.js based API.
  - Handles data management and authentication.

---

## How to Run the Project

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [NPM](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/) (if you are using MongoDB for your database)

### Running the Frontend

1. Clone the frontend repository:
    ```bash
    git clone https://github.com/sithuminikaushalya/Spotify-Clone.git
    cd Spotify-Clone
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the development server:
    ```bash
    npm run dev
    ```

   The frontend should now be running on `http://localhost:3000`.

### Running the Admin Panel

1. Clone the admin panel repository:
    ```bash
    git clone https://github.com/sithuminikaushalya/Spotify-Admin.git
    cd Spotify-Admin
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the admin server:
    ```bash
    npm start
    ```

   The admin panel should now be running on `http://localhost:3001`.

### Running the Backend

1. Clone the backend repository:
    ```bash
    git clone https://github.com/sithuminikaushalya/Spotify-Backend.git
    cd Spotify-Backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    node server.js
    ```

   The backend server should now be running on `http://localhost:5000`.

---

## API Endpoints

Here are the main endpoints provided by the backend:

- `GET /api/songs`: Fetch all songs.
- `POST /api/songs`: Add a new song.
- `PUT /api/songs/:id`: Update a song by ID.
- `DELETE /api/songs/:id`: Delete a song by ID.

---

## Technologies Used

- **Frontend**: React, CSS
- **Backend**: Node.js, Express.js
- **Admin Panel**: React, Admin Dashboard UI
- **Database**: MongoDB (or any database you configure)



