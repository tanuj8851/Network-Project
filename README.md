# Network Tab Clone

This project is a clone of the Network tab from Google Developer Tools, built using React and Material-UI. It provides a user interface to fetch URLs, view detailed network request information, and sort requests by type.


#Deployment

 **Deployed Link:** https://network-project-nine.vercel.app/
 **Backend Link:**  https://cors-backend-h9oa.onrender.com


 ## Random URLS to Fetch

 - https://jsonplaceholder.typicode.com/posts
 - https://jsonplaceholder.typicode.com/comments
 - https://jsonplaceholder.typicode.com/albums
 - https://jsonplaceholder.typicode.com/todos

## Features

- **Fetch URLs:** Enter a URL and fetch network requests.
- **Display Details:** View status, type, size, and timing of each request.
- **Sort Requests:** Sort requests dynamically by type.
- **Request Detail View:** Click on a request to see detailed information.

## Technologies Used

- **Frontend:** React, Material-UI
- **Backend (Proxy):** Node.js (for handling CORS)

## Installation

Ensure you have Node.js installed on your machine.

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/network-tab-clone.git
   cd network
   ```
2. **Install dependencies:**

  ```bash
  npm install
   ```
3. **Usage**

  ```bash
  npm install
   ```
- Start the development server:
- Open your browser and go to http://localhost:3000 to view the application.
- Enter a URL in the input field and click "Fetch" to see network requests.
- Click on a row in the table to view detailed information about a specific request.
- Use the sort buttons to sort requests by type.

## Project Structure

- **src/NetworkTab.jsx**  Main component for displaying network requests and fetching URLs.
- **src/RequestDetail.jsx**: Component for displaying detailed information about a selected network request.
- **src/interceptors.jsx**: Sets up Axios interceptors to capture request and response details.
