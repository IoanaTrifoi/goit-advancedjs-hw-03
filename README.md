GoIT Advanced JS - Homework 03: Image Search Gallery
A modular web application built with Vite that allows users to search for images using the Pixabay API and view them in a responsive gallery with modal functionality.

Features
Keyword Search: Users can search for images via a dedicated form.

Asynchronous Requests: Fetches data from Pixabay using axios with specific parameters (photo type, horizontal orientation, safe search).

Modular Codebase:

pixabay-api.js: Handles all HTTP requests to the backend.

render-functions.js: Contains logic for creating markup and manipulating the DOM.

main.js: Manages the overall application logic and event listeners.

Interactive Gallery: Integrated with SimpleLightbox for a full-screen modal experience.

Visual Feedback:

Loading indicator (CSS-loader) displayed during data fetching.

iziToast notifications for errors (empty results or failed requests).

Technologies Used
Vite: Frontend build tool.

Axios: Promise-based HTTP client.

SimpleLightbox: Touch-friendly image lightbox.

iziToast: Elegant responsive notifications.

 Installation and Setup
Clone the repository:

Bash
git clone https://github.com/IoanaTrifoi/goit-advancedjs-hw-03.git
Install dependencies:

Bash
npm install
Start development server:

Bash
npm run dev
Build for production:

Bash
npm run build
🔗 Project Links
Live Page: https://ioanatrifoi.github.io/goit-advancedjs-hw-03/

Source Code: https://github.com/IoanaTrifoi/goit-advancedjs-hw-03
