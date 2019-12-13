# Practice-Problem-Is-this-joke-funny

### link
https://datahack.analyticsvidhya.com/contest/jester-practice-problem/

Is this joke funny? Can you predict the crowdsourced rating of a joke using the just the joke text? Take this challenge to find out!

##About Practice Problem: Is this joke funny?
Many online businesses rely on customer reviews and ratings. Explicit feedback is especially important in the entertainment and ecommerce industry where all customer engagements are impacted by these ratings. Netflix relies on such rating data to power its recommendation engine to provide best movie and TV series recommendations that are personalized and most relevant to the user.

 

This practice problem challenges the participants to predict the ratings for jokes given by the users provided the ratings provided by the same users for another set of jokes. This dataset is taken from the famous jester online Joke Recommender system dataset.

 

We thank Dr. Ken Goldberg's group for putting this super cool data together and for permission to share it with the AV community. 


###Reference: 

Eigentaste: A Constant Time Collaborative Filtering Algorithm. Ken Goldberg, Theresa Roeder, Dhruv Gupta, and Chris Perkins. Information Retrieval, 4(2), 133-151. July 2001.


## Rules
One person cannot participate with more than one user accounts.
You are free to use any tool and machine you have rightful access to.
You can use any programming language or statistical software.
You are free to use solution checker as many times as you want.
## FAQs
1.  Are there any prizes/AV Points for this contest?

This contest is purely for learning and practicing purpose and hence no participant is eligible for prize or AV points.

2. Can I share my approach/code?

Absolutely. You are encouraged to share your approach and code file with the community. There is even a facility at the leaderboard to share the link to your code/solution description.

3. I am facing a technical issue with the platform/have a doubt regarding the problem statement. Where can I get support?

Post your query on discussion forum at the thread for this problem, discussion threads are given at the bottom of this page. You could also join the AV slack channel by clicking on 'Join Slack Live Chat' button and ask your query at channel: practice_problems.

## Problem Statement
The dataset contains anonymous ratings(-10 to 10) provided by a total of 41,000 users. Train file contains 1.1 million ratings and in the test file the user needs to predict the ratings provided by the same set of users on a diffrent set of jokes. The complete text for all 139 jokes is also provided in a separate csv. Given the combination of user and joke, the task is to predict the rating given by that user to the joke in the test set

## Public Private Split
Private split contains 60% of jokes from the test file rated by each user, while the public split contains the other 40% rated by the same user.

## Evaluation Metric
The evaluation metric for this challenge is root mean squared error (RMSE)




