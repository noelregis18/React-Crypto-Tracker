# Cryptocurrency Tracker

A modern React application for tracking cryptocurrency prices, market trends, and detailed information about various cryptocurrencies in real-time.

![Crypto Tracker](https://user-images.githubusercontent.com/51760520/136682357-5d269bb9-0e36-4f26-a468-fb2963dd9468.png)

## Demo

Check out the live demo: [Crypto Hunter](https://crypto-hunter.netlify.app/)

## Features

- **Real-time Cryptocurrency Data**: Track prices, market cap, and volume for 100+ cryptocurrencies
- **Currency Conversion**: Toggle between INR and USD currencies
- **Detailed Information**: View comprehensive details about each cryptocurrency
- **Historical Charts**: Analyze price trends with interactive charts
- **Search Functionality**: Easily find specific cryptocurrencies
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Trending Cryptocurrencies**: Carousel display of trending coins

## Technologies Used

- [React JS](https://reactjs.org/) - Frontend library for building user interfaces
- [Material UI](https://v4.mui.com/) - React component library implementing Google's Material Design
- [Chart JS](https://reactchartjs.github.io/react-chartjs-2/) - JavaScript charting library for interactive data visualization
- [React Router](https://reactrouter.com/) - Navigation and routing for React applications
- [Axios](https://axios-http.com/) - Promise-based HTTP client for API requests
- [CoinGecko API](https://www.coingecko.com/en/api) - Cryptocurrency data API

## Installation and Setup

### Prerequisites

- Node.js (v12 or higher)
- npm or yarn

### Steps

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/react-crypto-tracker.git
   cd react-crypto-tracker
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm start
   # or
   yarn start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Usage

- **Home Page**: Displays a banner with trending cryptocurrencies and a table of all available cryptocurrencies
- **Cryptocurrency Details**: Click on any cryptocurrency to view detailed information and historical price charts
- **Currency Toggle**: Switch between INR (₹) and USD ($) using the selector in the header
- **Search**: Use the search bar to filter cryptocurrencies by name or symbol
- **Pagination**: Navigate through the list of cryptocurrencies using the pagination controls

## Project Structure

```
├── public/             # Static files
├── src/                # Source files
│   ├── components/     # React components
│   │   ├── Banner/     # Banner components
│   │   ├── CoinInfo.js # Cryptocurrency details component
│   │   ├── CoinsTable.js # Table of cryptocurrencies
│   │   ├── Header.js   # Application header
│   │   └── SelectButton.js # Button component
│   ├── config/         # Configuration files
│   │   ├── api.js      # API endpoints
│   │   └── data.js     # Static data
│   ├── Pages/          # Page components
│   │   ├── CoinPage.js # Cryptocurrency details page
│   │   └── HomePage.js # Home page
│   ├── App.js          # Main application component
│   ├── CryptoContext.js # Context for cryptocurrency data
│   └── index.js        # Application entry point
└── package.json        # Project dependencies and scripts
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [CoinGecko](https://www.coingecko.com/) for providing the cryptocurrency data API
- [Material UI](https://v4.mui.com/) for the UI components
- [Chart.js](https://www.chartjs.org/) for the interactive charts
