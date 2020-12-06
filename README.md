# election-analysis
Using Python to determine election results

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. The voter turnout in each county.
3. The percentage of votes from each county of the total count.
4. The county with the highest turnout.
5. Get a complete list of candidates who recieved votes.
6. Calculate the total number of votes each candidate recieved.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

# Election-Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election.

Breakdown of votes by County:
- Jefferson County had 10.5% of the votes (38,855)
- Denver County had 82.8% of the votes (306,055)
- Arapahoe County had 6.7% of the votes (24,801)

Therefore, Denver had the largest voter turnout.

The candidates were: 
- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

The candidate results were:
- Charles Casper Stockham recieved 23.0% of the vote and 85,213 votes.
- Diana DeGette recieved 73.8% of the vote and 272,892 votes.
- Raymon Anthony Doane recieved 3.1% of the vote and 11,606 votes.

The winner of the election was:
- Diana DeGette, who recieved 73.8% of the vote and 272,892 votes.

## Election-Audit Summary
Members of the Election Commision,

I believe this code can be altered to serve as an efficient method of determining other election results. 
In an election, it is important there is as little room for human error as possible. We must be able to understand data like which candidates ran, how many votes they recieved, who won, and voter turnout. Automating the process means we can understand answers to these questions more quickly and accurately. 
Using this Python script, we can find the answers to these questions beyond the US Congressional preccinct in Colorado. We can use it to determine the outcome of senatorial districts and local elections throughout the country. The only modifications required would be to change the file_to_load, and the indexing of columns we want to count if candidate_name and county_name are not in the order they are here. 
So long as other data is collected, there are endless opportunities for data exploration. If we created a "Race" column in the csv, we could quickly understand the racial breakdown of voters for each candidate. If there were a column where socioeconomic status was reported, we could look into voting trends among different class brackets. I strongly encourage you to consider allowing us to automate this process in order to ensure a quick, accurate, and detailed understanding of voting trends and election results.
