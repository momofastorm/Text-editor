# 19 Progressive Web Applications (PWA): Text Editor

Welcome to the project that aims to develop a text editor running in the browser! This document will guide you through the development process, from setting up the project structure to deploying it on Heroku. Our goal is to create a Progressive Web App (PWA) that offers a seamless user experience, including offline functionality and data persistence through IndexedDB.

Project Overview:

Application Type: Single-page Progressive Web Application (PWA)
Data Persistence: IndexedDB with redundancy techniques
Offline Functionality: Full offline capability
Deployment Platform: Heroku
Backend: Node.js
Frontend: JavaScript bundled with webpack
Getting Started:

Clone the existing application repository.
Navigate to the root directory in your terminal.
Run npm run start to launch both the backend and serve the client.
Ensure that your JavaScript files are bundled using webpack.
Check for the presence of the generated HTML file, service worker, and manifest file.
IndexedDB and Data Persistence:

Utilize the idb package, a lightweight wrapper for IndexedDB API.
Implement methods for storing and retrieving data in IndexedDB.
Verify that upon opening the text editor, IndexedDB immediately creates a database storage.
Test the ability to save content in the text editor using IndexedDB when clicking off the DOM window.
Confirm that reopening the text editor retrieves the saved content from IndexedDB.
Offline Functionality:

The application should function offline seamlessly.
When the Install button is clicked, the web application should be downloaded as an icon on the desktop.
Ensure the service worker is registered using Workbox.
Pre-cache static assets upon loading, including subsequent pages and static assets.
Heroku Deployment:

Follow the Heroku Deployment Guide from The Full-Stack Blog.
Ensure your webpack application has proper build scripts for deployment.
Conclusion:

Your journey involves building a robust browser-based text editor with offline capabilities, utilizing IndexedDB for data persistence, and deploying the application on Heroku. By following these steps and adhering to the outlined goals, you'll create a feature-rich Progressive Web App that delivers a seamless and efficient user experience.

Feel free to reach out if you have any questions or require assistance during your development process. Good luck, and happy coding!