# world-K-means
an application of ML K-means algorithm on world population and economy dataset


I merged six dataframes containing some information about population and economy of world countries with Fuzzywuzzy package of Python. 
Then builded K-means clustering algorithm on it and used Plotly for visualization.

The application divides the world map over the selected columns and a selected region with K-means and specified parameter k. 
We can select the relevant or irrelevant columns using the correlation heatmap. Also, K-Elbow Visualizer from Yellowbrick shows the best k parameter.

Plotly graphs were attached on repo because they don't show up on Github.

In the preparation of the study, I was inspired and benefited from the notebook 'https://www.kaggle.com/code/gcmadhan/unsupervised-learning-countries-need-finance' 
along with lots of web research.

Amaç dünya populasyonunun sosyal durumuyla ilgili etiketlenmemiş, yüksek sütunlu bir veri kümesi üzerinde birkaç parametrenin birlikte etkisini incelemektir. 
Burada veri setlerini 
