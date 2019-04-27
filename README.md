# info474A2

##Exploratory Data Analysis

I chose a dataset on wine reviews that I found on Kaggle. I've delevoped a taste for certain wines recently so I am curious to learn more about which wines have the most value. I am also interested to see if the human palate can distinguish the difference between a "high quality" wine and a cheap wine because taste is subjective. I am hypothesizing that while there may be a slight increase in score per increase in price, there will be a lot of variability.

Initial Question:
Does price affect the wine's rating?

I created a scatterplot to visualize the points per price to see if there is a positive correlation between the two. While it is safe to say that there is a positive trend between the two variables, there also appears to be diminishing returns for the increase in quality to price anywhere beyond about $500

While the positive trend between price and points was apparent, there were a few outliers and low priced wines that scored 100. I didn't think price alone was a strong enough indicator of the wine's point value, so I decided to figure out what these outlier wines had in common that gave them higher points compared to the higher priced wines.

Before diving deeper into the exploratory data analysis I needed to check the distributions of the points and the prices. I created a histogram of the counts of each price (bins of 20) and points (bins of 1). The price had a right skewed distribution so I opted to using median for future price analysis. The points had a normal looking distribution so I decided that using mean would be appropriate.

I started by looking at the points awarded per variety of wine. I used a boxplot and sorted by descending points to discover the "best" varieties of wine. The top 5 wines that appeared were Chardonnays, Red Blends, Rieslings, Syrahs, and Merlots. I attributed this discovery to the high frequency of these common types of wines, which gives for more results which could increase the chances of better scoring wines appearing. Following this line of thought I figured that looking and sorting by the median would be more appropriate. The top 5 scoring wines by median were Tinta del Pais, Terrantez, Gelber Traminer, Sercial, and Riesling-Chardonnay.



Step 1. Pick a domain that you are interested in.
Some good possibilities might be the physical properties of chemical elements, the types of stars, or the human genome. Feel free to use an example from your own research, but do not pick an example that you already have created visualizations for.
Step 2. Pose an initial question that you would like to answer.
For example: Is there a relationship between melting point and atomic number? Are the brightness and color of stars correlated? Are there different patterns of nucleotides in different regions in human DNA?
Step 3. Assess the fitness of the data for answering your question.
Inspect the data--it is invariably helpful to first look at the raw values. Does the data seem appropriate for answering your question? If not, you may need to start the process over. If so, does the data need to be reformatted or cleaned prior to analysis? Perform any steps necessary to get the data into shape prior to visual analysis.
