# ReccomenderSysterms-IBM  

**Introduction**:  
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like.  

Though the above dashboard is just showing the newest articles, I could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.  

In order to determine which articles to show to each user, I will be performing a study of the data available on the IBM Watson Studio platform. One can create one's own account to become a part of their community, and get a better understanding of their data by creating an account on the platform here.

**Tasks Performed**:  
I.<ins>Exploratory Data Analysis</ins>:  
Before making recommendations of any kind, I will need to explore the data I am working with for the project. I've Dived in to see what I can find. There are some basic, required questions to be answered about the data I am working with throughout the rest of the notebook.

II.<ins>Rank Based Recommendations</ins>:  
To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles I might recommend to new users (or anyone depending on what I know about them).

III.<ins>User-User Based Collaborative Filtering</ins>:  
In order to build better recommendations for the users of IBM's platform, I could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. I will implement this next.

IV.<ins>Matrix Factorization</ins>:  
Finally, I will complete a machine learning approach to building recommendations. Using the user-item interactions, I will build out a matrix decomposition. Using my decomposition, I will get an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). I will finally discuss which methods I might use moving forward, and how I might test how well my recommendations are working for engaging users.
