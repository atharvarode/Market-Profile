# Market Profile Analysis with Python

![Market Profile]![market_profile](https://github.com/atharvarode/Market-Profile/assets/97606863/9e3744dc-4296-4aa9-995b-805c360404f1)


This project focuses on Market Profile analysis using Python. Market Profile is a tool used by traders to visualize price movement and understand the distribution of trading activity. In this project, we leverage Python and libraries like yfinance for data retrieval, NumPy and Pandas for data cleaning, and Seaborn and Matplotlib for visualization. We aim to display price, volume, and time frame in a single chart, indicating the value area and POC (Point of Control) for a stock. Additionally, we identify trends where there are high concentrations of transactions with respect to the price of the stock.It helps traders identify areas of value, support, and resistance.


## Algorithm

### Letter Allocation in Market Profile:

1. **Price Levels**:

   Market Profile divides the price levels into distinct increments or "TPOs" (Time Price Opportunities). Each TPO represents a price level at which trading occurred during a specific time period.<img width="167" alt="tpo1" src="https://github.com/atharvarode/Market-Profile/assets/97606863/d5cfddf4-05ab-4ddf-b286-cc4f89094fc7">

   

3. **Letter Assignment**:
   - **Single Letters (A, B, C, etc.):** These represent the initial letters assigned to each TPO during a trading session.
   - **Split Letters (e.g., A/B, B/C, etc.):** If trading spans multiple price levels within a TPO, the letter can be split to indicate higher or lower value within that TPO.
<img width="175" alt="tpo2" src="https://github.com/atharvarode/Market-Profile/assets/97606863/7409e3a7-1e45-427f-94da-30d4b2631ad8">

### Basic Algorithm for Market Profile:

1. **Data Collection**:
   - Collect price and volume data for a specified time period (e.g., a trading session).

2. **Price Level Segmentation**:
   - Divide the price range into equal increments or "TPOs". These are represented by individual letters.

3. **TPO Calculation**:
   - For each TPO, determine the price level where the most trading activity occurred during the specified time period.

4. **Letter Assignment**:
   - Assign a letter to each TPO based on the price level with the most trading activity. This is typically done from the highest traded price level to the lowest.

5. **Display as Histogram**:
   - Display the allocated letters as a histogram. The width of each letter corresponds to the amount of trading activity at that price level.

6. **Analysis**:
   - Traders analyze the Market Profile to identify areas of value, support, and resistance. They look for patterns, anomalies, and potential trading opportunities.


## Technologies Used

- Python 
- NumPy 
- Pandas 
- Seaborn 
- Matplotlib 
