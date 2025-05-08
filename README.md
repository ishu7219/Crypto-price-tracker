# Real-Time Crypto Price Tracker

A responsive React + Redux application that tracks cryptocurrency prices in real-time, simulating WebSocket updates.

![Demo GIF](demo/demo.gif)

## Features

- Real-time price updates every 1.5 seconds
- Shows 5 major cryptocurrencies (BTC, ETH, USDT, XRP, SOL)
- Color-coded percentage changes
- Responsive design
- 7-day price charts
- Complete market data (price, market cap, volume, supply)

## Tech Stack

- React 18
- Redux Toolkit for state management
- CSS for styling
- Simulated WebSocket updates

## Setup Instructions

1. Clone the repository
-> https://github.com/ishu7219/Crypto-price-tracker.git

2. Install dependencies
-> npm install

3. Start the development server
-> npm start


4. Open http://localhost:3000 to view the application

## Project Structure

- `/src/components` - React components
- `/src/features` - Redux slices and logic
- `/src/utils` - Helper functions and data simulator
- `/src/app` - Redux store configuration
