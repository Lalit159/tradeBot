# Trading Bot for CoinDCX

## Overview
This project is a trading bot designed to help make arbitrage on CoinDCX by leveraging price differences in the market and automating the process of making orders. It uses TypeScript, the CoinDCX API, and the Bun runtime for optimal performance and ease of use.

## Features
- **Automated Trading**: The bot automates the process of placing orders based on arbitrage opportunities.
- **Real-Time Market Analysis**: Continuously monitors the market for price differences to exploit.
- **Efficient Execution**: Built with the fast and efficient Bun runtime to ensure quick execution of trades.
- **Customizable**: Easily configurable to adjust trading strategies and parameters.

## Technologies Used
- **TypeScript**: For type-safe JavaScript development.
- **CoinDCX API**: To interact with the CoinDCX trading platform.
- **Bun Runtime**: A fast all-in-one JavaScript runtime.

## Installation

To install dependencies:

```bash
bun install
```

## Running the Bot

To run the trading bot:

```bash
bun run index.ts
```

## Setup and Configuration

1. **Clone the Repository**
   
   Clone this repository to your local machine using:

   ```bash
   git clone git@github.com:Lalit159/tradingBot.git
   ```

2. **Install Bun**
   
   Ensure you have Bun installed on your system. You can download and install Bun from the official [Bun website](https://bun.sh).

3. **Set Up Environment Variables**

   Create a `config.js` file in the root directory of the project and add your CoinDCX API credentials:

   ```plaintext
   export const key=your_api_key
   export const secret=your_secret_key
   ```

## How It Works

1. **Market Data Fetching**: The bot continuously fetches market data from CoinDCX using the CoinDCX API.
2. **Arbitrage Detection**: It analyzes the price differences between different markets to identify arbitrage opportunities.
3. **Order Execution**: When an arbitrage opportunity is found, the bot automatically places the necessary buy and sell orders to exploit the price difference.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please contact:

- [Lalit Gidwani](mailto:lalit159gidwani@gmail.com)

---
