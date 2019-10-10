# pandas-challenge

"Heroes of Pymoli" is a fantasy game. Task is to generate a report that breaks down the games purchasing data into meaningful insights using Python Pandas.

Player Count:
  Display the total number of players
  
Purchasing Analysis (Total):
  Run basic calculations to obtain number of unique items, average price, etc.
  Created a summary data frame to hold the results
  Displayed data with cleaner formatting
  Displayed the summary data frame.
  
Gender Demographics:
  Percentage and Count of Male Players
  Percentage and Count of Female Players
  Percentage and Count of Other / Non-Disclosed
  
Purchasing Analysis (Gender):
  Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc. by gender
  Created a summary data frame to hold the results
  Displayed data in a cleaner format
  Displayed the summary data frame
  
Age Demographics:
  Established bins for ages
  Categorized the existing players using the age bins using pd.cut()
  Calculated the numbers and percentages by age group
  Created a summary data frame to hold the results
  Rounded the percentage column to two decimal points
  Displayed Age Demographics in table format
  
Purchasing Analysis (Age):
  Bined the purchase_data data frame by age
  Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc. in the table below
  Create a summary data frame to hold the results
  Displayed data in cleaner format
  Displayed the summary data frame
  
Top Spenders:
  Run basic calculations to obtain the results in the table below
  Created a summary data frame to hold the results
  Sorted the total purchase value column in descending order
  Displayed data in a cleaner format
  Displayed a preview of the summary data frame
  
Most Popular Items:
  Retrieve the Item ID, Item Name, and Item Price columns
  Grouped by Item ID and Item Name. Performed calculations to obtain purchase count, item price, and total purchase value
  Created a summary data frame to hold the results
  Sorted the purchase count column in descending order
  Displayed data in cleaner format
  Displayed a preview of the summary data frame
  
Most Profitable Items:
  Sorted the above table by total purchase value in descending order
  Displayed data in cleaner format
  Displayed a preview of the data frame
  
Conclusions:
1) "Extraction, Quickblade Of Trembling Hands" though being a most popular game is not a highly profitable item.

2) We see a increase in the players by age group. As age increases and reaches 20-24 age group the players are increasing but from there on they decrease and become significantly less t 40+.

3) There are less number of female players than male players.

4) Though the others are fewer their average spending is more than male and females. Average spending of females is also much better when compared to males, who though more in number are spending less.

5) The highest average total per person is in the age group 35-39 which does not have so many players as the age group 20-24. So a lot of new items can be introduced to attract the 35-39 age group, who spend more.
