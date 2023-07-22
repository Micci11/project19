# Text Editor Web Application

## Overview

This repository contains a text editor web application with a set of features to provide a smooth and user-friendly writing experience. The application is built using modern web technologies, including Webpack for bundling, IndexedDB for content storage, and service workers for improved performance.

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the dependencies by running `npm install` in the root directory.
3. Start the application by running `npm run start` from the root directory.
4. The application will start up the backend server and serve the client-side of the application.

## Features

- Client-Server Folder Structure: The application follows a clear folder structure, separating client-side and server-side code for easy development and maintenance.

- Webpack Bundling: JavaScript files are bundled using Webpack, generating an HTML file, service worker, and manifest file for enhanced performance and functionality.

- Next-Gen JavaScript Support: The application fully supports next-generation JavaScript features, ensuring compatibility with modern browsers.

- IndexedDB Integration: IndexedDB is used to immediately create a database storage upon opening the text editor, allowing content to be automatically saved as you type.

- Content Persistence: The application retrieves content from IndexedDB, providing seamless persistence of your data even after reopening the text editor.

- Install Button: Users can download the web application as an icon on their desktop by clicking the Install button, offering convenient access.

- Service Worker with Workbox: The web application uses a registered service worker with Workbox to pre-cache static assets, providing improved performance and offline functionality.

## Deployment

This application is designed for easy deployment to Heroku. Proper build scripts for a webpack application are included to streamline the deployment process.

Feel free to explore the application's features and enjoy an enhanced writing experience!

## Screenshot

![screenshot](C:\Users\Micci\desktop\cautious-meme\client\src\images\Screenshot 2023-07-21 205848.png)


## Resources

Chat GPT: Chat GPT, powered by OpenAI, provided valuable assistance throughout the development process.
Carol Wargo (classmate) and I worked together on this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.