# Cryptocurrencies

Cryptocurrencies analysis using unsupervised machine learning.

## Project Overview

## Background: Accountability Accounting

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked me to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Software:

• VS Code

• Jupyter Notebook

• Pandas

# Data Source:

• [crypto_data.csv](https://github.com/muurid1/Cryptocurrencies/files/9864255/crypto_data.csv)

• crypto_clustering_starter code


## Results

###  Preprocessing the Data for PCA

<img width="514" alt="crypto_df" src="https://user-images.githubusercontent.com/107282754/198173898-31282a4a-df1b-42dc-b710-914a4ffb1983.png">


### Reducing Data Dimensions Using PCA

#### create DataFrame to reduce the dimensions using three principal components: PC 1, PC 2 and PC 3

<img width="318" alt="PCA" src="https://user-images.githubusercontent.com/107282754/198173990-2894641c-8407-4122-9738-ca2a2fd3c7ff.png">

### Clustering Cryptocurrencies Using K-means

#### Clustered_df

<img width="896" alt="Clustered_df" src="https://user-images.githubusercontent.com/107282754/198174263-cbfcbc2a-9cde-499e-965a-6263ae2f4254.png">

#### Elbow curve using K-Means

<img width="1030" alt="Elbow_curve" src="https://user-images.githubusercontent.com/107282754/198174154-380288fb-8591-4b56-ba92-cc11997420a7.png">

### Visualizing Cryptocurrencies Results

#### hvplot

<img width="747" alt="hvplot scatter" src="https://user-images.githubusercontent.com/107282754/198174339-a522f4e8-c6f2-4fd2-801c-6e508bda9c1c.png">

#### 3D-scatterplot

<img width="1247" alt="3D-scatter" src="https://user-images.githubusercontent.com/107282754/198174349-9c394329-57c8-43aa-9805-24fdd9331a52.png">

