# Currency Converter


A simple, clean, and intuitive web application for converting amounts between various world currencies. This project utilizes a free currency API to fetch up-to-date exchange rates and displays corresponding country flags for a user-friendly experience.

## Features

- **Real-time Conversion:** Fetches the latest exchange rates from the `@fawazahmed0/currency-api`.
- **Wide Range of Currencies:** Supports a comprehensive list of global currencies for conversion.
- **Visual Feedback:** Displays country flags corresponding to the selected currencies for easy identification.
- **Simple Interface:** An easy-to-use form to input amounts and select 'from' and 'to' currencies.
- **Responsive Design:** The layout is optimized for both desktop and mobile devices.

## How to use

No installation is required. Simply follow these steps to run the application locally:

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/sanzizlohar/currency-converter.git
    ```
2.  **Navigate to the directory:**
    ```sh
    cd sanzizlohar-currency-converter
    ```
3.  **Open the application:**
    Open the `index.html` file in your preferred web browser.

Once the page is loaded:
1.  Enter the numerical amount you wish to convert.
2.  Select the starting currency from the "From" dropdown.
3.  Select the target currency from the "To" dropdown.
4.  Click the "Convert" button to see the result. The application will also load an initial conversion from USD to INR by default.

## Technologies Used

-   **HTML5:** Structures the web page content.
-   **CSS3:** Styles the user interface, including the background, form, and responsive layout.
-   **JavaScript:** Handles the application logic, including API requests, DOM manipulation, and calculating the conversion.
-   **APIs:**
    -   [Currency API by Fawaz Ahmed](https://github.com/fawazahmed0/currency-api) for exchange rate data.
    -   [Flags API](https://flagsapi.com/) for displaying country flags.
