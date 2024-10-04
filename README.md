# Trading Bot Simulation

This project simulates a basic trading bot for a hypothetical stock market. It includes a frontend interface built with React.

## Project Structure

```
trading-bot
│   ├── public/
│   ├── src/
│   │   ├── App.js
│   │   ├── components/
│   │   │   ├── Dashboard.js
│   │   │   └── TradeHistory.js
│   │   └── index.js
│   └── package.json
│   └── README.md
```

## Features

- Backend service that monitors stock price changes using mock data
- Simple trading strategy based on price movements
- Frontend dashboard to display bot performance and trade history
- Real-time updates using WebSocket connection

## Getting Started

### Installation

Install frontend dependencies:
   ```
   cd ../frontend
   npm install
   ```

### Running the Application

In a new terminal, start the frontend development server:
   ```
   cd frontend
   npm start
   ```

## Trading Logic

The trading bot uses a simple strategy based on price movements:
- Buy when the stock price drops by 2% (configurable)
- Sell when the stock price rises by 3% (configurable)

The bot tracks its positions, balance, and overall profit/loss, providing a summary of trades and performance.


## Contributing

Feel free to fork this repository and submit pull requests for any improvements or additional features.
