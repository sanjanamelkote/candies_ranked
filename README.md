Candies Ranked: Which sweet treat reigns supreme?
=
Various candies and chocolates sorted by type, price, sugar level, and popularity 
-
### By Sanjana Melkote 

I recently decided to start eating healthier and avoid all processed foods and added sugars. Of course, right after I made that decision, I found a mouthwatering data set covering almost 100 different chocolates and candies. While this data set, titled **[Candy Power Rankings](https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking)** was really interesting and revealed a lot of useful information, I can't say completing this project made my already difficult diet any easier to stick to. However, as someone who is definitely too old to be trick-or-treating and instead should be preparing to hand out candies for the foreseeable future, this data set revealed many sweet secrets to a successful Halloween. 

I got the data from **[FiveThirtyEight Github Repository](https://github.com/fivethirtyeight/data)**. Thankfully, the data was already in a **[CSV file](https://raw.githubusercontent.com/fivethirtyeight/data/master/candy-power-ranking/candy-data.csv)** format and it was surprisingly pretty clean and succinct. The only quick clean up I had to do was standardizing the percentage formats between the three numerical columns. The columns that had price and sugar level percentiles were in decimal format with 1 being the highest number but the popularity percentage column had whole numbers with 100 being the highest percentage. To standardize the percentages to being in decimal format I used a quick formula to divide all the popularity percentages by 100. Then I changed the format of the three columns so that they were numbers. I also used Open Refine to standardize the names of the candy brands. There were some unneccesary special characters in the names like "Reese's" and "Hershey's" so I used Open Refine to remove the special characters. 

Each candy was categorized by type of candy (chocolate or fruity), key add on ingredients(caramel, nuts, nougat, or crisped rice wafer), whether the candy was a hard candy, bar, or came in a pack of multiple pieces. The candies were then rated based on price, sugar level, and popularity. Here are the candies with the highest and lowest prices, sugar level, and popularity.

![candies ranked, most and least](https://media.journalism.berkeley.edu/upload/2020/08/1597129324549fffe.png)

If people are looking out to give candy to many children, they won't be reaching for gourmet Lindt chocolates. This made me ask the question: is there a correlation between price and popularity? Are certain candies more popular because they are cheaper? Turns out, there doesn't seem to be much of a correlation between price and popularity. I guess flavor is truly the dictator of popularity, sweet-tooths couldn't be less concerned about the financial investment. Here is an interactive version of the [price and popularity chart](https://datawrapper.dwcdn.net/SpOE2/1/), where you can hover over dots to see which candy they are!

![price and popularity](https://media.journalism.berkeley.edu/upload/2020/08/1597128867b2a4275.png)

After realizing that flavor is a bigger factor in candy popularity, I looked to see if there was a correlation between sugar level in candy and its popularity. However, this chart also had little correlation between the two variables. A higher sugar level doesn't necessarily mean better tasting! Some good news: some of the most popular candies (i.e. Reese's miniatures) are lower in sugar! That means its healthy, *right*?  Here is an interactive version of the [sugar level and popularity chart](https://datawrapper.dwcdn.net/mKacm/1/)

![sugar level and popularity](https://media.journalism.berkeley.edu/upload/2020/08/1597131083801a346.png)



I ranked each candy by its popularity percentile, from most to least popular. This visualization revealed that every variation of a Reese's Peanut Butter candy was in the top 10 most popular candies.

1. Reese's Peanut Butter Cup
2. Reese's Miniatures
3. Reese's Pieces
4. Reese's Stuffed With Pieces

What's more is that in the top 10 candies, 6 of the candies were nut based candies. As good as the chocolate and nut combination is, I expected nutty chocolates to rank low in popularities due to nut allergies being common among children. This visualization also revealed that all of the top 10 ranked candies are chocolate based, which isn't surprising because chocolate reigns supreme in *any* situation. 

![candy popularity](https://media.journalism.berkeley.edu/upload/2020/08/159712793510cfe61.png)


***

markdown references:

[link](https://wikipedia.org)

1. item
2. second item
3. third item

* item
* item
* item

![cat pic](https://placekitten.com/400/300)

here is some text

more text

[previous projects](http://paldhous.github.io/ucbdataviz/2017/index.html)

[cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
