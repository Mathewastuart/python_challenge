# python_challenge

Py_bank
----------------

py_bank provides a financial analysis of the budget_data.csv

The results provide a total amount of months, the total profits, the Average change in profits, and Greatest increase and decrease in profits.

These results are printed to the terminal and a .txt file

 Py_bank analysis results
 -----------------------------
 
 Total months surveyed was found to be 86. This was found by using a .count() on the months column
 
 Total profits summed the repective column givng the result $22564198
 
 Average Change was found by creating a new column of the change bewteen one row and the previous, then averaging these values
 The average change was Average Change: $-8311.11
 
 Greatest Increase In Profits: Aug-16 $1862002, was found by locting the max in the new 'Change' column

Greatest Decrease In Profits: Feb-14 $-1825558, was found by locating the min in the new 'Change' column

Final Comments
------------------------

Formatting was applied where necesarry to provide a reasonable amount of decimal points
the file was read in simply by providing the .csv name since the file pathing was all in the same folder
The month for greatest increase/decrease was foudn by locating the index of the value.


Py_Poll
-------------------

py_poll provides election results/analysis based off the file election_data.csv

The results provide the total votes, Each candidate, their personal votes totaled, and the percentage of votes won.

results are printed to terminal and a .txt file

Py_Poll analysis results
-----------------------------

Total votes were found by summing the respective column. Total being: 369711

Three candidates were found to be invlved in the election 

1. Charles Casper Stockham: %23.05 (85213)
2. Diana DeGette: %73.81 (272892)
3. Raymon Anthony Doane: %3.14 (11606)

the votes for each candidate were found by sorting through the corresponding column and finding the totals associated with that candidate

percentage was then calcualted by doing the candidate's votes divided by the total votes

the votes for each candidate were then assigned to a new dataframe alongside the respective candidate names

Using this new dataframe the candidate winner was determined by finding the max votes.

The winner was Diana Degette

Final Comments
--------------------
adding the indivdual vote totals to a new dataframe was done to stay organized on my end
the logic behind this should be able to be followed through my commented subscript
