# Indian Premier League Auction Analysis

## Objective:
Analyze the auction data from the Indian Premier League (IPL) to gain insights into player salaries, team strategies, and player distribution across various roles.

## Libraries Used:

pyspark: For data processing, data manipulation and analysis.

## Data Transformation and Cleaning:

## Loading Data:

Utilized PySpark to read the IPL auction dataset (cpl_2022_dataset.csv) with a predefined schema.

## Data Exploration:

Explored the total number of rows and columns using df.count() and len(df.columns).

## Data Cleaning:

Renamed columns for clarity using withColumnRenamed.
Checked and handled null values in all columns

## Data Preprocessing:

Filled null values in currency columns with 0.0 & NotPartOfAnyTeam in twentyOne_team column
Dropped the cost_inr column.

## Analysis:

Analyzed specifics using PySpark DataFrame operations and SQL queries.

## Insights and Results:

### Top 3 Highest Paid Batsmen:
Rohit Sharma, Virat Kohli, Kane Williamson.

### Top 5 Highest Paid Bowlers:
Rashid Khan, Deepak Chahar, Jasprit Bumrah, Shardul Thakur, Lockie Ferguson.

### 5 Lowest Paid Wicket-keepers:
Jitesh Sharma, Aryan Juyal, N. Jagadeesan, Luvnith Sisodia, Baba Indrajith.

### Average Pay by Player Type:
Wicketkeeper: $278.99, Batter: $214.56, All-Rounder: $170.48, Bowler: $142.91.

### List of Retained Players with Team and Salary:
Players like Ravindra Jadeja, Rishabh Pant, Rohit Sharma, Virat Kohli, and others.

The analysis provides a comprehensive overview of player salaries, team-wise distribution, and average pay based on player roles in the IPL auction.
