# Financial Metrics and Global Stock Market Analysis
This project explores how U.S. economic metrics (such as GDP and Consumer Price Index) impact the performance of major world stock exchanges. Using Python and the FRED API, we retrieve economic data and compare it with stock price data obtained via the Yahoo Finance API.

## Hypothesis and Research Questions
Hypotheses:
1. The NYSE (U.S Stock Exchange) have stronger correlation or more senstive with the U.S Economic metrics than the International exchanges with the U.S Economic metrics.
2. Stock exchanges in developed countries show a stronger correlation or more sensitve to the U.S. economic metrics compared to those in developing countries.
3. The performance (NYSE) of U.S. stock exchanges is more sensitive to the U.S. CPI than international stock exchanges.
4. Stock exchanges in developed countries show a stronger correlation with the U.S. CPI metrics compared to those in developing countries

Research Questions:
1. How does U.S. economic metrics influence the performance of U.S. stock exchanges compared to international stock exchanges?
2. Do stock exchanges in developed countries show a stronger correlation with U.S. economic metrics than those in developing countries?
3. How does U.S. CPI influence the performance of U.S. stock exchanges compared to international stock exchanges?
4. Do stock exchanges in developed countries show a stronger correlation with U.S. CPI than those in developing countries?

Data that retreived from FRED API:
1. Gross Domestic Product (GDP) ('GDP'):
Measures the total monetary value of all goods and services produced within a country over a specific time period. It’s a key indicator of the overall economic health and growth of a nation.

2. Consumer Price Index (CPI) ('CPIAUCSL'):
Tracks the change in the price of a basket of consumer goods and services over time. It's used to gauge inflation, showing how much prices are rising or falling, which impacts purchasing power.

This project will compare these 2 U.S. Economic Metrics with the top stock exchanges in the world by market capitalization. We want to compare the impact of U.S. Economics for both developed countries and developing countries.

We retrieve the data from Yahoo Finance, which can be seen here:

Developed Countries:
1. **New York Stock Exchange (NYSE)** – USA  
   - Yahoo Finance Ticker: `^NYA`

2. **Japan Exchange Group (Tokyo Stock Exchange)** – Japan  
   - Yahoo Finance Ticker: `^N225`

3. **Euronext** – Europe (France, Netherlands, Belgium, Portugal)  
   - Yahoo Finance Ticker: `^N100`

4. **Toronto Stock Exchange (TMX Group)** – Canada  
   - Yahoo Finance Ticker: `^GSPTSE`

5. **Korea Exchange** – South Korea  
    - Yahoo Finance Ticker: `^KS11`

Developing Countries:
1. **Shanghai Stock Exchange** – China  
   - Yahoo Finance Ticker: `000001.SS`

2. **National Stock Exchange (NSE) of India** – India  
   - Yahoo Finance Ticker: `^NSEI`

3. **Saudi Stock Exchange** – Saudi Arabia
   - Yahoo Finance Ticker: `TASI.SR`

4. **Johannesburg Stock Exchange** – South Africa
   - Yahoo Finance Ticker: `JSE.JO`

5. **Brazil Stock Exchange** – Brazil
   - Yahoo Finance Ticker: `^BVSP`





