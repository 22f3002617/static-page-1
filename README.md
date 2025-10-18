# Currency Picker and Converter

This is a simple web application that allows users to select a currency to convert the total sales computed from a table. The conversion rates are embedded within the application.

## Features

- Displays a list of products with their sales in USD.
- Provides a dropdown to select different currencies.
- Converts total sales from USD to the selected currency.
- Updates the total with the selected currency code.
- Includes a conversion example in HTML format in `#markdown-output`.

## Usage

1. Open `index.html` in a web browser.
2. Use the dropdown to select a desired currency.
3. Observe the automatic conversion of total sales into the selected currency.

## Local Development

To run the app locally, clone the repository, and open `index.html` in a web browser. Ensure all logic and data are embedded within the HTML file to enable static site hosting.

## Deployment on GitHub Pages

1. Push all content to a GitHub repository.
2. Go to the repository settings and enable GitHub Pages from the `main` branch.
3. Access the live application through the provided GitHub Pages URL.

## Accessibility and Fallback

- Uses semantic HTML for better accessibility.
- Inline scripts and styles are used to ensure the app works without the need for external resources.
- Provides a default conversion when JavaScript is enabled.

## Future Improvements

- Add more comprehensive currency rate fetching from an external API.
- Implement region-based currency formatting.
- Enhance accessibility with ARIA roles if the UI becomes more complex.

## License

This project is licensed under the MIT License.