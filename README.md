# TATA_DATA_VISUALISATION
The purpose of this report is to present a succinct overview of the key data preparation and analytical processes undertaken within retail dataset. The dataset under consideration comprises several essential columns, including InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, Amount, CustomerID, and Country.

1. Data Loading:
   - The initial step in the analysis involved the successful loading of the dataset into the Power BI environment.
2. Data Cleansing:
   - The integrity of the data was maintained through a meticulous process that addressed null values within the CustomerID and InvoiceNo columns.
3. Data Filtering:
   - Filtering measures were applied to exclude data points exhibiting negative or subzero values within the Price and Quantity columns.
4. Feature Engineering:
•	To facilitate time-based analysis, new attributes, namely 'Month' and 'Week,' were derived from the InvoiceDate column.
•	A pivotal metric, 'Total Sales,' was computed as the product of Quantity and Unit Price.
5. RFM Score Computation:
   - The RFM (Recency, Frequency, Monetary) scoring system was diligently implemented to categorize customers based on their transactional behavior.
6. Pareto Analysis:
   - A comprehensive analysis was conducted to determine the Pareto percent, thereby offering insights into the relative contribution of each country to the overall sales and quantity.


![report](https://github.com/ShivarajPatilaa/TATA_DATA_VISUALISATION/assets/131588848/660d9e01-46e8-4a2b-ab8a-9beeb7dc7746)
