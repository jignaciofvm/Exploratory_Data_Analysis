# WHAT MAKES PEOPLE HAPPY?

The World Happiness Report is a survey of the state of global happiness. The happiness scores (0-10) are based on answers to the main life evaluation question asked in the poll.

The Dataset contained several variables such as GDP per capita, Family (Social Support), Life Expectancy, etc.

Our goal with this dataset is to understand what are the factors that drive the country happiness as well as find patterns among countries.

The main conclusions of the analysis were:
* Due to the fact that It exists a strong correlation between the Happiness Score and variables such as GDP per capita, Life Expectancy and Social Support, we could say that the richer the country, the happier. Also, the correlation is less strong with Freedom and Corruption.
* On the other hand, there is a small (non-existent) correlation between Happiness Score and Generosity, which seems a surprised to me.
![image](https://user-images.githubusercontent.com/77568333/111897218-0ce6be80-8a1f-11eb-9c97-767640b778ba.png)
* After doing an unsupervised learning with a clustering analysis (k-means method), we reach the conclusion that the best way to divide the 156 countries in the dataset were with four clusters. And, in the following box-plot, we can see the Happiness Score discrepancies among clusters.
![image](https://user-images.githubusercontent.com/77568333/111897237-26880600-8a1f-11eb-9e45-e662b4c065d6.png)
* As shown above, the main differences exist between cluster 1, where the happiest countries have been classified, and cluster 3 (The least happy countries). We can see this discrepancies in other variables such as GDP per capita.
![image](https://user-images.githubusercontent.com/77568333/111897256-3acc0300-8a1f-11eb-8702-cc019893af8e.png)
* However, we represent variables that didn’t have a correlation with Happiness Score (Generosity, for example), we will see that there are no significant differences among countries / clusters.
![image](https://user-images.githubusercontent.com/77568333/111897268-4a4b4c00-8a1f-11eb-8ad4-3b3adbc6c0cf.png)
* To conclude, we will represent in a map the countries distributed by cluster. We can see that the happiest countries (Cluster 1, represented with purple colour) are Canada, Australia or North European Countries (among others) and, on the other hand, we have cluster 3 (represent with orange colour) with countries such as Pakistan, Nigeria, Gambia, etc. Cluster 2 and Cluster 3 are represented with purple and yellow colour, respectively. Note: Some African Countries are missings. They will be included in further updates of the notebook.
![image](https://user-images.githubusercontent.com/77568333/111897277-5a632b80-8a1f-11eb-85a5-2f53d089a9df.png)
