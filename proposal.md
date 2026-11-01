
The Question:The question that I would like to pose for a final project is has the median age of players that are drafted 
into the NFL change after athletes begin earning name image and likeness money or more commonly known as nil money. And 
this could go further when begging the question if the changes hold up when you take into position and draft round of these 
players drafted. 

Who Would Care? I know for sure normal people that are interested in the NFL and football would be intrigued by this question.
I asked a few of my friends what they thought about it and they were definitely interested in what my findings would be. 
However I feel like the NFL's drafting agents would care most about this question because if a player is staying in college 
for possibly three years longer than that is affecting their prime years in the NFL Or at least taking a bit away from them,  
football is a super high contact sport so players don't have that long of a career span typically thus this information being 
crucial to them. 

What I expect to find:I definitely expect to find that the median age of rookies has risen since the introduction of NILmoney. 
Another thing that I think would definitely be affecting the state massively that is going to cause the median age to rise is
that a lot of players have had covid eligibility which means they have been able to play college football longer than 4 years.

The exact source:  https://github.com/nflverse/nflverse-data/releases/download/draft_picks/draft_picks.csv  https://github.com/nflverse/nflverse-data/releases/tag/players
These are the two links that I found on GitHub for this they both have draft and player data one having the players ages and 
the other having the birth dates thus giving me the ability to be able to actually go through and check birthdays according 
to when they started as rookies so it could be  as accurate as possible.

How I will get the data: To get the data out of the csv’s I will use Python and use different pandas functions that we have 
learned throughout the year to extract the data then I will form the two tables together with a shared ID so we can see the 
values for each year.

The Scope: When taking a look at the scope of all this we could take a look at all the players drafted before 2021 more 
specifically July 1st that is when nil money first took place meaning anything after that we could use as a post nil section 
and anything previously would be pre-nil we could use for the data.

The Analysis: So I'll start off by Computing each player's age on April 30th of the draft year that is selected  
because that is a pretty close average of the draft years, then I'll take the median for each class and plot it on a line 
where we can see where nil started and where it was not in effect yet. I will also highlight the 2022 and 2023 classes 
because those were the covid years that were affected  then I'll compare the differences between the pre and post and NIL eras.
I will also check if there are any discrepancies based on position since there are some positions that are older and younger.

Terms Of Service and the robots txt: I first off tried to go to a website called pro football reference which had a lot of 
data I would need to use however I did get a 403 when I prompted it. so I pivoted to this GitHub project called NFL verse 
that had these files within the project and in there license it does say “From the nflverse's perspective, CC-BY 4.0 loosely 
means anyone is permitted to use any of the CC-BY 4.0 datasets for both non-commercial and commercial purposes provided 
that you attribute the nflverse and (if applicable) the provider nflverse sourced it from. “ So I'm pretty sure it's all 
good to use, considering I cite them when it is needed and I'm also using it for school purposes even though it seems that 
doesn't matter here. 

Personal Information:The data has names and birth dates of every player drafted in the NFL they're all very public figures 
whose draft details are publicly online however I only really need the names for the database so I'll use a player ID and
their birth dates I'll only use them for those charts and graphs so no files of anyone's name specifically are going 
to be posted anywhere.

The biggest risk: The biggest risk going up into this is there's a possibility that some players might not have their 
birthday in these tables which could skew the data. Another risk I would have like I mentioned previously some positions 
have much higher age ranges than others so that could also possibly skew the data.

