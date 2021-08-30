# 02-stock-analysis

# **STOCK MARKET ANALYSIS**

Green energy is an emerging market as the transition to alternative energy generation is accelerating; increasingly, investors' focus is turning to this market. The purpose of the project is analyse green energy stock market performance of 12 companies in 2017 and 2018, to understand whether or not to invest.

As the stock market trades everyday, manage the size of this data manually will complicate the analysis, as part of the review an excel macro will be delivered to not only perform an analysis on the data set received, but also to be used in different years and different markets.

## **GREEN STOCK MARKET REVIEW**

In 2017 and 2018, the 12 companies traded between 3.2 and 3.3 billion shares each year. However, when comparing the opening with the closing price, in 2017 most of the companies generated positive return, while in 2018 only two generated positive return.

#### **Green stock market performance 2017 and 2018
![green_stock_performace_2017_2018](https://user-images.githubusercontent.com/88411170/131267945-e6df7173-2066-4e83-94ec-e2404e640f62.png)

When reviewing in detail there are only 2 companies generating return; ENPH traded 222 million shares in 2017 with positive 129.5% return and 607 million shares in 2018, also positive return 81.9%, while RUN in 2017 traded 268 million shares with 5.5% positive return and in 2018, 503 million with positife return as well of 84.0%. Being both ENPH and RUN, the ones with the strongest and healthier portfolio as volumes are increasing as well as the returns.

On the other hand, DQ and HASI volume of shares traded incrase year-on-year, but the return decrease, being an indicator of their portfolio gathered streghten to the downside, being portfolios to keep an eye on.

## **VBA STOCK ANALYSIS TOOL**

The green stock analysis was done by developing a macro to gather and display the data in a single page. 

A macro was develop by the programmer from scratch analyse the dataset, the outcome was fuilfilled and the data was gathered and displayed as desired; then a second, a refactored macro was develop to recycled standard code used to meet the same purpose.

Despite both macros are meeting the requirement of the client, the execution time was longer in the macro compared to the refactored macro. 

##### **Macro performance
<img width="273" alt="green_stocks_2017" src="https://user-images.githubusercontent.com/88411170/131267014-4f6f35b3-9513-46c1-9a6b-0cef391941df.png"> <img width="273" alt="green_stocks_2018" src="https://user-images.githubusercontent.com/88411170/131267029-0bbc00b9-19f9-42e4-999f-50a430e4ccf6.png">
The macro tooked about 0.3s to process the data, which might sound not much time when thinking of bigger sets of data this might delayed the analysis.

##### **Refactored macro performance
<img width="273" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/88411170/131267035-22112485-8d51-4691-94c5-b4ba70438916.png"> <img width="273" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/88411170/131267045-ae73fccb-92f0-4b93-83dd-4148c1d1b9d6.png">
The refactored macro tooked 6 times less processing the data, around 0.05 seconds.

At a first glance refactored VBA script improves the performance as it improves the performance as it reduces the time execution of the script by using standard set of code for standard can be faster, and can make easier understanding a code. However, when refactoring non standard set of code it can be dificult to program and to mantain, when switching code writer.

In general code refactoring can be useful, as saves a lot of time when the programs are executed, standardizes the way of writting and documenting the code, but depending on the complexity of the program it could be time consuming while writting the code and it can lead to errors; meaning that code refactoring is a powerful way to follow when code programming, but not in every single program and need to be single evaluated in each project.  
