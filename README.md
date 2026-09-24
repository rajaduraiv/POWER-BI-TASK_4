# POWER-BI-TASK_4

## Project Title

**Stock Price and Volume Analysis Dashboard**

## File Name

`POWER BI TASK_3(3).pbix`

## Description

This Power BI task focuses on analyzing stock price and trading volume data using interactive visualizations. The dashboard presents important stock price statistics, trading volume trends, moving averages, and date-based filtering.

The report was created using **Microsoft Power BI** to transform the available stock data into an interactive and easy-to-understand dashboard.

## Tools Used

* Microsoft Power BI Desktop
* Power Query
* DAX
* Data Visualization
* Data Modeling

## Operations Performed in Power BI

### 1. Data Loading

* Imported the stock-related data into Power BI.
* Used the stock data for price and volume analysis.
* Used a date dimension (`Dim_Date`) for date-based analysis.

### 2. Data Preparation

* Prepared the data for analysis using Power BI.
* Organized date and stock-related fields.
* Used the date field as the main category for time-based visualizations.

### 3. Data Modeling

* Used the `Dim_Date` table for date-related analysis.
* Used the `Shopify Stock` table for stock volume information.
* Created/used measures for important stock calculations.

### 4. DAX Measures

The report contains measures for:

* **Latest Close** – identifies the latest closing price.
* **Lowest Price** – identifies the lowest stock price.
* **Highest Price** – identifies the highest stock price.
* **Average Volume** – calculates the average trading volume.
* **Close Price** – used for stock price trend analysis.
* **20 Day Moving Average** – calculates the moving average over 20 days.
* **50 Day Moving Average** – calculates the moving average over 50 days.

### 5. KPI Cards

Four card visuals were created to display important summary values:

* Latest Close
* Lowest Price
* Highest Price
* Average Volume

These cards provide a quick overview of the stock data.

### 6. Date Slicer

A **Date Slicer** was added to the dashboard.

The slicer allows users to select a particular date or date range and dynamically filter the dashboard visuals.

### 7. Stock Price Trend Analysis

A line chart was created using:

* Date
* Close Price
* 20 Day Moving Average

This visual helps compare the actual closing price with its 20-day moving average.

### 8. 50 Day Moving Average Analysis

Another line chart was created using:

* Date
* Close Price
* 50 Day Moving Average

This allows the closing price trend to be compared with the 50-day moving average.

### 9. Trading Volume Analysis

A combination chart was created using:

* Date
* Sum of Volume

This visual represents how trading volume changes over time.

### 10. Price and Volume Comparison

A combination chart was also created to compare:

* Trading Volume
* Close Price
* Date

This provides a combined view of stock price movement and trading activity.

## Visualizations

<img width="1372" height="750" alt="Screenshot 2026-09-24 204345" src="https://github.com/user-attachments/assets/276c3cad-a446-4650-ac26-24bb0a453d45" />


## Visualizations Used

The report contains the following Power BI visuals:

| Visual      | Purpose                              |
| ----------- | ------------------------------------ |
| Card        | Display Latest Close                 |
| Card        | Display Lowest Price                 |
| Card        | Display Highest Price                |
| Card        | Display Average Volume               |
| Slicer      | Filter data by Date                  |
| Line Chart  | Close Price vs 20 Day Moving Average |
| Line Chart  | Close Price vs 50 Day Moving Average |
| Combo Chart | Date vs Trading Volume               |
| Combo Chart | Date vs Volume and Close Price       |

## Dashboard Features

* Interactive date filtering
* KPI summary cards
* Stock closing-price analysis
* Trading-volume analysis
* 20-day moving average analysis
* 50-day moving average analysis
* Combined price and volume analysis
* Interactive Power BI visuals

## Key Fields Used

### Dim_Date

* Date
* Close Price
* Latest Close
* Lowest Price
* Highest Price
* Average Volume
* 20 Day Moving Average
* 50 Day Moving Average

### Shopify Stock

* Volume

## Outcome

The completed Power BI report provides an interactive dashboard for understanding stock price movements and trading volume. Users can select dates using the slicer and analyze the corresponding stock information through KPI cards, line charts, and combination charts.

## Conclusion

This Power BI task helped in understanding data loading, data preparation, data modeling, DAX measures, slicers, KPI cards, line charts, combination charts, and time-based stock analysis. The final dashboard presents stock information in a clear and interactive format.
