# NSE Equity Stock Screener — Python + Power BI

## What it does
Screens 200+ NSE-listed stocks by fundamental + technical criteria
and generates a ranked watchlist in under 60 seconds.

## Filters applied
- PE Ratio < 20 (value stocks only)
- Return on Equity > 15% (quality companies only)
- Debt-to-Equity < 1.0 (financially healthy companies)
- Market Cap > Rs.500 Crore (established companies only)
- RSI between 30-70 (not overbought or oversold)

## Tech stack
Python 3.x | yfinance | Pandas | OpenPyXL | Power BI Desktop

## How to run
1. pip install yfinance pandas openpyxl matplotlib
2. python screener.py
3. Open screener_results_final.xlsx in Power BI

## Sample output
STOCKS PASSING ALL FILTERS ===
Total qualifying stocks: 37
           Ticker                                        Company     Price   PE_Ratio  MarketCap_Cr
1         BPCL.NS           Bharat Petroleum Corporation Limited    281.00   4.880166      121912.0
2    COALINDIA.NS                             Coal India Limited    450.45   9.293377      277600.0       
3         ONGC.NS        Oil and Natural Gas Corporation Limited    284.65   9.416142      358098.0       
4         SBIN.NS                            State Bank of India    979.40  10.660716      904047.0       
5     HINDALCO.NS                    Hindalco Industries Limited    884.45  12.239828      197752.0       
6     AXISBANK.NS                              Axis Bank Limited   1161.30  13.774168      360923.0       
7        WIPRO.NS                                  Wipro Limited    187.64  14.856690      196743.0       
8     ADANIENT.NS                      Adani Enterprises Limited   1758.80  15.898040      239537.0       
9     HDFCBANK.NS                              HDFC Bank Limited    731.55  16.314674     1126097.0       
10   ICICIBANK.NS                             ICICI Bank Limited   1205.90  16.474045      863405.0       
11        INFY.NS                                Infosys Limited   1250.60  17.122124      506069.0       
12         ITC.NS                                    ITC Limited    287.70  17.693727      360473.0       
13         TCS.NS              Tata Consultancy Services Limited   2358.90  17.889427      853471.0       
14     DRREDDY.NS               Dr. Reddy's Laboratories Limited   1254.90  18.484314      104482.0       
15  HEROMOTOCO.NS                          Hero MotoCorp Limited   5063.00  18.622187      101305.0       
16   KOTAKBANK.NS                    Kotak Mahindra Bank Limited    353.40  18.688524      351474.0       
17   POWERGRID.NS        Power Grid Corporation of India Limited    296.10  19.017342      275391.0       
18        NTPC.NS                                   NTPC Limited    370.65  20.489220      359407.0       
19         M&M.NS                    Mahindra & Mahindra Limited   2954.70  21.141243      354704.0       
20       CIPLA.NS                                  Cipla Limited   1224.20  21.786795       98889.0       
21    RELIANCE.NS                    Reliance Industries Limited   1343.90  21.834282     1818629.0       
22     HCLTECH.NS                       HCL Technologies Limited   1341.60  22.124010      362990.0       
23  ADANIPORTS.NS  Adani Ports and Special Economic Zone Limited   1312.60  22.729004      302418.0       
24      MARUTI.NS                    Maruti Suzuki India Limited  12306.00  25.906822      386904.0       
25   TATASTEEL.NS                             Tata Steel Limited    191.86  26.103401      239285.0       
26       TECHM.NS                          Tech Mahindra Limited   1384.00  26.594927      122632.0       
27         UPL.NS                                    UPL Limited    567.95  27.096853       48008.0       
28  BAJAJFINSV.NS                             Bajaj Finserv Ltd.   1631.80  27.246620      260680.0       
29          LT.NS                        Larsen & Toubro Limited   3504.10  27.397186      482035.0       
30  BAJAJ-AUTO.NS                             Bajaj Auto Limited   8781.50  27.624334      245226.0       
31  BAJFINANCE.NS                          Bajaj Finance Limited    801.55  27.696959      498271.0       
32        LTIM.NS                                LTIMindtree Ltd   4504.00  28.090310      133516.0       
33   EICHERMOT.NS                          Eicher Motors Limited   6586.00  33.783020      180663.0       
34  BHARTIARTL.NS                          Bharti Airtel Limited   1782.40  35.211380     1085744.0       
35    JSWSTEEL.NS                              JSW Steel Limited   1122.50  36.900066      274211.0       
36      GRASIM.NS                      Grasim Industries Limited   2557.70  38.311863      173441.0       
37   SUNPHARMA.NS          Sun Pharmaceutical Industries Limited   1757.20  38.611294      421611.0       

Results saved to screener_results.xlsx
![Alt text](image-url)
<img width="1893" height="943" alt="Screenshot 2026-03-31 135438" src="https://github.com/user-attachments/assets/5c99157a-dac8-42f1-b575-6c4966ef11fc" />

