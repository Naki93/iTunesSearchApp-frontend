### iTunes Store Search App
The iTunes Store Search App allows users to search for different types of media, such as movies, music, podcasts, and more, using the iTunes Search API. Users can also add their favorite media items to a favorites list.

### How to Use the App
Search for Media Content:

Enter a search term in the search input field.
Select the media type from the dropdown menu (e.g., movie, music, podcast, etc.).
Click the "Search" button or press Enter to initiate the search.
The search results will be displayed below the search form.

Add Items to Favorites:

After performing a search, the search results will be displayed in a list.
Click the "Add to Favorites" button next to an item in the search results to add it to the favorites list.

View Favorites List:

The "Favorites" section below the search results displays the list of favorite items.
Click the "Remove" button next to an item in the favorites list to remove it from the list.

### Getting Started
To run the application on your local machine, you don't need to clone the entire repository. Instead, you can directly use npm start to start the frontend and backend servers.

### Prerequisites
Ensure that you have the following software installed on your machine:

Node.js (version 14 or higher)
npm (Node.js package manager)
Installation
Install Backend Dependencies:

### Install backend dependencies (skip if already installed)
`npm install --prefix backend`
Install Frontend Dependencies:

### Install frontend dependencies (skip if already installed)
`npm install --prefix frontend`

### Running the App
Start the Backend Server:
### From the project root directory
`npm start --prefix backend`
The backend server will run on port 5000 by default. If you need to change the port, you can modify it in the index.js file inside the backend folder.

Start the Frontend Development Server:
### From the project root directory
`npm start --prefix frontend`
The frontend server will run on port 3000 by default. If you need to change the port, you can modify it in the package.json file inside the frontend folder.

Open your Web Browser:

Once both the backend and frontend servers are running, open your web browser and visit http://localhost:3000 to access the application.

### Testing
The application comes with automated tests to ensure its functionality. To run the tests, use the following commands:

Run Backend Tests:
### From the project root directory
`npm test --prefix backend`
The tests use Jest and Supertest for testing the API endpoints.

Run Frontend Tests:
### From the project root directory
`npm test --prefix frontend`
The tests use Jest and React Testing Library for testing the React components.

### Security Measures
To ensure the security of this application, the following measures have been implemented:

The iTunes Search API does not require an API key for basic search requests. It is a public API provided by Apple that allows users to search for media content on the iTunes Store. However if there was any usage of API keys, the API keys and sensitive information would be stored as environment variables to prevent exposure in version control or public access.

Error Handling:
Proper error handling is implemented to handle and log errors securely without revealing sensitive information to the end-users.

CORS and Helmet Middleware:

The backend server uses CORS middleware to restrict cross-origin requests.
The backend server uses Helmet middleware to set various HTTP headers, enhancing security.

# Contributing
Contributions to the iTunes Store Search App are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


Happy searching! 🎶🎬📚
