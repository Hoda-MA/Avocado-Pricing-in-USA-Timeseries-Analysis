# Avocado-Pricing-in-the-USA-Timeseries-Analysis

his Project reviews the Avocado's price-anomalies in US States over period of three years. This is a timeseries analysis, therefor we have a chronological set of data. The prices have been recorded over time and we want to undestand if the price is increasing or descreasing in the future by doing forcastion.
Sources: The Dataset of Avocado pricing (as a csv. file) is available on the Kaggle.com. you can find it also under the same folder.

The Avocado's type are organic and conventional. It would be intersting to see if the prices of each will be different over time and if the forcasting shows a reduction or an increase in the prices in the future.

![1](https://user-images.githubusercontent.com/64262003/115572366-1e421580-a2c0-11eb-8163-8f01a9b8ede5.png)

As expected the organic sort has a higher price.

On the diagram below, we have have seperated the price records for each year. 
![download](https://user-images.githubusercontent.com/64262003/115572683-695c2880-a2c0-11eb-836e-d636bbcb7b2b.png)
This reveals that the year 2017 had the highest fluctuation in price and also the highest and lowesr price.

For doing the forcasting, there are several methods in time series. here we have studied some of them. In this picture we see the result of Moving Average and our Test-train split.
![download (1)](https://user-images.githubusercontent.com/64262003/115575051-7c6ff800-a2c2-11eb-97a2-f914da05c3a5.png)
We see clearly that the MA results are further near to the real data rather than the test data.

# Correlation
In my opinion, heat map is the easiest way to  have the first overview of correlation between our data. 
![download (2)](https://user-images.githubusercontent.com/64262003/115577039-5d726580-a2c4-11eb-8d68-aff82624fb4d.png)

The clolumns total volume and average price have actually a negative correlation. In order to approve it, we visualize our data:
![download (3)](https://user-images.githubusercontent.com/64262003/115577347-a32f2e00-a2c4-11eb-91d1-6a7d145006a9.png)

