## Unit 4 | Python (Pandas)
<<<<<<< HEAD
=======

Skills Tested: Python (Pandas, Matplotlib, Arrays, Loops), Visualizing and Analyzing Data

--Synopsis--
This is the readme file for the Pymoli homework.  Pymoli is a free game where players can purchase items throughout the game.  The files we are reading are json files, where panda can read into dataframes and dataseries.
we then manipulate the data into tables and break down the data about the players and their purchase habits.  We analyze age and gender demographics, as well as popular and profitable items within the game.

--Motivation--
My motivation for this project is that it is homework, and that I want to learn python and pandas?  And to make tables so that analyzing data is easy.

--Testing--
Program was tested with both json data files.

--Contributors--
Me, myself, and I (Albert Doan)...with help from Charlie and Julien.

--License--
<b>Part of UCB extension analytics bootcamp, in conjunction with Trilogy education services.  Copyright.</b>
>>>>>>> 0b86f3725191ad131d79a91dc54a96eb2fb1347a

Skills Tested: Python (Pandas, Arrays, Loops), Data Analysis

Pymoli is a free game where players can purchase items throughout the game.  The files we are reading are json files, where panda can read into dataframes and dataseries.  We then manipulate the data into tables and break down the data about the players and their purchase habits.  We analyze age and gender demographics, as well as popular and profitable items within the game.  There are two JSON files, with the purpose of writing Python code that can be universally applied to both files, without having to change any variables or directly access the data.

Analysis of virtual data:

Analysis #1: Looking at the top 5 popular items and the top 5 profitable items, I would be interested in increasing the price for the popular items. Assuming that the items are similar in nature, you have profitable ones selling at nearly twice the price as the popular items. As for the purchase counts, you will also see that although there is a decrease of approximately 30% in purchase count, the purchase price is nearly doubled. Which, in effect, would be profitable if you double the price of the popular items.

Analysis #2: Looking at the normalized purchases, you notice that the average price spent per age demographic increases with age. This is expected since older individuals have more stable income. The takeaway from this data, is that older individuals are price/demand inelastic, meaning that they are not sensitive to increase in prices. Hence an increase in certain items that are popular in that age group would yield more profits. Basically when prices increase for that age group, then revenue should increase as well. According to the function e=|(dQ/Q)/(dP/P)|, a value closer to 0 is good, where the increase in price results in a small (or smaller) decrease in quantity purchased.

Analysis #3: Looking at the gender demographics, it is obvious that the male players are spending more on items (according to the normalized average purchases). I would ignore the Non-disclosed gender, based on the fact that it is too small of a sample size, most likely with a large margin of error. Hence, from a marketing perspective, if one had a fixed marketing budget, the target audience would be males. Due to the evidence, males spend more on items, and hence offer a better return on investment (per dollar invested in marketing campaign).
