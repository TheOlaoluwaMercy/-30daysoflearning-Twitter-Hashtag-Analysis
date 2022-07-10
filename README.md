# -30daysoflearning-Twitter-Hashtag-Analysis
Analysis of [#30daysoflearning](https://twitter.com/hashtag/30DaysOfLearning?t=7fIlvikFtrVBZLJyrNy7kg&s=09) twitter hashtag with power Bi
#30daysoflearning is a learning program set up by  [TheOyinbooke](https://www.bing.com/ck/a?!&&p=7c773d4a26aa5bdab9bb0d54542f8c46JmltdHM9MTY1NzQ3NzI2MSZpZ3VpZD1lYTExZmY4OS0yZGY5LTQ0NTItYmQ3Yy0xYWM1MzUyODRlZDYmaW5zaWQ9NTE3NQ&ptn=3&hsh=2&fclid=0d6b6270-007d-11ed-9fbe-958a85e5b5a9&u=a1aHR0cHM6Ly90d2l0dGVyLmNvbS9UaGVPeWluYm9va2U&ntb=1) and his team to to help students skill up during this ASUU strike period.

## Goals and Objectives
- To access the performance of the hashtag
- To discover the engagement of the hashtag(tweets,likes,shares)
- To discover the reach of the hashtag
- To know what the hashtag users are tweeting about
- To know how people tweet with the hashtag over time
- To know the most active users of the hashtag

## Tools
- Python
- Excel
- Power BI
- Power Quwery Editor

## Tasks 
- Data scrapping with Python
- Data cleaning with Power Query Editor
- Data Visualization with Power BI

## Data Scrapping
The data used was scrapped from twitter using python code. The code extracted the tweet date,tweet url,tweeter's twitter username,tweet source,tweeter's location,tweet content, and number of likes,retweets and quotes of any tweet containing the #30daysoflearning and/or #NG30daysoflearning hashtag.
![Screenshot (141)](https://user-images.githubusercontent.com/107176991/178151811-4b98ddd2-9b66-4d05-8bb7-69002030010f.png)
The data was downloaded as a csv file
![Screenshot (142)](https://user-images.githubusercontent.com/107176991/178161567-996dd6ef-d45f-46e1-b074-beaee10ff2c3.png)

## Data Cleaning
The data was imported into power BI 
![Screenshot (143)](https://user-images.githubusercontent.com/107176991/178161614-0be5ec45-9466-45e4-b840-b75ed7471371.png)
It was cleaned using the power query editor. This involved removal of  some columns, formatting each column to the right data type and tranforming the date column to month name, month number,dayname and day number.
![Screenshot (146)](https://user-images.githubusercontent.com/107176991/178161761-8b07a76e-f672-4f51-8430-8e6c581f8bea.png)

## Insights
### Engagements
As at the time of conducting this analysis:
259 users made 986 tweets with the hashtag. These tweets gathered 16,000 likes and 3,546 likes.
![Screenshot_20220709-084210](https://user-images.githubusercontent.com/107176991/178153854-2a283832-3eef-4009-b6c4-b44705441a96.png)
### Time and Trend Analysis
The hashtag gathered more interactions in June, than in May and July. This is the expected trend because the program started in June. Tweets from May are by the organizers to sensitize students about the learning oppourtunity. 
There are lesser tweets during weekends. The fact that lesser learning activities are slated for weekends in the #30daysoflearning program schedule might be a factor contributing to this.
![Screenshot_20220709-084001](https://user-images.githubusercontent.com/107176991/178154338-678ba1a6-d42f-4964-8f77-41a27b82c5f8.png)
### Location 
The data extracted from twitter contained the locations of the users though only 63% of these locations are real locations. And the location analysis was based on this 63%. 92% of the users are tweeting from Nigeria. Tweets came in from other locations like Nainital, India, Palm Beach FL,Orlando FL, Accra Ghana,Toronto Ontario,Bahawalpur, Pakistan,Islamabad Pakistan,Virginia USA,Nainital India,Southampton England,Weija Ghana,Nepal,Hyderabad,Orange County California,Durban South Africa,St Neots,Bangladesh.
![Screenshot_20220709-084103](https://user-images.githubusercontent.com/107176991/178156074-2a31d27b-b311-448c-a401-2a389c787da5.png)
### Users
One of the organizers of the learning program [TheOyinbooke](https://www.bing.com/ck/a?!&&p=7c773d4a26aa5bdab9bb0d54542f8c46JmltdHM9MTY1NzQ3NzI2MSZpZ3VpZD1lYTExZmY4OS0yZGY5LTQ0NTItYmQ3Yy0xYWM1MzUyODRlZDYmaW5zaWQ9NTE3NQ&ptn=3&hsh=2&fclid=0d6b6270-007d-11ed-9fbe-958a85e5b5a9&u=a1aHR0cHM6Ly90d2l0dGVyLmNvbS9UaGVPeWluYm9va2U&ntb=1) is the most active user with a total of 143 tweets followed by [Richie4love](https://www.bing.com/ck/a?!&&p=a1684d25a729bb2d69cc0983f3565d6dJmltdHM9MTY1NzQ3NzM0NyZpZ3VpZD04YmEyNTZiNi00OGVkLTQ3OWUtYmRjZC0wMTAwZWVkZWI2NjYmaW5zaWQ9NTEyNg&ptn=3&hsh=2&fclid=4043821e-007d-11ed-8222-a517b4d2fe19&u=a1aHR0cHM6Ly90d2l0dGVyLmNvbS9SaWNoaWU0bG92ZQ&ntb=1) with 64 tweets. 
![Screenshot_20220709-084043](https://user-images.githubusercontent.com/107176991/178155916-7c461df4-ac3b-444b-978f-f9e75b9fabc0.png)
Further analysis can be performed to show the most active user of each track if the data of users and their track is provided.
### Tools
Learners in the data analysis track tweeted more about the learning program as shown by the higher number of mentions of their tool Excel and Power BI. 
![Screenshot_20220709-084536](https://user-images.githubusercontent.com/107176991/178156051-e6ef0862-29e8-4e1b-b106-b97b6608aaf1.png)

Interact with the dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiMmEzZWM1MTMtNTk0Mi00YjFiLWJlOWQtMTQ3YWY3NTU0MTQ4IiwidCI6IjNjOWJiNWVjLTU3NmItNDY2NS05N2Y0LTlmNDBmYzQ1YTRjMiJ9)



