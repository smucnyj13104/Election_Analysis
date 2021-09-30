# Election_Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Get a complete list of counties that received votes.
7. Calculate the total number of votes each county received.
8. Calculated the percentage of votes each county received.
9. Determine which county had the most votes.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9, Visual Studio Code, 1.60.2

## Election Audit Results 
The analysis of the election shows that:
- There were 369,711 total votes cast in the election.
- The breakdown of the county votes were:
    - Jefferson 10.5% (38,855 votes) 
    - Denver: 82.8% (306,055 votes)
    - Arapahoe: 6.7% (24,801 votes)
- Denver county had the largest number of votes.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 votes
    - Diana DeGette received 73.8% of the vote and 272,892 votes
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was:
    - Diana DeGette received 73.8% of the vote and 272,892 votes


## Election-Audit Summary
- This script can be used for any election as it flexible because it works over any number of counties, any number of candidates. It also does not matter what the county or candidate names are. If desired the script can be modified to work on a national level where additional data is tabulated re: states (in addition to counties). This modification would simply require additional code similar to the code used for county and candidate data. A limitation of this code is that it does not account for ties - if the leading candidates are tied then it will only report the first candidate in the data as the winner. The code could then be modified with an elif statement in the event of a tie, where it would output that the election was tied with the % of the vote and total votes for each "winner." 
