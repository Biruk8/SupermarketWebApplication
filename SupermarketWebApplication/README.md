# Supermarket Web Application

Supermarket Web Application is a simple learning project designed to showcase web development skills. This basic web application allows users to view a catalog of items and place orders. The project utilizes technologies like Express, EJS, and MongoDB to demonstrate the fundamentals of building a web application with server-side and client-side interaction.

## Table of Contents

- [Introduction](#supermarket-web-application)
- [Technologies](#technologies)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Technologies

- Node.js
- Express.js
- EJS (Embedded JavaScript)
- MongoDB

## Features

- Display a catalog of items available in the supermarket.
- Allow users to place orders by selecting the desired items and quantities.
- Calculate the total price for the items in the order.
- Render the order confirmation with the list of items ordered and the total price.

## Getting Started

To run the Supermarket Web Application locally, follow these steps:

1. Clone the repository to your local machine.
2. Install Node.js and npm (Node Package Manager) if you haven't already.
3. Install the required dependencies using the following command:
'npm install'

4. Make sure you have MongoDB installed and running on your local machine.

## Usage

1. Start the web server using the following command:
'node supermarketServer.js [jsonFile]'


Replace `[jsonFile]` with the path to your JSON file containing the list of items.

2. Open your web browser and navigate to `http://localhost:5000/` to view the home page.

3. Explore the catalog of items available in the supermarket by visiting the `/catalog` route.

4. Place an order by visiting the `/order` route, selecting the desired items, and specifying the quantities.

5. The application will calculate the total price for the items in your order and display an order confirmation.

## Contributing

This project is for learning purposes and is not actively maintained. However, if you have any suggestions or improvements, feel free to fork the repository, make your changes, and create a pull request. We welcome community contributions!

---

