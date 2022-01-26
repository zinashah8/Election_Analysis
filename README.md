# Election Analysis
Overview:

A Colorado Board of Elections employee has given us the following tasks to complete the election audit of a recent local congressional election.

* Calculate the total number of votes cast.
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
* Determine which county had the largest number of votes.
* Get a complete list of candidates who received votes.
* Calculate the total number of votes each candidate received.
* Calculate the percentage of votes each candidate won.
* Determine the winner of the election based on popular vote.

## Data Sources:
- election_results.csv

## Technology Used:
- Python, Visual Studio Code

## Election Analysis Results:
There were 369,711 votes cast in the election.

The breakdown of the number of votes and the percentage of total votes per county was:
* Jefferson had 10.5% of the votes and 38,855 ballots cast.
* Denver had 82.8% of the votes and 306,055 ballots cast.
* Arapahoe had 6.7% of the votes and 24,801 ballots cast.

The county with the largest turnout was Denver with 82.8% of the votes and 306,055 number of votes.

The candidates were:
* Charles Casper Stockham
* Diana DeGette
* Raymon Anthony Doane

The candidate results were:
* Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
* Diane DeGette received 73.8% of the vote and 272,892 number of votes.
* Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

The winner of the election was:
* Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Election Audit Summary: 

![Image](/Resources/election_outcomes.png)

1. PyPoll_Challenge.py could be modified to conduct an audit analysis for any election organized by the election commission.
Here are the requirements:

Ensure the election results *.csv file has the following structure:
Ballot ID | County | Candidate 

2. Modify PyPoll_Challenge.py script by assigning user input variables for the folder and name of the results *.csv file and analysis *.txt file which will respectively be read and saved.
