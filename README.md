# Summer 2023 Data Science Intern Challenge
## Question 1: 
Given some sample data, write a program to answer the following.
On Shopify, we have exactly 100 sneaker shops, and each of these shops sells only one model of shoe. We want to do some analysis of the average order value (AOV). When we look at orders data over a 30 day window, we naively calculate an AOV of $3145.13. Given that we know these shops are selling sneakers, a relatively affordable item, something seems wrong with our analysis.
- a. Think about what could be going wrong with our calculation. Think about a better way to evaluate this data.
- b. What metric would you report for this dataset?
- c. What is its value?

## Question 2:
 For this question you’ll need to use SQL. Please use queries to answer the following questions. Paste your queries along with your final numerical answers below.
- a. How many orders were shipped by Speedy Express in total?
- b. What is the last name of the employee with the most orders?
- c. What product was ordered the most by customers in Germany?

# The Coaster dataset

- Download dataset here: https://buff.ly/3k6woDG 

- Read in the data:
url = 'https://raw.githubusercontent.com/kedeisha1/Challenges/main/coaster_db.csv'

- df = pd.read_csv(url) 

# This analysis reflected on the following:

1. How many columns and rows are in the dataset?
2. Is there any missing data?
3. Display the summary statistics of the numeric columns using the describe method.
4. Rename the following columns:
- coaster_name: Coaster_Name
- year_introduced : Year_Introduced
- opening_date_clean : Opening_Date
- speed_mph : Speed_mph
- height_ft : Height_ft
- Inversions_clean : Inversions
- Gforce_clean : Gforce

5. Are there any duplicated rows?
6. What are the top 3 years with the most roller coasters introduced?
7. What is the average speed? Also, display a plot to show its distribution.
8. Explore the feature relationships. Are there any positively or negatively correlated relationships?
9. fill the missing values of speed1_value with the mean
10. Check the data type of the DataFrame and convert the type to Datetime.
11. Plot a heatmap of missing values
12. visualize the speed1_value column using the density plot.



# Pandas Data Exploration
Pandas is one of the most powerful python libraries with the ability to read datasets in DataFrames, exploring and making them ready for modeling / machine learning and Scikit-learn for actually learning from these features created in Pandas.

# The chipotle dataset

- Link to dataset: https://raw.githubusercontent.com/justmarkham/DAT8/master/data/chipotle.tsv

- Read in .tsv file as .csv:

- url
 = 'https://raw.githubusercontent.com/justmarkham/DAT8/master/data/chipotle.tsv'
chipo = pd.read_csv(url, sep = '\t')

## Challenge
- Questions1. Which was the most-ordered item?
- Question2. For the most-ordered item, how many items were ordered?
- Question3. What was the most ordered item in the choice_description column?
- Question4. How many items were ordered in total?
- Question5. Turn the item price into a float
- Question6. How much was the revenue for the period in the dataset?
- Question7. How many orders were made in the period?
- Question8. What is the average revenue amount per order?
- Question9. How many different items are sold?
