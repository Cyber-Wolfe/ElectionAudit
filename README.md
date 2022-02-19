# Election Audit

## Project Overview
Seth and Tom had enlisted me to audit data from the upcoming election and evaluate the findings. The results that were wanted were: 
1. Voter turnout from each county,
2. Percentage of votes each county contributed to the total voting poo
3. County with the highest voter turnout.

### Rescources
- Data: election_results.csv
- Software: Python 3.9.1
	    Visual Studio Code 1.63.2
- Analysis: election_analysis.txt

## Election Results
With the election data compiled and broken down we had gathered 
369,711 votes were cast in this election.

The votes were broken down from these 3 counties:
-Jefferson area having 38,855 votes (10.5% of the voting pool). 
-Denver area having 306,055 votes (82.8% of the voting pool).
-Arapahoe area haveing 24,801 votes (6.7% of the voting pool).

*Votes and Percentages by Candidate*
-Charles Casper Stockham had recieved 85,213(23.0% of the voting pool).
-Diana DeGette had recieved 272,892 votes (73.8% of the voting pool).
-Raymon Anthony Doane had recieved 11,606 votes (3.1% of the voting pool).

This gives Diana DeGette with 272,892 (73.8% of the voting pool) votes a landslide of a victory in the election.

## Election Summary
The election commision can easily reformat this script to be used with any future election they see fit. What has to be done is is just to alter all the blue text in this order:

1. Add new variables to the variables section.

![Variables_pull.PNG](https://github.com/Cyber-Wolfe/ElectionAudit/blob/main/Script_Screenshots/Variables_pull.PNG)

2. Add a list line in the for-loop.

![Row_reader](https://github.com/Cyber-Wolfe/ElectionAudit/blob/main/Script_Screenshots/Row_reader.PNG)

3. Then a new for and if-statement.

![for_block](https://github.com/Cyber-Wolfe/ElectionAudit/blob/main/Script_Screenshots/for_block.PNG)

Then it is ready to run with a print statement 'txt_file.write(your_variable_here)' =COUNTIF().

A good example would be if the election commission wanted to add demographic or ages into the election data to see a breakdown of who and how old the voters are. Add in a new set of variables into the variable list, a new list in the for-loop, and the a new if and for statement and then we can print.  That knowledge could help candidates with campaigning for diversely in the future.
A second example could be just to increase the overall amount of candidates. The code does not even need to be altered for an increase in candidates and areas.  The code is already to have more people in it, all it needs is to read out the CSV file with more poeple and the data is ready.
