## <h2 align="center"> <hr/>Predict Forcast Sell using MongoDB and Machine Learning<hr/> </h2>

<h2 align= "center">Introduction</h2>
 
> <p align="justify"> MongoDB is an open-source document database and leading NoSQL database.MongoDB is written in C++.In our project we have analysed the output of the queries of real-world scenarios in the MongoDB . In order to understand the market better we have also tried to predict the future sales of the supermarket dataset using various Machine Learning Algorithm.</p>

<h2 align= "center">Problem Statement </h2>
 
> <p align="justify"> The supermarkets are the one stop destination for all the city folks to explore new products that have arrived in the marketplace. The dataset that we have of the supermarket is of 3 branches in the city and is composed for a time period of three months. Our main aim is to analyse the database using the Machine Learning Models and apply K Means and Prophet is applied to forecast the sales of the next 15 days. Primarily MongoDB has been used to query the relevant solutions to the technical questions on the dataset.</p>

<h2 align= "center">Solution Approach</h2>
 
> <p align="justify"> The dataset has been loaded on MongoDB then the pre-processing has been applied on the dataset to remove the null values. Also the Date parameter is processed to view the date in the correct Date Time object to be processed further. MongoDB queries have been written to resolve the real world queries to analyse the market dataset and also analyse the output for the respective questions. Then in order to predict the sales of the market analysis the dataset is divided into training dataset and testing dataset in order to predict the sales for the next 15 days using the Machine Learning Algorithm.</p>

<h2 align= "center"> Flow Diagram of purposed solution:</h2>
<img src="./Image/Flow Chart.png" alt="iagrammatic Approch for the workflow of proposed methodology" width="100%" height="600px"/>

> _Diagrammatic Approch for the workflow of proposed methodology._

> <p align="justify"> The dataset has been loaded on MongoDB then the pre-processing has been applied on the dataset to remove the null values. Also the Date parameter is processed to view the date in the correct Date Time object to be processed further. MongoDB queries have been written to resolve the real world queries to analyse the market dataset and also analyse the output for the respective questions. Then in order to predict the sales of the market analysis the dataset is divided into training dataset and testing dataset in order to predict the sales for the next 15 days using the Machine Learning Algorithm.</p>

<h2 align= "center">DataSet</h2>

> <p align="justify">The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket
> company which has recorded in 3 different branches for 3 months data. Predictive data analytics methods are easy to apply with this dataset.</p>

> ### Attribute information:
>
> > - **<p align="justify"> Invoice id:** Computer generated sales slip invoice identification number </p>
> > - **<p align="justify"> Branch:** Branch of supercenter (3 branches are available identified by A, B and C).</p>
> > - **<p align="justify"> City:** Location of supercenters.</p>
> > - **<p align="justify"> Customer type:** Type of customers, recorded by Members for customers using member card and Normal for without member card.</p>
> > - **<p align="justify">Gender:** Gender type of customer </p>
> > - **<p align="justify"> Product line:** General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel</p>
> > - **<p align="justify"> Unit price:** Price of each product in $</p>
> > - **<p align="justify"> Quantity:** Number of products purchased by customer</p>
> > - **<p align="justify"> Tax:** 5% tax fee for customer buying. </p>
> > - **<p align="justify"> Total:** Total price including tax</p>
> > - **<p align="justify"> Date:** Date of purchase (Record available from January 2019 to March 2019)</p>
> > - **<p align="justify"> Time:** Purchase time (10am to 9pm)</p>
> > - **<p align="justify"> Payment:** Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet). </p>
> > - **<p align="justify"> COGS:** Cost of goods sold. </p>
> > - **<p align="justify"> Gross margin percentage:** Gross margin percentage. </p>
> > - **<p align="justify"> Gross income:** Gross income </p>
> > - **<p align="justify"> Rating:** Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)</p>

<h2 align= "center">Result</h2>

> <p align="justify"> The analysis and the prediction of sales for next 15 days has been achieved using MomgoDB queries and Machine Learning Algorithms. This predicted data can be used to make future decisions for the products in the different branches of the supermarket.</p>

<h2 align= "center">Conclusion</h2>

> > - <p align="justify"> We used uni-variate, bi-variate and correlation analysis to perform basic EDA on the supermarket sales data. </p>
> > - <p align="justify"> The customer rating is more or less uniform with the mean rating being around 7 and there is no relationship between gross income and customer ratings.</p>
> > - <p align="justify"> The data consists of 3 cities/branches. Though branch A has slightly higher sales than the rest, C i.e. Naypyitaw is the most profitable branch in terms of gross income.</p>
> > - <p align="justify"> Fashion accessories and food and beverages are the most sold product in Naypyitaw and these products should be focused on along with electronic accessories.</p>
> > - <p align="justify">The most popular payment method is E-wallet and cash payment is also on the higher side. </p>
> > - <p align="justify"> There is no particular time trend that can be observed in gross income.</p>
> > - <p align="justify">At an overall level, ‘Sports and Travel’ generates highest gross income.</p>
> > - <p align="justify"> Gross income is similar for both male and female, though female customers spend a bit higher at the 75th percentile. Females spend on ‘fashion accessories’ the most and for males surprisingly it is ‘Health and beauty’. Females also spend more on ‘Sports and travel’ which generates highest income overall.</p>
> > - <p align="justify"> Using the correlation analysis, one interesting observation has emerged that customer ratings is not related to any variable.</p>
> > - <p align="justify"> Most of the customers buy 10 quantities and busiest time of the day is afternoon i.e. around 2 pm which records highest sales. Sales is higher on Tuesdays and Saturdays compared to the rest of the week.</p>
> > - <p align="justify"> Though the rating for ‘fashion accessories’ and ‘food and beverages’ is high but the quantity purchased is low. Hence, supply for these products need to be increased.</p>

---

 <h2 align="center"> ** Thank YOU ** </h2> 
 
 ***
