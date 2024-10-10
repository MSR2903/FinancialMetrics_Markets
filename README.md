# Financial Metrics and Global Stock Market Analysis
This project explores how U.S. economic metrics (such as GDP, inflation rate, and unemployment rate) impact the performance of major world stock exchanges. Using Python and the FRED API, we retrieve economic data and compare it with stock price data obtained via the Yahoo Finance API.

Data that retreived from FRED API:
1. Gross Domestic Product (GDP) ('GDP'):
Measures the total monetary value of all goods and services produced within a country over a specific time period. It’s a key indicator of the overall economic health and growth of a nation.

2. Unemployment Rate ('UNRATE'):
Represents the percentage of the labor force that is unemployed and actively seeking work. A rising unemployment rate signals economic distress, while a falling rate suggests economic growth and job creation.

3. Consumer Price Index (CPI) ('CPIAUCSL'):
Tracks the change in the price of a basket of consumer goods and services over time. It's used to gauge inflation, showing how much prices are rising or falling, which impacts purchasing power.

4. Federal Funds Rate ('FEDFUNDS'):
This is the interest rate at which banks lend money to each other overnight. It is a key tool used by the Federal Reserve to influence monetary policy, impacting borrowing costs, inflation, and economic growth.

5. Consumer Confidence Index (CCI) ('UMCSENT'):
Measures the degree of optimism that consumers feel about the overall state of the economy and their personal financial situation. High consumer confidence typically leads to more spending, which drives economic growth.

This project will compare these 5 U.S. Economic Metrics with the top 10 stock exchanges in the world by market capitalization. We retrieve the data from Yahoo Finance, which can be seen here:

1. **New York Stock Exchange (NYSE)** – USA  
   - Yahoo Finance Ticker: `^NYA`

2. **Nasdaq** – USA  
   - Yahoo Finance Ticker: `^IXIC`

3. **Japan Exchange Group (Tokyo Stock Exchange)** – Japan  
   - Yahoo Finance Ticker: `^N225`

4. **Shanghai Stock Exchange** – China  
   - Yahoo Finance Ticker: `000001.SS`

5. **National Stock Exchange (NSE) of India** – India  
   - Yahoo Finance Ticker: `^NSEI`

6. **Euronext** – Europe (France, Netherlands, Belgium, Portugal)  
   - Yahoo Finance Ticker: `^N100`

7. **Hong Kong Exchanges and Clearing** – Hong Kong  
   - Yahoo Finance Ticker: `^HSI`

8. **Shenzhen Stock Exchange** – China  
   - Yahoo Finance Ticker: `399001.SZ`

9. **Toronto Stock Exchange (TMX Group)** – Canada  
   - Yahoo Finance Ticker: `^GSPTSE`

10. **Korea Exchange** – South Korea  
    - Yahoo Finance Ticker: `^KS11`

