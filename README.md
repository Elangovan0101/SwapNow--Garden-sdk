# SwapNow App

Welcome to SwapNow, a demonstration project showcasing the integration of the [Garden SDK](https://docs.garden.finance/developers/sdk/) for a seamless WBTC to BTC swap experience.

> [!NOTE]
> While this demo runs on a local network for convenience, you can configure it to operate on Testnet or Mainnet by adjusting the settings.

## Features

- **Comprehensive Environment**: Enables multichain operations effortlessly.
- **Intuitive Swap Interface**: Swap WBTC to BTC with ease.
- **Transaction Monitoring**: Real-time display of transaction status.
- **Powered by Garden SDK**: Leveraging the Garden SDK for secure and efficient swaps.
- **Efficient State Management**: Utilizes [zustand](https://zustand-demo.pmnd.rs/) for robust state handling.

## Environment Setup

To ensure a smooth development experience, we utilize [Merry](https://docs.garden.finance/developers/merry/) to set up the required multichain environment for seamless swapping. This includes essential components like the [Orderbook](https://docs.garden.finance/developers/fundamentals/orderbook/), [Filler](https://docs.garden.finance/developers/fundamentals/filler/), [Faucet](https://www.alchemy.com/faucets#faucets-switchback-right-light), and nodes for Bitcoin, Ethereum, and Arbitrum.

1. Install Merry
curl https://get.merry.dev | bash
Start Merry

merry go



# Launch Merry in headless mode
merry go --headless

# 2.Install Dependencies
npm install

# 3.Run the Development Server
npm run dev


## Project Setup

## 1. **Clone the Repository**

git clone (https://github.com/Elangovan0101/SwapNow--Garden-sdk.git)

