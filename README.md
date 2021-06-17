# Trapis-DataScience-Training-Internship-Program
This repository contains the solution of the 3 tasks provided to me in "Trapis Data Science Training/Internship Program"

## **Task 2**: Predict housing prices using machine learing algorithm and perform EDA on the data set 
- [The dataset is available here](https://www.kaggle.com/vikrishnan/boston-house-prices)

### Context

To Explore more on Regression Algorithm

### Content

Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): 

**Data Set Information**

**Features**

|Feature|Description|
|-----|-----|
|CRIM|per capita crime rate by town|
|ZN|proportion of residential land zoned for lots over 25,000 sq.ft.|
|INDUS|proportion of non-retail business acres per town|
|CHAS|Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)|
|NOX|nitric oxides concentration (parts per 10 million)|
|RM|average number of rooms per dwelling|
|AGE|proportion of owner-occupied units built prior to 1940|
|DIS|weighted distances to ﬁve Boston employment centers|
|RAD|index of accessibility to radial highways|
|TAX|full-value property-tax rate per 10,000 dollars|
|PTRATIO|pupil-teacher ratio by town |
|B|1000(Bk−0.63)2 where Bk is the proportion of blacks by town| 
|LSTAT|% lower status of the population|
|MEDV|Median value of owner-occupied homes in 1000s dollars|

We can see that the input attributes have a mixture of units.



## **Task 3:** Perform EDA Exploratory Data Analysis on the data set

- [The dataset is available here](https://www.kaggle.com/ramjidoolla/ipl-data-set)

The Indian Premier League (IPL) is a professional Twenty20 cricket league in India usually contested between March and May of every year by eight teams representing eight different cities or states in India.The league was founded by the Board of Control for Cricket in India (BCCI) in 2007. The IPL has an exclusive window in ICC Future Tours Programme.

The IPL is the most-attended cricket league in the world and in 2014 was ranked sixth by average attendance among all sports leagues.In 2010, the IPL became the first sporting event in the world to be broadcast live on YouTube.The brand value of the IPL in 2019 was ₹475 billion, according to Duff & Phelps. According to BCCI, the 2015 IPL season contributed ₹11.5 billion to the GDP of the Indian economy.

### Dataset Information

This Notebook contains 6 datasets. The information about all of them are as follows:-

|**Dataset**|**Content**|
|----|----|
|matches.csv|This dataset contains information about details of every ipl matches e.g teams,city and stadium in which match was played,name of all the umpires, winner of toss and toss decision and also the winner.|
|teamwise_home_and_away.csv|This dataset contains information of how many matches does a team won while playing in home stadium and away and their percentage win-loss.|
|deliveries.csv|This dataset contains information about the details of every deliveries bowled in ipl.|
|most_runs_average_strikerate.csv|This dataset has the details about the runs scored by every batter along with their strike rate and average.|
|teams.csv|This dataset has the name of all the teams that have played in the history of ipl.|
|Players.xlsx|This dataset has the details of the player including their dob,batting_hand and the country they belonged.|


There are few changes that we can see in the names of the teams, in these datasets. They are:
- Deccan Chargers is renamed to Sunrisers Hyderabad 
- Delhi Daredevils is renamed to Delhi Capitals
- Pune Warriors is renamed to Rising Pune Supergiants.



## **Task 4**: Build a movie recommendation system using the given data set. 
- [The dataset is available here](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)

### Dataset Information

This Notebook contains various movies and their IMDB information. They are as follows:-

|**Feature**|**Description**|
|----|----|
|color|It contains the information whether the movies are coloured or black and white.|
|director_name|It contains the name of the director for that movie.|
|num_critic_for_reviews|Number of critic for reviews of that movie.|
|duration|This feature has the duration of the movie.|
|director_facebook_likes|Number of likes of the Director on his/her Facebook Page.|
|actor_3_facebook_likes|Number of likes of the Actor_3 on his/her Facebook Page.|
|actor_2_facebook_likes| Number of likes of the Actor_2 on his/her Facebook Page.|
|actor_1_facebook_likes|Number of likes of the Actor_1 on his/her Facebook Page.|
|gross| The Gross amount for the movie.|
|genres|The genre og the movie.|
|actor_1_name|Name of the 1st actor.|
|movie_title|Title/Name of the movie.|
|num_voted_users|Number of users who voted for the movie.|
|cast_total_facebook_likes|Total Facebook likes for the cast of the movie.|
|actor_2_name|Name of the 2nd actor.|
|actor_3_name|Name of the 3rd actor.|
|facenumber_in_poster|Number of posters on the Facebook.|
|plot_keywords|Keywords that can be used to identify the plots in the movie.|
|movie_imdb_link|The IMDB link of that movie.|
|num_user_for_reviews|Number of users who wrote reviews.|
|language|Language of the movie.|
|country|Country in which the movie was made.|
|content_rating|Rating of the content of the movie.|
|budget|Budget used for making the movie.|
|title_year|The year in which title of the movie was launched.|
|imdb_score|The IMBD score or rating for the movie.|
|aspect_ratio|It is the ratio of width to height of the scenes in that movie.|
|movie_facebook_likes|Number of likes for that movie on Facebook.|

I have used the **cosine similarity** to calculate a numeric quantity that denotes the similarity between two movies. Cosine similarity score is used since it is independent of magnitude and is relatively easy and fast to calculate. Mathematically, it is defined as follows:

![image](https://user-images.githubusercontent.com/67048227/122387230-47171c00-cf8c-11eb-8bbc-b2a2d409d9a8.png)
