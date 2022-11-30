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
