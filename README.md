# Stock Market Dashboard

A modern, interactive stock market dashboard built with **HTML**, **CSS**, and **JavaScript**. This application allows users to search for stocks, view price data, track changes, and manage a personalized watchlist.

## ✨ Features

- 📈 **Interactive Stock Charts** - Real-time line charts powered by Chart.js showing stock price trends
- 🔍 **Stock Search** - Search for any stock by ticker symbol (e.g., AAPL, TSLA, AMZN)
- 💰 **Live Price Display** - Shows current price, percentage change, and trading volume
- ⭐ **Quick Watchlist** - Pre-loaded with popular stocks (Apple, Tesla, Amazon, Microsoft)
- 🎨 **Dark Theme UI** - Modern, sleek dark interface optimized for market data visualization
- ♻️ **Auto-Refresh** - Dashboard updates every 5 seconds automatically for fresh data

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Usage

1. **Open the Application**
   - Simply open `stocks.html` in your web browser

2. **Search for a Stock**
   - Enter a stock ticker symbol in the search box (e.g., AAPL)
   - Click the "Search" button to load the stock data

3. **View Stock Information**
   - **Price**: Current stock price
   - **Change**: Percentage change in price (color-coded: green for positive, red for negative)
   - **Volume**: Trading volume for the stock

4. **Use the Watchlist**
   - Click on any stock name in the watchlist (Apple, Tesla, Amazon, Microsoft)
   - The chart and stats will update instantly

5. **Auto-Refresh**
   - The dashboard automatically refreshes data every 5 seconds

## 📁 Project Structure

```
Stock-Market-Dashboard/
├── README.md          # Project documentation
└── stocks.html        # Complete application (HTML + CSS + JavaScript)
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, flexbox, and grid layouts
- **JavaScript (ES6)** - Dynamic functionality and interactivity
- **Chart.js** - Beautiful, responsive chart library (CDN)

## 💻 UI Components

### Header
- Application title with emoji indicator
- Search input field
- Search button

### Stats Section
- Price card - Current stock price
- Change card - Percentage change with color coding
- Volume card - Trading volume

### Main Container
- **Chart Area** (3/4 width) - Line chart showing price trends
- **Watchlist** (1/4 width) - Quick-access list of popular stocks

## 🎨 Color Scheme

- **Background**: Dark slate (#0f172a)
- **Cards**: Darker slate (#1e293b)
- **Primary Button**: Blue (#3b82f6)
- **Positive Change**: Green (#22c55e)
- **Negative Change**: Red (#ef4444)
- **Text**: White

## 📊 Data Updates

- Auto-refresh interval: **5 seconds**
- Chart data points: **10-point moving window**
- Price range: Randomly generated between $100-$150 (demo data)

## 🔮 Future Enhancements

- ✅ Integration with real stock market APIs (Alpha Vantage, IEX Cloud, Finnhub)
- ✅ Historical data analysis and technical indicators (MA, RSI, MACD)
- ✅ Portfolio tracking and performance metrics
- ✅ User authentication and persistent watchlists
- ✅ Mobile responsive design
- ✅ Additional stock indices (S&P 500, Nasdaq, Dow Jones)
- ✅ Price alert notifications
- ✅ Stock comparison tools

## 📝 Notes

- **Current Status**: Uses simulated/demo data for demonstration
- **For Production**: Replace data generation with actual API calls to real-time stock data providers
- **Browser Compatibility**: Works on all modern browsers supporting ES6

## 📄 License

Open source project available for educational and personal use.

---

**Happy Trading!** 📈

For questions or suggestions, feel free to open an issue or contribute to the project.