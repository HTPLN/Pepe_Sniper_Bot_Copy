# Telegram Crypto Sniper Bot

Telegram Crypto Sniper Bot is a subscription-based bot that allows users to monitor and automatically trade newly listed tokens on Uniswap, Pancakeswap, and Sushiswap. The bot is designed to handle user payments, wallet management, and token trading, offering a seamless experience for crypto enthusiasts.

## Features

1. Telegram bot interface for easy user interaction.
2. Subscription-based access with crypto payments.
3. Built-in wallet management module for creating and registering wallets securely.
4. Automatic trading of newly listed tokens on Uniswap, Pancakeswap, and Sushiswap.
5. Customizable user settings for slippage percentage, buy per listing in native currency, total allocated funds, and take profit/stop loss actions.
6. Monitoring and information sharing for newly listed tokens.
7. Scanning for specific contract liquidity addition and executing trades for users who request it.

## Getting Started

### Prerequisites

- Python 3.6+
- Web3.py library
- python-telegram-bot library
- An Ethereum node (e.g., Infura)

### Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/telegram-crypto-sniper-bot.git
```

2. Install the required Python packages

```bash
pip install -r requirements.txt
```

3. Set up your environment variables for the bot token, Ethereum node, and HD wallet seed. Replace `<...>` with your actual values.

```bash
export TELEGRAM_BOT_TOKEN=<your_telegram_bot_token>
export ETHEREUM_NODE_URL=<your_ethereum_node_url>
export HD_WALLET_SEED=<your_hd_wallet_seed>
```

4. Run the bot

```bash
python main.py
```

## Usage

After deploying the bot, users can interact with it through Telegram. The bot provides a menu-driven interface, allowing users to navigate through various features like wallet management, sniper settings, and new listings info.

Users must first subscribe to the bot by paying the required subscription fee in crypto. Once subscribed, they can access all the features offered by the bot.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
