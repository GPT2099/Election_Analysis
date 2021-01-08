# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local 
congressional election.

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who recieved votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.1, Visual Studio Code, 1.52.1

## Summary
The Analysis of the election show that:

- There were 369,711 votes cast in the election. 
- Jefferson County received 10.5% of the vote and 38,855 number of votes.
- Denver County received 82.8% of the vote and 306,055 number of votes.
- Arapahoe County received 6.7% of the vote and 24,801 number of votes.
- Denver County recieved the greatest turnout with 82.8% of the vote and 306,055 number of votes. 
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were: 
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes. 
  - Diana DeGette received 73.8% of the votes and 272,892 number of votes. 
  - Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes. 
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes. 
  
[View All Results Here](./analysis/election_analysis.txt)
  
## Challenge Overview 
The election commission has requested additional data to complete the audit. 

1. Calculate the voter turnout for each county. 
2. Calculate the percentage of votes from each county out of the total count. 
3. Determine the county with the highest turnout. 


## Challenge Summary 
This script can be used for future elections to determine any number of votes, counties, percentages, and candidates as long as adherence to the format of [election_results.csv](./Resources/election_results.csv) is followed. This script can be modified for future election result csv files containing no header by removing line 43. This script can further be modified for csv result files with candidates and counties being listed differently by simply changing each location within the list starting at 0 on lines 52 and 55. 


- 

