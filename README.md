# IPL-DATA-ANALYSIS-
EDA-IPL-DATA-ANALYSIS USING PYTHON ON DATASET 2008-2020

# IPL-DATA-ANALYSIS-
Exploratory Data Analysis on IPL data (2008 - 2020). Finding insights and patterns in data.

[IPL DATA ANALYSIS USING PYTHON.pdf](https://github.com/user-attachments/files/22234392/IPL.DATA.ANALYSIS.USING.PYTHON.pdf)

Exploratory Data Analysis (EDA) is an approach to analyze the data using visual techniques. It is used to discover trends, patterns, or to check assumptions with the help of statistical summary and graphical representations

The primary objective of any EDA process is to analyse the underlying structure of a dataset which can help in insight generation.

Components of EDA
There are main components of exploring data:

    Understanding your variables
    Cleaning your dataset
    Analyzing relationships between variables

Steps Involved in Exploratory Data Analysis[EDA]

    Data Collection
    Data Cleaning
    Univariate Analysis
    Bivariate Analysis

Repository Overview
This repository is about EDA performed on Indian Premier League Data available between 2008 - 2018.

It has a python notebook where all the coding has been done
It also has the relevant datasets used for this analysis
Brief Overview of the steps followed in this project

There are 2 datasets used for the analysis. ' IPL Deliveries 2008-2020.csv' dataset gives information on all the matches played in IPL between 2008 and 2020 i.e. information on the following:

    Season
    Venue
    City
    Teams
    Winner
    Toss Winner
    Winning margin
    Umpires

On the other hand 'IPL Ball-by-Ball 2008-2020.csv' dataset gives ball by ball information on every match played during 2008 - 2020.
i.e. information on the following:

    Runs scored per ball
    Extras by bowlers/fielding team
    Wickets taken
    Types of dismissals
    Venue It basically provides individual records of players.

The entire EDA process was broken down into 2 high level topics to find answers to the problem statement

    Univariate Analysis (analysing individual attributes)
    Bivariate Analysis (analysing 2 attributes together)

HYPOTHESIS TESTING 

Use Statistical models to examine if there is correlation between
1) Toss Decision and Win/Lose a match
2) Ground (Home/Away) and Win/Loss a match
   
Statistical models used:
➢ Chi-Square Test
Null Hypothesis (Ho):

1) There is no relationship between Toss Decision and Win/Lose a match
2) There is no relationship between Ground (Home/Away) and Win/Lose a match

Chi-Square Test (χ² Test)
A statistical test used to determine if there is a significant association between two categorical 
variables.
Key Points:
Used in contingency tables (cross-tabulations).
Compares observed vs expected frequencies.
Does not give direction or strength, just association.
Formula:
\chi^2 = \sum \frac{(O - E)^2}{E}
O = Observed frequency
E = Expected frequency
Types:
Goodness of Fit Test – Checks if sample matches a population.
Test of Independence – Checks relationship between two variables.

Significance Value:
Degrees of Freedom (df) = (rows−1) × (columns−1)
If p-value < 0.05, reject the null hypothesis (variables are associated).
Significant Chi-square values are based on a Chi-square distribution table.
Test Used For Key Statistic Significant If
Chi-Square Categorical variables χ² p-value < 0.05
Correlation Numeric variables r p-value < 0.05
General Test Any hypothesis testing p-value p-value < 0.05

However, before analysing, Profiling and processing of data was undertaken. After finding patterns and relationships in the data, EDA process was concluded with few conclusions as derived while analysing. Along with concluding insights, few actionable items were also suggested which could help in better performance of players or auctioning of players, etc.
