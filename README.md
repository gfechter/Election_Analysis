# Election_Analysis

## Project Overview
A Colorado Board of Elections gave the following tasks to complete an audit of a recent local congressional election. 

The tasks are as follows:
1. Calculate the total number of votes cast.
2. Get a list of all candidates who received votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate received. 
5. Determine the winner of the election based on the popular vote. 

Additional tasks were then requested by the Board of Elections. Those tasks are as follows: 
1. Calculate the voter turnout for each county. 
2. Calculate the percentage of votes from each county of the total count. 
3. Determine the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.66.2

## Election Results Summary
The analysis of the election results shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Dianna DeGette
  - Raymon Anthony Doane
- The counties where votes were cast:
  - Arapahoe
  - Denver
  - Jefferson
- The results for each candidate were:
  - Charles Casper Stockham received 23% of the vote with 85,213 votes.
  - Diana DeGette received 73.8% of the vote with 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote with 11,606 votes.
- The results for each county were:
  - 6.7% of the vote (24,801 votes) was cast in Arapahoe County. 
  - 82.8% of the vote (306,055 votes) was cast in Denver County. 
  - 10.5% of the vote (24,801 votes) was cast in Jefferson county. 
- The winner of this election was:
  - Diana DeGette with 73.8% of the vote with 272,892. 
- The county with the largest number of votes:
  - Denver County with 306,055 votes (82.8% of the vote). 

### Results in Terminal

<img width="977" alt="Screen Shot 2022-05-09 at 12 35 20 PM" src="https://user-images.githubusercontent.com/103774401/167485298-b0bbfee8-88cd-440b-a12f-49222fa63781.png">

### Results in Election Results Text File 

<img width="391" alt="Screen Shot 2022-05-09 at 12 37 08 PM" src="https://user-images.githubusercontent.com/103774401/167485352-8aaf97cc-9a84-4eab-ac76-439a499f0455.png">

## Election Audit Summary and Further Consideration
The script for this code can be used with some modifications for any election. This script is clear and easily modifiable which is demonstrated by the further analysis conducted for this project. Additionally, throughout the script, comments describe the code below. Therefore, this script could be modified to be used for other elections. 

One way this script could be modified is if the data included the party the candidate was running for, the script could be modified to show the results by political party. Another way this script could be modified is to show the number of votes each candidate received in each county if that data was available. Both of these are common in election results, and so modifying the script to include both of these would be very useful for an elections board. 

