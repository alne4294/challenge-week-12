# Challenge Week 12 Submission Template

# Reddit Data Challenges

## Challenge 1

![Insert Screenshot](rc1.png)

## Challenge 2

All of the documents have a 'like' and 'replies' value of null.

![query](rc2.png)

## Challenge 3

We may want to look at the behavior of the authors that make the most comments and compare that to users that have less activity (excessively high activity may indicate spammers, moderators, or other alterier intentions)... The five most frequent authors were:
"AutoModerator", "value" : 12520
"pixis-4950", "value" : 9521
"ModerationLog", "value" : 7820
"imgurtranscriber", "value" : 7403
"LiveMeme_Transcriber", "value" : 5594

![query](rc3.png)

## Challenge 4

If we could look at common words, it could give us some indications about the population that uses it.
For example, we notice that 217,677 documents contain the word "hate" while 1,564,778 documents conatin the word "like".  That can help suggest the sentiment of the site, while other keywords can indicate what the content of the posts are typically about.

![query](rc4.png)

## Challenge 5

I couldn't find reddit.json or figure out how to link the subredit_counts with the mongo database... however, I was able to do the bonus challenge to create a query to sort they subreddits with the most number of comments.  Here are the top ten:

{ "_id" : "AskReddit", "value" : 1381077 }
{ "_id" : "funny", "value" : 414800 }
{ "_id" : "AdviceAnimals", "value" : 359460 }
{ "_id" : "pics", "value" : 325559 }
{ "_id" : "leagueoflegends", "value" : 310783 }
{ "_id" : "WTF", "value" : 301396 }
{ "_id" : "gaming", "value" : 269637 }
{ "_id" : "nfl", "value" : 209344 }
{ "_id" : "worldnews", "value" : 191495 }
{ "_id" : "videos", "value" : 168662 }

![query](rc5.png)

## Challenge 6

Since the data is only a subset of reality, we need to adjust our conclusions.  Perhaps it is actually more representative of the Reddit population, since only the comments that were approved by the populace were included.  However, we will not notice certain niches that may be equally important, even if not "liked".

## Challenge 7

Are conclusions would only apply to this subset.  We would need to do further analysis what an upvote means before adjusting them.

## Challenge 8

Limitations in data... we only have so much time in the data set.  Perhaps it is restricted to a geographic region or occurred during some sort of special day which could have affected the behavior.

## Challenge 9

Look at world events surrounding this date or evaluate the quantitative limitations of the data set.

## Challenge 10

On Aug. 28, 2013, the day of this data, there were breaking news about conflict in Syria and a cyberattack on the New York Times website.  These stories (especially the latter) could certainly change the "normal" commenting behavior on Reddit.

# Yelp and Weather 

## Challenge 1

![Screenshot your query and a result](yc1.png)
Answer: 62

## Challenge 2

![Answer](yc2.png)
Answer: 110.083333

## Challenge 3

![Query snippet](yc3.png)
Answer: 1630

## Challenge 4

![Query snippet](yc4.png)
Answer: 12572

## Challenge 5

![Query snippet](yc5.png)
Answer: 7502

## Challenge 6 [BONUS]

[Code]
[Answer]



