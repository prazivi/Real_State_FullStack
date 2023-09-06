@author:- Pranav Gupta
# Homzy - A Real Estate Website

![Dashboard](https://github.com/prazivi/Real_State_FullStack/blob/master/Project%20snip/DashBoard.JPG)

## Overview

Homzy is a real estate website that simplifies the process of buying and selling properties. It provides a user-friendly interface for property owners to list their properties and for potential buyers to search and view available properties. The website allows users to search for properties in any location and view surrounding areas to get a better understanding of the neighborhood. Additionally, users can like and add properties to their favorites list for future reference. To enhance security and provide a seamless authentication experience, Auth0 is used for both client-side and server-side authentication. The UI components are developed with Mantine to ensure a polished and responsive user interface.

## Key Features

- Property Search: Users can search for properties in any location using the search functionality. The website also provides the ability to view areas around a property on a map.

- Favorites List: Logged-in users can like properties and add them to their favorites list for easy access and comparison.

- User Authentication: Auth0 is integrated into the website to handle user authentication securely.

- Login and Signup: Users can create an account and log in to access additional features and save their preferences.

## Tech Stack

The project is built using the following technologies:

- React: A popular JavaScript library for building user interfaces.
- Node.js: A server-side JavaScript runtime environment.
- Express: A web application framework for Node.js, simplifying server-side development.
- MongoDB: A NoSQL database used for storing property and user data.
- Auth0: A third-party authentication service that handles user authentication for both the client-side and server-side.
- Mantine: A React component library providing UI components for a polished user interface.

## How to Run

To run Homzy on your computer, follow these steps:

1. Clone this repository to your local machine:
git clone https://github.com/prazivi/Homzy-Real-Estate.git


2. Navigate to the project directory:
cd Homzy-Real-Estate


3. Install the required dependencies for both the client and server sides:
cd client
npm install
cd ../server
npm install


4. Set up environment variables:
- For the server, create a `.env` file in the `server` directory and set the required variables for MongoDB connection and Auth0 credentials.

5. Start the development server for both the client and server sides:
cd client
npm start
cd ../server
npm start


6. Open your web browser and visit `http://localhost:3000` to access the Homzy website.

## Contributing

Contributions to this project are welcome. If you wish to contribute, please follow the standard GitHub workflow by creating pull requests and discussing any proposed changes via issues.

## Reporting Issues

If you encounter any issues while using the Homzy website or have any suggestions for improvement, please open an issue on the GitHub repository. Your feedback is valuable to us, and we will address any reported issues promptly.




