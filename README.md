# Currency Converter

A simple and intuitive web-based currency converter application that allows users to convert amounts between different currencies in real-time.

## Features

- **Real-time Exchange Rates**: Fetches live exchange rates from a reliable API.
- **Wide Currency Support**: Supports a comprehensive list of currencies from around the world.
- **Flag Display**: Shows country flags corresponding to the selected currencies for better visual identification.
- **User-Friendly Interface**: Clean and responsive design with easy-to-use dropdown menus and input fields.
- **Instant Conversion**: Get conversion results instantly with a single click.

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling and layout.
- **JavaScript (ES6)**: For dynamic functionality and API interactions.
- **Currency API**: Powered by [fawazahmed0/currency-api](https://github.com/fawazahmed0/currency-api) for exchange rates.
- **Flags API**: Uses [flagsapi.com](https://flagsapi.com/) for country flag images.
- **Font Awesome**: For icons.

## How to Use

1. Enter the amount you want to convert in the input field.
2. Select the source currency from the "From" dropdown.
3. Select the target currency from the "To" dropdown.
4. Click the "Get Exchange Rate" button.
5. View the converted amount and the current exchange rate displayed below.

## Installation and Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Currency_Converter.git
   ```

2. Navigate to the project directory:
   ```
   cd Currency_Converter
   ```

3. Open `index.html` in your web browser.

No additional setup or dependencies are required as the application runs entirely in the browser.

## Project Structure

```
Currency_Converter/
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── js/
│   ├── app.js          # Main JavaScript logic
│   └── codes.js        # Currency code mappings
└── README.md           # Project documentation
```

## API Usage

The application uses the free Currency API by Fawaz Ahmed. The API provides exchange rates in JSON format and supports various endpoints for different date ranges.

- Base URL: `https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies`
- Endpoint format: `/{fromCurrency}/{toCurrency}.json`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

Exchange rates are provided for informational purposes only and may not reflect real-time market rates. Always verify with official sources for financial transactions.