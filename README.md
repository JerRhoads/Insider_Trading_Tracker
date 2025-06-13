# Insider_Trading_Tracker
Monitors SEC Form 4 filings using HTML, JavaScript, and the SEC EDGAR API. 

Key Features:
## Trading Analysis

Search by ticker symbol with customizable date ranges
Filter by minimum trade amounts
Real-time dashboard with key metrics
Buy/sell ratio analysis and unique insider tracking

## Interactive Interface

Modern, responsive design with gradient backgrounds
Interactive filters (All trades, Purchases, Sales, Executives)
Hover effects and smooth animations
Mobile-friendly responsive layout

## Data Visualization

Total trades and volume metrics
Buy/sell ratio indicators
Color-coded positive/negative trends
Detailed trade breakdowns with insider information

## Smart Alerts

Configurable notifications for high-value trades (>$1M)
Executive trading alerts for CEOs/CFOs
High-volume trade notifications
Real-time pop-up notifications

## Export Functionality

CSV export with complete trade data
Formatted reports for further analysis
Date-stamped file naming

Technical Implementation:
The tracker uses HTML5, CSS3, and vanilla JavaScript for maximum compatibility. While it currently uses mock data for demonstration (since the SEC EDGAR API has CORS restrictions), the structure is ready for real API integration.
For Production Use:

## Implement server-side proxy for SEC EDGAR API calls
Add authentication headers (User-Agent required by SEC)
Parse actual XML Form 4 filings
Implement rate limiting (SEC allows 10 requests/second)

