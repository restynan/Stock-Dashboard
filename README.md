# Stock Ticker Dashboard

## Overview

The Stock Ticker Dashboard is an interactive web application built using Python's Dash framework. This application provides real-time stock data visualization, allowing users to track and analyze stock prices for various companies listed on NASDAQ.

## Features

- **User Authentication**: Basic authentication to ensure secure access to the dashboard.
- **Interactive Dropdown**: Select multiple stock symbols to compare their performance.
- **Date Range Picker**: Define custom date ranges to visualize stock data over specific periods.
- **Dynamic Graphs**: Real-time updating of stock prices displayed in a clear, user-friendly graphical format.
- **Responsive Design**: User interface designed for easy navigation and interaction, with a modern and clean aesthetic.

## Technology Stack

- **Python**: Core programming language used for developing the application.
- **Dash**: Framework for building analytical web applications.
- **Plotly**: Used for creating dynamic and interactive graphs.
- **YFinance**: API to fetch historical market data from Yahoo Finance.
- **Pandas**: Data manipulation and analysis library.

## How It Works

1. **User Authentication**: Secure login with predefined credentials.
2. **Select Stock Symbols**: Users can choose multiple stock symbols from the dropdown menu.
3. **Define Date Range**: Specify the start and end dates to filter the data.
4. **Submit and Visualize**: Click the submit button to generate the stock price graphs for the selected symbols and date range.
5. **Dynamic Graph Update**: The application fetches the data and updates the graph in real-time, providing users with an immediate visual representation of the stock performance.

## Key Components

- **Dash and Plotly**: Used for creating the web application's frontend and graphs.
- **YFinance**: Provides historical stock data.
- **Pandas**: Handles data processing and manipulation.

## Usage

To run the Stock Ticker Dashboard:

1. Clone the repository:
   ```bash
   git clone https://github.com/restynan/Stock-Dashboard.git

2. Navigate to the project directory:
   ```bash
   cd stock-ticker-dashboard

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

4. Run the application script:
   ```bash
   python app.py

5. Access the dashboard through the local server address:
   ```bash
   http://127.0.0.1:8050/
