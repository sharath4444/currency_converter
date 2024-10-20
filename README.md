# Currency Converter

A simple web-based currency converter that allows users to convert amounts between various currencies in real-time using exchange rates.

## Features

- Convert between multiple currencies
- Real-time exchange rates
- User-friendly interface
- Responsive design for mobile and desktop

## Technologies Used

- HTML
- CSS
- JavaScript
- [Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies) for fetching real-time exchange rates

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sharath4444/currency_converter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd currency_converter
   ```
3. Open `index.html` in your web browser.

## Usage

1. Enter the amount you want to convert.
2. Select the currency you want to convert from and to.
3. Click the "Convert" button to see the converted amount.

## Live Demo

You can try the live demo of the currency converter [here](https://sharath4444.github.io/currency_converter/).

## API Integration

The currency converter uses the [Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies) to fetch real-time exchange rates. 

### Example API Call
```javascript
fetch('https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies')
  .then(response => response.json())
  .then(data => console.log(data));
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## Acknowledgements

- [Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies) for providing the exchange rate data.
- Inspiration from various currency converter applications.
