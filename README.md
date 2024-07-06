# Express.js Practical Lessons

This repository contains practical lessons for learning Express.js, a popular Node.js framework for building web applications.

## Table of Contents

- [Overview](#overview)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the Server](#running-the-server)
  - [Accessing Pages](#accessing-pages)
- [Folder Structure](#folder-structure)
- [License](#license)

## Overview

In this series of practical lessons, I learn how to use Express.js to create a basic web server, serve static HTML files, and define routes for different content pages such as a home page, services page, and contact page. Additionally, I learn how to create a simple "About" page route to demonstrate handling non-static content.

### Prerequisites

Before starting, make sure you have the following installed:

- Node.js (which includes npm, the Node.js package manager)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Heshbon/Express.js.git 
   cd express-js-practical-lessons

2. Install dependencies using npm:
    npm install

## Usage
Running the Server
To start the Express server, run the following command:
    npm run dev

## Accessing Pages

Once the server is running, you can access the following pages in your web browser:

    Home Page: http://localhost:8000/
    Services Page: http://localhost:8000/services
    Contact Us Page: http://localhost:8000/contactUs
    About Page: http://localhost:8000/about

## Folder Structure

The folder structure of this repository is as follows:
express-js-practical-lessons/
```
├── public/
│   ├── home.html
│   ├── services.html
│   └── contact.html
├── server.js
└── README.md
```
## License

This project is licensed under the MIT License. See the [MIT License](https://opensource.org/licenses/MIT) file for details.
