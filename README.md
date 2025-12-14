Lumina Crypto Tracker
A beautiful, privacy-focused cryptocurrency dashboard that runs entirely in your browser. Track your portfolio,
visualize market trends, and estimate potential tax liabilities without sending your data to any server.

🌟 Features
Real-Time Tracking: Live price updates for major cryptocurrencies (BTC, ETH, SOL, etc.) using the CoinGecko
API.
Privacy First: All portfolio data is stored locally in your browser ( localStorage ). No accounts, no database,
no tracking.
Interactive Charts: * Toggle between 7-day, 30-day, and 1-year history.
Logarithmic scale support.
Visual indicators for period Highs and Lows.
Toggle specific assets on/off the main chart.

Smart Tax Estimator:
Estimate capital gains/income tax based on your location.
New Zealand Mode: Specifically calculates using NZ progressive income tax brackets (10.5% - 39%).
Supports USA (Short/Long term), UK, Australia, Germany, and India.
Adaptive UI: Fully responsive design with a built-in Light/Dark mode toggle.

🚀 How to Use
Running Locally
1. Download the crypto_tracker.html file.
2. Open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. That's it! The app will start fetching data immediately.
Hosting on GitHub Pages
1. Upload the file to a GitHub repository.
2. Rename the file to index.html .
3. Go to Settings > Pages and enable GitHub Pages on the main branch.
4. 
🛠Technologies Used
HTML5 & JavaScript (ES6+): Core logic and structure.
Tailwind CSS: For styling, glass-morphism effects, and responsive layout.
Chart.js: For rendering the interactive price history graphs.
Phosphor Icons: For the clean, modern iconography.
CoinGecko API: For fetching free, public market data (no API key required for basic use).

⚠️ Disclaimer
This tool is for informational purposes only.
Not Financial Advice: The tax estimator provides a rough estimate based on standard brackets; it does not
account for deductions, specific financial situations, or tax law changes. Always consult a qualified accountant.
Data Persistence: Since data is stored in your browser's local storage, clearing your browser cache will delete
your portfolio data.
📄 License
Open source. Feel free to modify and use for your own personal finance tracking.
