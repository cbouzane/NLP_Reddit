## Problem Statement

The aim of this project is to use Reddit's API to collect posts from two subreddits, and to then use Natural Language Processing (NLP) to identify which subreddit a given post came from. Ultimately, I will be solving a binary classification problem.    

## Executive Summary

I decided to analyze the posts between the subreddits Legal Advice and Unpopular Opinion, specifically.  Both subreddits are roughly similar in size.  Legal Advice contains roughly 942,000 users, while Unpopular Opinion contains roughly 734,000 users.  Additionaly, the posts of both subreddits were similar in style (few pictures/links, and mostly text).  However, advice and opinion can ultimately be the same thing.  I figured these subreddits could present a great opporunity to test whether a subject/theme can actually be identified with NLP.   

The first step in this project was to gather data.  I used .JSON, and luckily Reddit's API was pretty straightforward to tap into - I just added ".json" on the end of each subreddit's url. 

## Data Dictionary


## Conclusions and Recommendations

From a business standpoint, I could see model such as this being used to imrove Reddit's User Experience on the "create a post" page.