# Population Viewer

## Overview

The **Population Viewer** is a simple web application that dynamically displays population data from a JSON file. The data is fetched and displayed using JavaScript, and styled with CSS.

## Files

- `index.html`: The main HTML file that sets up the structure of the web page.
- `styles.css`: The CSS file that styles the elements of the web page.
- `population.json`: The JSON file containing the population data to be displayed.

## Prerequisites

To run this application, you need to have a local HTTP server set up. This is necessary because modern browsers block fetching of local files (e.g., the JSON file) due to security restrictions.

## Setting Up a Local HTTP Server

You can use various methods to set up a local HTTP server. Below are instructions for using Node.js and the `http-server` package.

### Using Node.js and `http-server`

1. Install Node.js from [nodejs.org](https://nodejs.org/).
2. Open your terminal or command prompt.
3. Install the `http-server` package globally by running the following command:

   ```bash
   npm install -g http-server
   ```

### Opening up the app

1. Navigate to the directory containing your project files.
2. Start the HTTP server by running the following command:

   ```bash
   http-server
   ```

3. Open your browser and go to http://localhost:8080 (or the port indicated in your terminal).
