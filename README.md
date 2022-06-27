# Cryptocurrencies
 The purpose of this analysis was to use supervised machine learning to analyze cryptocurrencies in order to make the most educated decision for potential clients who are looking to invest in crypto.
 
 ## Analysis
  In order to minimize the amount of outliers or less useful data, our data was first cleaned before starting the analysis. To narrow down or results I did three things:
  
  - Only included cryptocurrencies that are currently being traded
  - Dropped Null values
  - Only included cryptocurrencies with a working algorithm
  
  As a result, the clean dataframe below was created
  
  ![clean_df](https://github.com/JTGonzaga/Cryptocurrencies/blob/main/Analysis/cleaned_df.png)
  
  This clean dataset was then analyzed using Principal Component Analysis in order to reduce the number of dimensions to contain the most amount of information without having excess data. This was then put into a elbow curve model using hvplot to find the most ideal number of clusters to plug into our machine learning algorithms. 
  
  ![elbow](https://github.com/JTGonzaga/Cryptocurrencies/blob/main/Analysis/eblow.png)
  
 The elbow curved showed an ideal K-Value of 4 which means that I'll use 4 as my value for the amount of clusters.
 
 This data was then shown in 3 different graphs
 
 ### Table of Tradable Cryptocurrencies
 ![tradable](https://github.com/JTGonzaga/Cryptocurrencies/blob/main/Analysis/tradable_table.png)
 
 ### 2-D Plot
 ![2D](https://github.com/JTGonzaga/Cryptocurrencies/blob/main/Analysis/2d_plot.png)
 
 ### 3-D Plot
 ![3D](https://github.com/JTGonzaga/Cryptocurrencies/blob/main/Analysis/3d_plot.png)
 
 ## Results
 Our results showed a total of 532 tradable cryptocurrencies out of all the data we analyzed. This narrowed down the original 1,252 cryptocurrencies and allows further research to be more focused and calculated.
