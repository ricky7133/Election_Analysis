# Election_Analysis

## Project Overview
A Colorado Board ofElections employee has givenyou the following tasks to complete the election audit ofa recentlocal congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election
- The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymond Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the votes and 272,892 number of votes.
  - Raymond Anthony Doane received 3.1% of the votes and 11,606 number of votes.
- The winner of the election was: 
  - Diana DeGette, who received 73.8% of the votes and 272,892 number of votes.
- The counties involved were:
   - Jefferson
   - Denver
   - Arapahoe
- The results for the amount of votes in each county were:
   - Jefferson casted 10.5% of the total votes making 38,855
   - Denver casted 82.2% of the total votes making 306,055
   - Arapahoe casted 6.7% of the total votes making 24,801
- The county with the largest voter turnout was:
   - Denver who made up 82.8% of the total votes (306,055)

## Challenge Overview
The purpose of this election audit was to see who won the election and the amount of votes each candidate got. We also wanted to know which counties were involved, how many voters each county had and which county had the largest voter turnout. 
## Challenge Summary
Based off of how well we were able to calculate things such as total votes, elction winner, total votes cast in each county, we can safely assume that this script can be used for other elections. We can also add more to the script. For example, adding another if statement that tells us how many voters in each county voted for each candidate. We could also add a statement that looks for repeat ballot id's so we dont include those in the results.
