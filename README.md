# Sales Summary Dashboard

## Overview
This is a single-page web application designed to provide a quick and clear summary of sales data. It fetches sales figures from a `data.csv` file, calculates the total sales, and displays this summary prominently on the page. The application is built with modern web technologies for a responsive and user-friendly experience.

## Features
*   Fetches sales data from an attached `data.csv` file.
*   Calculates the sum of the 'sales' column from the CSV data.
*   Dynamically updates the page title to 'Sales Summary 2025'.
*   Displays the calculated total sales within the `#total-sales` element.
*   Integrates Bootstrap 5 for a styled and responsive user interface.

## Usage
1.  Ensure the `data.csv` file is present in the project's attachments.
2.  Open the `index.html` file in your web browser.
3.  The application will automatically load the data, perform the calculation, and display the sales summary.

## Technical Details
The application utilizes plain HTML, CSS, and JavaScript.
*   **HTML:** Provides the structure of the single-page application, including the placeholder for the total sales display (`#total-sales`).
*   **JavaScript:** Handles the data fetching (using the Fetch API), CSV parsing, sales column summation, and dynamic DOM manipulation to update the title and display the total.
*   **Bootstrap 5:** Loaded via jsDelivr CDN, providing pre-built components and styling for a clean and responsive layout.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.