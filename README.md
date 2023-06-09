# Looking for Ways to Get the Most Comments on Hacker News Posts

## Introduction

Hacker News is a site started by the startup [incubator Y](https://www.ycombinator.com) Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

Our main task in this project is to analyze  **Hacker News posts** . We want to find out which posts are more likely to get the most comments on average. We also want to know if the post creation time affects the number of comments they receive.


**Hacker News** mainly consists of two types of posts. Among these type of posts are: 
 * **ASk HN**: In this type of posts, users get to ask the Hacker News Community a question to get clarified
 * **Show HN**: Here a users show the Hacker News community a project, product, or just something interesting.
 
 Our analysis shall focus on these two type of posts.
 
 In our research, we learned that **Ask HN** gets the most comments. The creation time of the post also affects the number of comments per the post. The following will show the steps we used to achieve our goal.
 
 We are using [this](https://www.kaggle.com/datasets/hacker-news/hacker-news-posts) dataset from Kaggle. You can download it directly from this link.


# Conclusion

The goal of our project was as follows. To understand which **Ask HN** or **Show HN** posts get more comments on average and whether time of the day affects this. To do this, we first calculated the average number of comments for each type of posts. Then we calculated the average number of comments **Ask HN** posts receive by hour created to see if it affects the average number of comments.

In the end, we learned that Ask HN posts gain a lot more comments on average. Time is also greatly affects the average number of comments per post. The best hours for Ask HN posts is between 13:00 and 16:00.
