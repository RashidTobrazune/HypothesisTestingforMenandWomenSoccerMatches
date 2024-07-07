# Hypothesis Testing forMen and Women Soccer Matches
![soccer-pitch](https://github.com/RashidTobrazune/HypothesisTestingforMenandWomenSoccerMatches/assets/150378293/7d3eee23-d486-4bb9-9aed-4f70b474d6af)
![pexels-rethaferguson-3621121](https://github.com/RashidTobrazune/HypothesisTestingforMenandWomenSoccerMatches/assets/150378293/084ca206-4a48-4974-a854-247680283359)

I performed a hypothesis test to determine if more goals are scored in women's soccer matches than men's.
# Task
Problem Statement
You're working as a sports journalist at a major online sports media company, specializing in soccer analysis and reporting. You've been watching both men's and women's international soccer matches for a number of years, and your gut instinct tells you that more goals are scored in women's international football matches than men's. This would make an interesting investigative article that your subscribers are bound to love, but you'll need to perform a valid statistical hypothesis test to be sure!

While scoping this project, you acknowledge that the sport has changed a lot over the years, and performances likely vary a lot depending on the tournament, so you decide to limit the data used in the analysis to only official FIFA World Cup matches (not including qualifiers) since 2002-01-01.

You create two datasets containing the results of every official men's and women's international football match since the 19th century, which you scraped from a reliable online source. This data is stored in two CSV files: women_results.csv and men_results.csv.

The question you are trying to determine the answer to is:

Are more goals scored in women's international soccer matches than men's?

You assume a 10% significance level, and use the following null and alternative hypotheses:

 H0: The mean number of goals scored in women's international soccer matches is the same as men's.

HA : The mean number of goals scored in women's international soccer matches is greater than men's.
# Solution
Process

1. Loaded the data
2. Converted date columns to datetime
3. Filtered for matches since 2002-01-01 and only World Cup matches
4. Calculated total goals scored in each match
5. Extracted the total goals into separate lists
6. Plotted to see the best hypothesis test 
7. Determined the normality and mean goal scores 
8. Performed the hypothesis test
   
Analysis

<img width="827" alt="head" src="https://github.com/RashidTobrazune/HypothesisTestingforMenandWomenSoccerMatches/assets/150378293/5e2b073a-8d5d-4b6e-b5ef-523989ef3864">
<img width="800" alt="women" src="https://github.com/RashidTobrazune/HypothesisTestingforMenandWomenSoccerMatches/assets/150378293/bb18cf09-6e3f-4df2-981c-04e9560e3afd">
<img width="782" alt="men" src="https://github.com/RashidTobrazune/HypothesisTestingforMenandWomenSoccerMatches/assets/150378293/4c4c9bb2-ce37-4dfd-8f49-1427f541c18e">
<img width="960" alt="result" src="https://github.com/RashidTobrazune/HypothesisTestingforMenandWomenSoccerMatches/assets/150378293/654116c2-246e-4768-9883-f0b5be3ea3c6">
  
   Insight
   
By rejecting the null hypothesis, we conclude that there is sufficient evidence to support the claim that the mean number of goals scored in women's international soccer matches is greater than in men's international soccer matches.



