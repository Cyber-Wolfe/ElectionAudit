# Election Audit

## Project Overview
Seth and Tom had enlisted me to audit data from the upcoming election and evaluate the findings. The results that were wanted were: 
1. Voter turnout from each county,
2. Percentage of votes each county contributed to the total voting poo
3. County with the highest voter turnout.

### Rescources
- *Data*: election_results.csv
- *Software*: Python 3.9.1
	    Visual Studio Code 1.63.2
- *Analysis*: election_analysis.txt

## Election Results

### *Area Votes Breakdown*

369,711 votes were cast in this election.

The votes were broken down from these 3 counties:

* Jefferson area having 38,855 votes (10.5% of the voting pool).

* Denver area having 306,055 votes (82.8% of the voting pool).-

* Arapahoe area haveing 24,801 votes (6.7% of the voting pool).-

### *Votes and Percentages by Candidate*

* Charles Casper Stockham had recieved 85,213(23.0% of the voting pool).

* Diana DeGette had recieved 272,892 votes (73.8% of the voting pool).

* Raymon Anthony Doane had recieved 11,606 votes (3.1% of the voting pool).

This gives Diana DeGette with 272,892 (73.8% of the voting pool) votes a landslide of a victory in the election.

## Election Summary
The election commision can easily reformat this script to be used with any future election they see fit. What has to be done is is just to alter all the blue text in this order:

1. Add new variables to the variables section.

![Variables_pull.PNG](https://github.com/Cyber-Wolfe/ElectionAudit/blob/main/Script_Screenshots/Variables_pull.PNG)

2. Add a list line in the for-loop.

![Row_reader](https://github.com/Cyber-Wolfe/ElectionAudit/blob/main/Script_Screenshots/Row_reader.PNG)

3. Then a new for and if-statement.

![for_block](https://github.com/Cyber-Wolfe/ElectionAudit/blob/main/Script_Screenshots/for_block.PNG)

Then it is ready to run with a print statement `txt_file.write(your_variable_here)`. This can be done for any new variable set we want! For instance...

A great addition to this code to would be for the election commission to gather data on demographic or ages and add that into the election CSV. The breakdown of that new data  of who had voted and how old the voters were could add a great deal of how the people had cast their votes. That knowledge could help candidates with campaigning for diversely in the future and try to reach audiences they have not focused on as much in prior campaigns. When candidates run for election they try to hit as many demographics as they can with varying degrees of success. With the data from the votes, they can more accurate pinpoint their weaknesses in demographic and maybe even abandon trying to reach for certain demographics if they seem not too respondant to their campaigns. To add in the age or demographic, the steps above can be followed and the new data can be analyzed.

Another edition could be to add in voting times which could potentially be very valuable.  A possibility to see how campaigning throught out the areas directly affects voters.  Maybe a big campaign dinner had played a part in a surge of votes the following week for a candidate or a scandal with another cause their opposing person to also gain more votes instead of their scandalous self. 
