# WeRateDogs Data Wrangling Project

## Authors

- [David Abiose](https://www.github.com/Abiose)


## Introduction
in this project, the tweet archive of Twitter user @dog_rates, also known as WeRateDogs is 
being wrangled. WeRateDogs is a Twitter account that rates people’s dogs with a humorous
comment about the dog. The ratings almost have a denominator of 10. The numerators caries 
values that are almost greater than 10 (11/10, 12/10, 13/10) etc. This is because “They’re good dogs Brent.”

## Documentation
> Wrangling Process
- Data Gathering
The datasets used for this project was gathered from three (3) different sources which involves 
1. A CSV file at hand
This CSV file (“twitter-archive-enhanced.csv”) was read into the DataFrame using the
Pandas function.
2. A TSV file downloaded programmatically
This file (“image-predictions.tsv”) was downloaded from the internet programmatically
using the “Requests” library as it is best for scalability and reproducibility. Afterwards,
the file was read into a DataFrame using the Pandas function.
3. Querying the Twitter API
This process involves specifying the required tweet IDs for the project and querying 
Twitter’s APIs for each tweet IDs JSON data.

- Data Assessing
This wrangling process involves two (2) steps.

• Visual Assessments
Each file was visually assessed and it means systematically looking through each table of 
data in the Jupyter Notebook using Pandas and scrolling through the data, looking for 
interesting and relevant issues such as (completeness, validity, accuracy and 
consistency)

• Programmatic Assessments
All files went through this process and it involves using functions and methods to reveal 
information on issues about each dataset’s quality and tidiness.

Some of the issues identified in the data assessing process of each datasets include the 
following:

**Quality**
1. Unusual characters in the name column.
2. Erroneous datatypes.
3. Non-descriptive column names.
4. Columns with non-useful information.
5. Problems of outliers and inaccurate values.

**Tidiness**
1. A new variable to form a column.
2. Merging the 3 datasets to for form a table.


- Data Cleaning
This process involves cleaning the issues that was revealed during the assessment of the 
datasets. It follows three (3) steps

• Define the issue.

• Writing the cleaning code.

• Test the code for successful execution.



## Summary Of Findings
- It is clear from our study and our graphic that Floofer is the dog stage with tweets that has the highest average ratings, with a roughly 12.67 rating per tweet.
- The Bedlington Terrier was the dog breed that received the most average tweet likes out of these five breeds.
- The aggregate tweets' likes and retweets are strongly positively correlated.


## Conclusion
The lengthy but successful data wrangling procedure helped to clean up our unclean and disorganized data. This gives us the chance to continue with our data analysis and visualization in order to effectively present our findings.
