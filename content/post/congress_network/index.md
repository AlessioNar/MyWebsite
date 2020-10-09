---
author: Alessio Nardin
categories:
- pol_sci
date: "2020-05-02"
description: Measuring the polarization of Democrats and Republicans on Twitter
image: matt-le-SJSpo9hQf7s-unsplash.jpg
tags:
- Social Network Analysis
- R
title: Mapping the US political community
---

# Goal

The objective of this analysis was to map the structure of the social network of the US political community on Twitter and to detect the relationships between members of different party affiliations and ranks.

## Sample choice 

Why the United States? I chose the United States because 

- the bipartisan division makes it relatively easy to classify elected officials;
- Twitter is commonly used as a means of communication for reaching to the electorate and shaping the public discussion;
- there is a broad literature treating the political usage of social media.

As of the 1st May 2020, the Senate was formed by 100 Senators, and the House of Representatives of 436 Representatives out of 441 (5 seats are currently vacant). I included in the Presidential Cabinet the 23 Cabinet members, the President, and the First Lady. I decided to include her in the analysis because of her importance in the political and social sphere of the country. 

## About Twitter usages: following and followed

Twitter is used by politicians to convey their positions with the electorate, of enhancing the public debate, and, more in general, campaigning. 

The rate of usage of US politicians of the social media technology is very high. All of the users have at least one account. Contrary to other countries' political communities such as South Korea or Italy, among the Congress members there is a tendency of using "insitutional" accounts preceded by sigle as "rep", "sen". The rate of verified is also very high, demonstrating that common practices among the political community are in place. 

The variable that I have taken in account: friends, is more practical than the function get_followers. There are structural limitations decided by Twitter that makes easier the application of the get_friends fuction. In this way it is possible to gather all the accounts followed by the poliicians and then to see the relations among a predetermined list of individuals.  

Following allows an account to receive the feed of the microblogging acivity of another user. People can follow somebody on Twitter for many different reasons. Especially, in the political activty motivations can span from discussion of the daily political agenda, to monitoring the communication strategy of the opponents or the needs of their constituencies and their opponents', among others.

While posting requires the user to actively participate to the Twittersphere, the simple act of following doesn't necessarily implies it. An user can follow a large number of accounts and not interact with, comment, or repost any of their tweets. 

Being followed, on the other hand, is essential in order to increase the reach of the communication campaigns on Twitter. In a closed network, a user that is followed by a large number of the remaining accounts possess a high visibility potential, since through the act of posting it can potentially deliver messages directly towards a greater proportion of other accounts. 

An increase in the visibility potential of the followed is corresponded by an increase in the information potential of the following. I speak of potential (or probability) because the realized value may vary a lot depending on exogenous variables.

## Social Network analysis

