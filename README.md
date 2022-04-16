# Sales Data Analysis for Company XYZ

This project is an analysis of three months sales data for three branches of a supermarket company (Company XYZ) located at Port Harcourt, Lagos and Abuja respectively.  

# Project Steps

The sales data for each of the Supermarkets were contained in three different csv files which were concatenated into a pandas dataframe and used subsequently for the necessary analysis. The analysed dataframe contained 1000 unique rows of customer data with 17 columns. The data was first analysed for occurences of missing values and it was found that there was none. Subsequently, the pandas describe method was used to obtain a statistical summary of the dataframe. Moving on, pandas datetime methods were used to explore and extract features from the date column before groupby was used to draw insights from aggregated data. Finally, different plots from the seaborn visualisation library were used to generate charts and obtain important insights from the data. 

# Insights
1. The supermarkets open for ten hours each day beginning at 10am and closing at 8pm.
1. Port Harcourt had the highest gross income and rating of the three cities followed by Lagos. However, Abuja had the highest number of sales records followed by Lagos.
2. The most used payment method across the three supermarkets was Epay closely followed by cash. Card payments were the least used. The trend was identical for Abuja and Lagos respectively. In Port Harcourt however, card payments ranked highest followed by Epay and then cash. Moreover, Lagos had the highest Epay and card payments, while Port Harcourt accepted the most cash payments. Port Harcourt also recorded the lowest number of card and Epay payments.
3. Despite ranking as the most used method of payment, Epay did not have the highest payment volume. The highest payments volumes were obtained via cash payments while card payments accounted for the least volume of payments.
4. Fashion accessories and home and beauty products were the most sold and least sold products respectively
5. Men and women patronised the supermarkets an almost equal amount of time. Whereas females bought more fashion accessories, food and beverages, and sport and travel equipment, the other three product lines were more frequently patronised by men.
6. Products with a higher average unit price were purchased less than products with a lower average unit price.


# Standout Section

1. Payment volume per channel - the total volume of payments obtained via each payment channel was determined as merely knowing th enumber of transactions per each channel may not tell the full story. 

# Executive Summary.
The recorded data for the three branches of Company XYZ supermarkets included data obtained from 1st January to 30th March, 2019. 