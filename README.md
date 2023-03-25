# UEFA-Champions-Leguea-EDA-With-SQL-

 ## DATA Over View 
 
###### 1.  This dataset contains over 75,000 rows and 6 different sheets of data from 2016 to 2022 on players, coaches, goals, stadiums, and teams.
and lucky it was found in Kaggle: https://www.kaggle.com/datasets/acothahaha/epl-dataset-20222023-update-every-week by Abdulrahman Shiddiq Thaha
 
On Tuesday, March 14, 2023, Manchester City defeated RB Leipzig 7-0 as the away team, and it was one of the biggest losses in Champions League history, and Haland scored five goals, so I began to wonder about some other intriguing questions.
  questions including 
  
  
  
  
  
  
1.Teams that win by more than 5 goals on the road in away matches?
   
2.average time it takes teams to score five goals and more?

   
3.average goal difference between the home team and away team?
   
4.Players who score more than a hat-trick on away nights?


#### Let us  divine in 


I went ahead and wrote this following To write to check about all Matches in data 
![Fulll View data](https://user-images.githubusercontent.com/122876767/227631271-2cb8b82a-6f8c-4660-8b1e-8c0309b9b03a.PNG)
Ok, this data looks all right so, its time search for more.

For  more details about the coulms the data dictionary is providedd in kaggle dataset 


#### Teams that win by more than five goals on the road in away matches?


There is a lot of information, but I was only interested in the away team that made history nights.
I wrote this query to find what I was looking for.
![Score More Than 5 goals](https://user-images.githubusercontent.com/122876767/227632478-6f933701-3a3a-40a4-a517-0c34de89c973.PNG)


Ok, that looks great let go Barca vs Bayern 2-8 that night was shocking. 

In This querry following considerition was in in mind 

The home team should be defeated by five goals or more at their home stadium.

I checked the date and time, which matched.

###### Here result for that query


![Score 5 goal and more in](https://user-images.githubusercontent.com/122876767/227632528-7a181660-b14d-4904-87ad-0a6cf4d83d35.PNG)

  Ok, that looks great. That shows that Manchester city is not only team to score 7 goals in night but for me  Barca vs Bayern 2-8  game that night was shocking.
  
  
 #### Average time it takes to score 5 goals and more in  away game 
 
Normally time for  football match is 90 minutes so, I ask my self what is average time that it takes to score more than 5 goals in single game.
Then, I wrote this query to get that

![Avg time](https://user-images.githubusercontent.com/122876767/227690106-d654b7fd-e034-499d-9eec-252f451f8231.PNG)

This query joins the Goals and Matches tables together. And AVg time that i takes to score 5 goal in away match is 

#### 49 mintues

for the next question, it asks average goal difference between the home team and away team?
this is simply the difference between two goals scored in each net at that match. To answer that, I wrote this query

![avg Goal Difrerence](https://user-images.githubusercontent.com/122876767/227690567-7b3c1fed-a5ee-420d-8194-b9ad1e52274b.PNG)
The average goal difference between the home and away teams retrieved from this query is

#### 5 goals 

For the last quetions since Manchester City forward Haaland score 5 goal in that away game. Then, 
I ask myself players who score a HAT-trick and more in one away game ?
this following query and result for that answer 

![More than Hat trick](https://user-images.githubusercontent.com/122876767/227692457-41141832-5167-49f3-bfb4-6f1c731f86fc.PNG)


In the above query, I combine (join) the matches table with the two other tables, which are the goals and player tables, because there are 7 players who score a hatrick or more during the game, including
Kyllian Mbappe, Robert Lewandowski, Mane, and others


### Summary 
I was satisfied with all the answers I got to my queries.
This data was in good shape to use for this quick EDA analysis, which was a great exercise and quite interesting for me since I do love football.


                       .      .      .
#### Thank You so much for your time to checking out this project! I hope you have great day. 

 



 
 
   
   
