# Election-Analysis

## Project and Challenge Overview
  For this analysis Tom (a member of the Colorado Board of Elections) and I retirieved data from an election audit for the United States Congressional precinct in Colorado. The first objective of this Module was:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

  After retrieving the necessary data, I was then tasked with using a set of starter code to find out more information about the congressional election. The election commission requested additional information is as follows:
1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout 


## Results
According to the extra data I was tasked in retireving, the results are as follows:
There were 369,711 total votes cast across the three counties. 
### County votes
  -Jefferson county received 10.5% of the votes with 38,855 number of votes.
  -Denver county received  82.8% of the votes with 306,055 number of votes.
  -Arapahoe county received 6.7% of the votes with 24,801 number of votes. 
  -The county with the largest amount of votes was the city of Denver with 82.8% of votes with 306,055 number of votes.

### Candidates 
  - Charles Casper Stockham 
  - Diana DeGette
  - Raymon Anthony Doane
The results are as follows:
  - Chalres Casper Stockham received 23% of the votes with 85,213 number of votes.
  - Diana DeGette received 73.8% of the votes with 272,892 number of votes 
  - Raymon Anthony Doane received 3.1% of the votes with 11,606 number of votes
The winner of the election was:
  - Diana DeGette with the winning vote count of 272,892 votes  with a 73.8% of the vote.

![Election_Results](./Election_Results.pdf)
  

## Challenge Summary 
  Using the Challenge code, I believe it is also completely possible to use this format to retrieev data fir any election. With the proper modifications, we can use Python and more specifically this code, to gather data that can be used in any election from the local level to even a presedential election. One way this can be used in something like the presidentail election is to first retireve a new CSV file that can contain the election data for a presidental election. With the new CSV file we can upload it and change the varaible around as well as rename the multiple variables containing county information to "state" variable such as "state_votes" or "largest_state_turnout".


## Resources 
-Data Source: election_results.csv
-Software: Python 3.7.6, Visual Studio Code, 1.66.2
