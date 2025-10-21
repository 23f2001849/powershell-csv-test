# Project Overview
This project is a web application designed to display product data from a CSV file in a Bootstrap table. The application reads the CSV file, parses the product data, and generates a responsive table that can be viewed on any device. The primary purpose of this application is to provide an easy way to view and understand the product data. The application also calculates and displays the total price of all products, providing a quick overview of the total cost. 

This application is particularly useful in e-commerce scenarios, where managers and stakeholders need a clear, concise view of their product inventory at a glance. This app can be integrated into larger inventory management systems or used as a standalone tool for small businesses.

# Requirements
The application meets the following evaluation criteria:

1. **Displays CSV data**: The application reads a CSV file (products.csv), parses the product data, and displays it in a table.
2. **Bootstrap table**: The application uses Bootstrap, a popular CSS framework, to generate a responsive table that looks good on all screen sizes.
3. **Calculates total**: The application adds up the prices of all products and displays the total.

# Installation & Setup
To set up this application, follow these steps:

1. **Clone the repository**: Clone this repository to your local machine using the command `git clone <repository-url>`.
2. **Open the HTML file**: Navigate to the directory where you cloned the repository and open the `index.html` file in your web browser. This will start the application.
3. **View the application**: You should now see a table with product data and a total price displayed on your screen.

No additional setup or installation is required as the application is entirely client-side and does not require a server or database.

# Usage Instructions
Using this application is straightforward:

1. **View Product Data**: When you open the application, you will see a table displaying product data.
2. **View Total Price**: The total price of all products is displayed below the table.

You can refresh the page to reload the data.

# Technical Details
This application is built using HTML, CSS, and JavaScript. The HTML and CSS are used to create and style the table, while the JavaScript fetches and parses the CSV data, populates the table, and calculates the total price. 

The application uses the Fetch API to retrieve the CSV file. This data is then split into rows and columns and used to create the table. The Bootstrap framework is used to create a responsive table that looks good on all screen sizes.

# Troubleshooting
If you're having trouble viewing the data, make sure the CSV file is in the same directory as the `index.html` file. If the file is not found, the table will not be populated.

If the total price is not displayed, make sure the price data in the CSV file is formatted correctly. The price should be a number with no dollar sign or other characters.

# License
This project is licensed under the MIT License, which means you can freely use, modify, and distribute the code, as long as you include the original copyright notice and disclaimer. For more details, see the `LICENSE` file in the project repository.