# crypto_currencies

##
Purpose

###
The purpose of this analysis is to use unsupervised machine learning to assist an important client, a prominent investment bank, in creating a
classification system for their trading cryptocurrencies portfolio. 

##
Overview

###
The client provided a dataset that included trading and non-trading cryptocurrencies, as well as other information such as Coin Name, Total Supply and 
Total Coins Mined. Below is a summary of the procedures performed. 

•	Dataset was processed by removing non-trading cryptocurrencies and null values. 

•	Dataframe was created and all columns were converted to numerical values, as needed. 

•	Data was scaled

•	PCA was used to reduce the number of dimensions, number of components was set to 3

•	Elbow curve was created

•	K-Means model was ran, number of clusters was set at 4

•	Results were plotted using a 3D scatter
