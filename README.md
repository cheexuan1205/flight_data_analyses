# Flight Data Analyses and Flight Delays Prediction (Project of Programming for Data Science)
This is a project of Programming for Data Science which is analysing the US airlines data and predicting the arrival delays using several machine learning classification algorithms. (logistic regression, penalised logistic regression, gradient boosting, classification trees, random forest, support vector machine (SVM), k-nearest neighbors (KNN) classifier, naïve bayes classifier)

You may download the detail report of my analyses based on the flight data of the years from 2004 to 2006 below and have a look on my Python, R codes and SQL commands for answering the questions.

## 1 Introduction 
Nowadays, air transportation has become more popular compared to the 20th century. It
plays a vital role in fostering globalisation in the 21st century. Many people still have to travel
to other countries for work, study and other purposes even during Covid-19 pandemic. The
flight data that is used to analyse and discover hidden patterns are from the Harvard
Dataverse and it contains flight arrival and departure details.

## 2 Data
The 2009 ASA Statistical Computing and Graphics Data Expo consisted of flight arrival and departure
details for all commercial flights on major carriers within the USA, from October 1987 to April 2008.
This is a large dataset; there are nearly 120 million records in total, and takes up 1.6 gigabytes of space
compressed and 12 gigabytes when uncompressed. The complete dataset along with supplementary
information and variable descriptions can be downloaded from the Harvard Dataverse at
https://doi.org/10.7910/DVN/HG7NV7

If you wish to run my codes, you may download the data of the years from 2004 to 2006 and 3 supplementary data from the website mentioned above as it is too large to upload here. (2004.csv.bz2, 2005.csv.bz2, 2006.csv.bz2, airports.csv, carriers.csv, plane-data.csv)

## 3 Tasks
Question 1: When is the best time of day, day of the week, and time of year to fly tominimise delays? 

Question 2: Do older planes suffer more delays? 

Question 3: How does the number of people flying between different locations change over time?

Question 4: Can you detect cascading failures as delays in one airport create delays in others? 

Question 5: Use the available variables to construct a model that predicts delays.

## 4 Proposed Technique 
I have used Python, R programming and DB Browser for SQLite.

Firstly, I have created a database using SQLite through R programming and Python respectively. I
created 4 tables in the database with the names “delays”, “airports”, “carriers’ and “planes”.
The “delays” table is the main data set of the flight details and I decided to analyse 3
consecutive years of flight data from the year 2004 to 2006 in all the following analyses. The
other 3 supplementary data are about airport details, carrier details and planes’ information
respectively and will be used in the following analyses.

While answering all the 5 questions, I am assuming from the flight customer's perspective to
better cater their thoughts and needs. Exploratory data analysis with tables and graphics will
be carried out within each question after the data extraction from database, data
pre-processing and data preparation are done. In question 5, I will make a flight arrival delay
prediction using machine learning classification algorithms with some most relevant and
accessible features when making the future flight arrival delay prediction.

## 5 Flight Data Analyses 
All questions have been answered using R and Python for all tasks.

I have performed Exploratory Data Analysis (EDA) using R programming and Python to answer 5 interesting questions and hidden patterns from the flight data.

The details of my analyses can be found in the pdf file below.

[Report of Flight Data Analyses and Flight Delays Prediction.pdf](https://github.com/cheexuan1205/flight_data_analyses/files/8490442/Report.of.Flight.Data.Analyses.and.Flight.Delays.Prediction.pdf)

© 2022 YUI CHEE XUAN
