# Election_Analysis

## Project Overview of Election Audit:
The Colorado Board of Elections requested help to complete an election audit for a recent local congressional election. The audit also included finding the answer to the following:

* Total number of votes cast
* A complete list of candidates who received votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote
* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout
------------------------------------------------------------

## Resources
Data Sources: election_results.csv
Software: Python 3.8.9, Visual Studio Code 1.67.2

------------------------------------------------------------

## Election-Audit Results:

* How many votes were cast in this congressional election?
    - Total Votes: 369,711
------------------------------------------------------------

* A complete list of candidates who received votes;
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
------------------------------------------------------------

* Which county had the largest number of votes?
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    - Largest County Turnout: Denver
    - County Votes:
        - Jefferson: 10.5%: (38855)
        - Denver: 82.8%: (306055)
        - Arapahoe: 6.7%: (24801)
------------------------------------------------------------

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
	- Winner: Diana DeGette
    - Winning Vote Count: 272,892
    - Winning Percentage: 73.8%
------------------------------------------------------------

Below is a screenshot of the election analysis txt file.
![Image of Election Analysis txt file](/Resources/election_analysis_txt.png)

------------------------------------------------------------

## Election-Audit Summary:
Because the Python code does not have values for the candidate names or counties hard-coded, the script could be applied too other State elections by changing the following:
* The “file_to_load” variable can easily be given a new path to a different csv file from another state’s election data.
* The “file_to_save” variable can also be assigned to a new txt file to record the results.