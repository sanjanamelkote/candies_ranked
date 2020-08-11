Candies Ranked: Which sweet treat reigns supreme?
=
Various candies and chocolates sorted by type, price, sugar level, and popularity 
-
### By Sanjana Melkote 

I recently decided to start eating healthier and avoid all processed foods and added sugars. Of course, right after I made that decision, I found a mouthwatering data set covering almost 100 different chocolates and candies. While this data set, titled **[Candy Power Rankings](https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking)** was really interesting and revealed a lot of useful information, I can't say completing this project made my already difficult diet any easier to stick to. However, as someone who is definitely too old to be trick-or-treating and instead should be preparing to hand out candies for the foreseeable future, this data set revealed many sweet secrets to a successful Halloween. 

I got the data from **[FiveThirtyEight Github Repository](https://github.com/fivethirtyeight/data)**. Thankfully, the data was already in a **[CSV file](https://raw.githubusercontent.com/fivethirtyeight/data/master/candy-power-ranking/candy-data.csv)** format and it was surprisingly pretty clean and succinct. The only quick clean up I had to do was standardizing the percentage formats between the three numerical columns. The columns that had price and sugar level percentiles were in decimal format with 1 being the highest number but the popularity percentage column had whole numbers with 100 being the highest percentage. To standardize the percentages to being in decimal format I used a quick formula to divide all the popularity percentages by 100. Then I changed the format of the three columns so that they were numbers. I also used Google Sheets "Find" and "Replace" to standardize the names of the candy brands. There were some unneccesary special characters in the names like "Reese's" and "Hershey's" so I used "Find" and "Replace" to remove the special characters and format the names.

Once the data set was cleaned, I sorted the data in multiple ways: by popularity, price, sugar level, type, and ingredient. I also did some further research to find which candies avoided the top 8 most common allergens and which candies were vegetarian and vegan friendly and made separate tables with those restrictions in mind. With all this data at my fingertips, I started curating the ultimate Halloween Candy Hand Out Guide!

![candies ranked, most and least](https://media.journalism.berkeley.edu/upload/2020/08/1597129324549fffe.png)

Each candy was categorized by type of candy (chocolate or fruity), key add on ingredients(caramel, nuts, nougat, or crisped rice wafer), whether the candy was a hard candy, bar, or came in a pack of multiple pieces. The candies were then rated based on price, sugar level, and popularity. Here are the candies with the highest popularity, lowest prices, and lowest sugar level.

![candy popularity](https://media.journalism.berkeley.edu/upload/2020/08/1597187754bc83131.png)
![candy price](https://media.journalism.berkeley.edu/upload/2020/08/15971882910fd939c.png)
![sugar level](https://media.journalism.berkeley.edu/upload/2020/08/15971884878391f3b.png)

I ranked each candy by its popularity percentile, from most to least popular. This visualization revealed that every variation of a Reese's Peanut Butter candy was in the top 10 most popular candies.

1. Reese's Peanut Butter Cup
2. Reese's Miniatures
3. Reese's Pieces
4. Reese's Stuffed With Pieces

What's more is that in the top 10 candies, 6 of the candies were nut based candies. As good as the chocolate and nut combination is, I expected nutty chocolates to rank low in popularities due to nut allergies being common among children. This visualization also revealed that all of the top 10 ranked candies are chocolate based, which isn't surprising because chocolate reigns supreme in *any* situation. 

![pie chart](https://media.journalism.berkeley.edu/upload/2020/08/1597176374ecb9ed5.png)

Out of the 85 top ranked candies, 37 were chocolate based, 36 were fruity, 11 were neither chocolate nor fruit based, and 1 was both chocolatey and fruity — tootsie rolls!

![price and popularity](https://media.journalism.berkeley.edu/upload/2020/08/1597128867b2a4275.png)

If people are looking out to give candy to many children, they won't be reaching for gourmet Lindt chocolates. This made me ask the question: is there a correlation between price and popularity? Are certain candies more popular because they are cheaper? Turns out, there doesn't seem to be much of a correlation between price and popularity. I guess flavor is truly the dictator of popularity, sweet-tooths couldn't be less concerned about the financial investment. Here is an interactive version of the [price and popularity chart](https://datawrapper.dwcdn.net/SpOE2/1/), where you can hover over dots to see which candy they are!

![sugar level and popularity](https://media.journalism.berkeley.edu/upload/2020/08/1597131083801a346.png)

After realizing that flavor is a bigger factor in candy popularity, I looked to see if there was a correlation between sugar level in candy and its popularity. However, this chart also had little correlation between the two variables. A higher sugar level doesn't necessarily mean better tasting! Some good news: some of the most popular candies (i.e. Reese's miniatures) are lower in sugar! That means its healthy, *right*?  Here is an interactive version of the [sugar level and popularity chart](https://datawrapper.dwcdn.net/mKacm/1/).

![allergies](https://media.journalism.berkeley.edu/upload/2020/08/159717820995d4bec.png)

The fact that nut based candies are still the most popular despite the common nut allergy had me researching further into sweet treats that can cause allergies. I'm not sure this is something people think about when handing out Halloween candies, but it's better to be safe than risk sending a child to the emergency room on what's supposed to be a fun night of trick or treating. According to an [article](https://www.spokin.com/candy-guide/list-of-food-allergy-friendly-halloween-candy) on Spokin, a website that details brands that abide by FDA policies, many fruity candies are free of the top eight most common allergens. 

![vegetarian](https://media.journalism.berkeley.edu/upload/2020/08/159718618983266e6.png)
![vegan](https://media.journalism.berkeley.edu/upload/2020/08/1597186493c6d31c9.png)

While thankfully, I don't have any allergies, I am vegetarian and I was curious to see what types of candies are vegetarian and vegan! Hey, lets not leave anyone out when it comes to Halloween sugar highs, right? Unlike the Spokin article, an [article](https://www.connectionsacademy.com/the-monitor/candies-vegetarians-vegans-can-eat) on Connections Academy lists many chocolates that are suitable for vegetarians because the fruitier candies tend to have ingredients like gelatin. Vegan candies are also available on the article! The article suggests to avoid gummies, starburst, candy corn, marshmallows, and junior mints if you are vegetarian or vegan. Quick PSA: Jolly Ranchers(one of my favorite candies) was on the vegan list but not in the data set I am using for the popularity percentiles! 

So, does deciding which Halloween candy to pass out require an entire data analysis project accompanied by multiple data visualizations? *Probably* not. However, if I can't eat sugar, I might as well spend my time thinking about it. Yum!

![halloween success guide](https://media.journalism.berkeley.edu/upload/2020/08/159718927497e8915.png)

***
