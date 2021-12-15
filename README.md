Final_Project -- Chess Dataset

Kevin Hou
## Dataset Explain
This dataset contains all games on lichess both rated and non-rated games. Also, it haves every game who wins who losses and drew. Plus, it also have every move in the game. There are 20058 observations and 17 variables inside of this dataset.

## Why this dataset is interest to me
I start playing chess when I was 12 years old, which means I have played more than 9 years of chess. During this 9 years stretch, I have win more than 50 trophies and medals. It is one of my hobbies. Back in high school, I have started a chess club, which gave me another 2 hours to play chess. Also when I play chess, my brain will become more focus, which helps me easier to think what move should I make. I'm once a candidate master back in my country. My rating is around 2100, which is around 92 percentile on lichess.com.


## GM Hikaru
GM Hikaru once said that "I fear not the man who has practiced 10,000 openings once, but I fear the man who has practiced one opening 10,000 times" GM Hikaru once the world 2nd in chess ranking. 
## State The Problem
I will focus on Which opening has the highest winning percentage for both white and black.

## Step 1 
I want to see what is the percentage of games that are rated and not rated
## Step 2
I want to find out the average rating of both black and white. As you see the graph below, 1500 rating has the most people for both black and white. As the rating goes up or down, the amount of people drop significantly, which means that most people are around 1500 rating range.
## Step 3
I want to check the winning percentage of white, black and draw. As you see the graph below, the winning percentage of white is 50% and for black is around 45% and there are 5% of draw. The reason why white has the highest winning percentage because white can move first and can choose it's own favorite opening. Therefore, it will has the highest winning percentage.
## Step 4 
In this step, I want to check what is the top 10 opening moves. 7 of them the first move is E4, which is 68% of the top ten opening move. D4 comes in the second at 20%. And G3 is around 13%. As shown in the pie chart below.
## Step 5
I want to find out what is the top 10 opening being played on lichess through database.
## Step 6
I calculated how many games are win by each side so that later on I will be able to find the highest winning percentage for both colors. 
## Step 7
I want to find out the top 10 highest opening winning percentage for white color. I divide it by 10001 because in step 6 I found out that there are 10001 games win by white.
## Step 8
I want to find out the top 10 highest opening winning percentage for black color. I divide it by 9107 because in step 6 I found out that there are 9107 games win by black.
## Step 9
I want to find out the top 10 highest opening drawing percentage. I divide it by 950 because in step 6 I found out that there are 950 draw games.
## Step 10
I compare the winning percentage for white, black, and draw. I found out that Scotch game and Sicillian game are both in the top 10 openings. The data are all in step 7 through 9.
## Step 11
I take out the games that are played by sicillian defense and make this pie chart. As shown in this pie chart, when you play with black while using sicillian defense you have a 54% of winning the game, which is more then half of the chance. 
## Step 12
I take out the games that are played by scotch game and make this pie chart. As shown in this pie chart, when you play with white while using scotch game you have a 54% of winning the game, which is more then half of the chance. 
## Linear Regression
Comparing white rating to black rating.
## Challenges
The main challenges that I faced are that the data I tried to analyze are all mainly words, so I need to keep on using filter in order to compare the data. It is hard to made the linear regression out of the data that I have chose. But I managed to make it at last. Because I couldn't make linear regression in the beginning, I decided to make pie and bar chart.

## Why I didn’t choose Van’t kruijs Opening 
The reason why I didn't choose Van't Kruijs Opening because this opening is start from E3, which is not even in the top opening first moves despite being one of the top opening. The reason why it is one of the top opening is because there are not that many opening that start with E3 move. So if e3 is played, there is a very high chance that it will be Van't Krujs Opening.

## Conclusion
Base on this dataset and what GM Hikaru has said. I will play white using scotch game and black using sicillian defense. Even though I never played these two openings before, I am going to start learning these openings. If I has taken this class earler, I might have a higher rating if I know that these two are the top openings for white and black. From now on when I play chess, I will focus on scotch game and sicillian defense. 
