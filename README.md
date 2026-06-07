# Currency Exchange Rate Visualizer

A dynamic, interactive tool for visualizing historical currency exchange rates against the US Dollar (USD). Compare how different currencies have depreciated or appreciated over decades with an intuitive chart interface.

## Features

- 📊 **Interactive Charts** - Visualize currency trends over time with smooth, responsive charts
- 🌍 **Multi-Currency Support** - Track 14+ major currencies including EUR, GBP, INR, JPY, CNY, and more
- 🔍 **Smart Search** - Quickly find currencies by code, name, or by typing
- 📅 **Flexible Time Range** - Select custom start and end years to focus on specific periods
- 🎨 **Multiple Visualization Modes** - Switch between different chart types for better analysis
- ⚡ **Offline Friendly** - Works offline with cached historical data
- 📱 **Responsive Design** - Fully functional on desktop and mobile devices

## Live Demo

Visit the [live demo](https://r21meghashyam.github.io/currency-exchange-value/) to explore currency trends yourself.

## What You Can Do

- **Compare Multiple Currencies** - Hold Cmd/Ctrl and select multiple currencies to compare their performance against the USD
- **Analyze Time Periods** - Choose specific start and end years to focus on particular economic periods
- **Track Depreciation** - See how many units of each currency equal 1 USD over time
- **Switch View Modes** - Toggle between different visualization modes for deeper insights

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Responsive styling
- **Vanilla JavaScript** - No dependencies, pure JavaScript implementation
- **Chart.js** - Beautiful data visualization
- **Static Data** - JSON-based historical currency exchange rates

## Data

The project includes historical exchange rate data for:
- USD, EUR, GBP, INR, PKR, BDT, LKR, IDR, JPY, CNY, CAD, AUD, RUB, TRY

Data spans from 1960 onwards and is stored in JSON format for quick access.

## Project Structure

```
├── index.html              # Main HTML file
├── app.js                  # Application logic and state management
├── style.css               # Styling and layout
├── data/
│   ├── currency-data.json  # Historical exchange rate data
│   ├── latest-rate-source.json
│   └── source-summary.json
└── lib/
    └── chart.min.js        # Chart rendering library
```

## Getting Started

### Using GitHub Pages (Recommended)

The project is deployed on GitHub Pages and can be accessed directly:
https://r21meghashyam.github.io/currency-exchange-value/

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/r21meghashyam/currency-exchange-value.git
cd currency-exchange-value
```

2. Open with a local server (required for JSON data loading):
```bash
# Using Python 3
python -m http.server 8000

# Or using Node.js with http-server
npx http-server
```

3. Open `http://localhost:8000` in your browser

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Android)

## License

This project is open source and available for educational and personal use.

## Contributing

Feel free to fork, modify, and use this project for your own purposes!

---

Made with ❤️ for currency enthusiasts and data visualization lovers.
