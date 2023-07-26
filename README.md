# uber-pandas-analysis
Basic data analysis and visualization using pandas. 

For this project, I used a dataset from Kaggle entitled "Uber Data Analysis🚗 🚕" (link: https://www.kaggle.com/datasets/bhanupratapbiswas/uber-data-analysis). The dataset contains information related to specific Uber rides, including their start and end timestamps, starting and ending locations, ride category and purpose, etc.

Upon a brief overview of the data, I formulated the following Uber stakeholder questions to analyze: 
  Question 1: What are the top 20 most popular starting cities? 
  Question 2: Which five starting cities have the highest average ride length? 
  Question 3: What is the average speed of each ride in miles per hour? 
  Question 4: How does the average miles per hour compare among ride purposes?
  Question 5: What percentage of business rides start and stop in the same city?

I answered these questions using the Python pandas package. I used a Jupyter notebook as the coding environment. The general workflow is as follows: 
  1. Download the Kaggle Zip file for the dataset.
     NOTE: In future projects, I will demonstrate how to interact with the Kaggle API to download datasets directly from Kaggle to the Jupyter notebook.
  2. Unzip the Zip file to gain access to the .csv that contains our dataset.
  3. Read the .csv into a pandas DataFrame.
  4. Perform some basic data cleansing and transformation, including dropping unneccesary rows, editing column names, changing data types, and identifying columns with missing values.
  5. Answer our five questions using analytical methods within Python. Some techniqes I used include slicing, DataFrame operations, filtering, grouping, sorting, and datetime operations.
  6. Create a basic visualization to showcase our answer to Question 4.

After cleaning and analyzing the data, here are the main takeaways and insights gained: 
  1. The dataset is highly focused on the city of Cary, though a wide variety of cities are represented. In this particular dataset, Cary appears to be an extremely popular Uber market. 
  2. The average MPH of an Uber ride depends heavily on the purpose of the rides. Commute rides have the highest average miles per hour, while airport/travel rides are typically the slowest. 
