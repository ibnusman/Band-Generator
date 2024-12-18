# Band Name Generator

This is a simple web application built with Node.js, Express, and EJS that generates a random band name by combining an adjective and a noun.

## What It Does

- **Generates a Random Band Name**: When you visit the homepage and click the "Generate Name" button, the app randomly selects an adjective and a noun from predefined lists and displays them together as a band name.
  
- **Dynamic Content Rendering**: The app uses **EJS (Embedded JavaScript)** to dynamically render the band name or a welcome message on the page based on whether the name has been generated yet.

## How It Works

1. **Initial Page Load**: When you first visit the homepage, you’ll see a welcome message: "Welcome to Band Generator".
   
2. **Form Submission**: When you click the "Generate Name" button, the app sends a POST request to `/submit`.
   
3. **Band Name Generation**: Upon receiving the request, the server randomly selects an adjective and noun from a list and renders them as a band name on the page, such as **"Excited Cat"** or **"Brave Moon"**.

4. **Result Display**: The newly generated band name is displayed at the top of the page.

## Technologies Used

- **Node.js**: The runtime environment.
- **Express**: A web framework for building the server.
- **EJS**: A templating engine used to dynamically render content.
- **Body-Parser**: Middleware used to parse form data.
