# About

## "WHISTLE!"

I recently started watching Ted Lasso on AppleTV+ and got interested in ~~soccer~~ football. Basic, I know, but it is what it is. As I was reading up on "the beautiful game," trying to figure out just what the heck "offside" is, I also realized I could probably use this to practice data analytics and kill two birds with one stone. Even though Ted thinks "success is not about wins and losses," most ~~soccer~~ football (dang it) fans seem to erm...respectfully... disagree. :goal_net: :soccer:

## "Because if they were curious, they would have asked questions." :dart:

I originally found the data and initial questions for this project from [DataCamp](https://www.datacamp.com/workspace/datasets/dataset-python-soccer), but actually downloaded the data on data.world, where the data dictionary is [located](https://data.world/chas/2018-2019-premier-league-matches/workspace/data-dictionary). I had to refer back to the data dictionary and several random websites to understand what all the fields meant, but I finally started to figure it out. DataCamp provided some prompts for analyzing this dataset, which I also found helpful:

- What team commits the most fouls?
- What percentage of matches end in a draw?
- Does the number of red cards a team receives have an effect on its probability of winning a game?

## "Butts on Three! 1...2..."

I used Microsoft Excel and Powerpoint for this project because I wanted to "get in some reps" with these tools. I started by checking for duplicate entries, misspellings, and such. The data were clean, so I moved on to answering the 3 questions from DataCamp.

### “Taking on a challenge is a lot like riding a horse, isn't it? If you're comfortable while you're doing it, you're probably doing it wrong.”

Working through this dataset was actually more challenging than I anticipated. Maybe because I'm not used to analyzing sports data or maybe just because it's ~~soccer~~ football, but I had a hard time reading the pivot tables I'd made comparing teams with the other fields. I kept referring back to the larger data set, which I filtered by teams, and even the official records from the Premier League, to make sure I was understanding what I was reading. In the end, I think I learned a bit about the sport and how things work - at least how it went during the '18-'19 season.

### Foul Play

Players can make a foul a number of ways, including deliberately handling the ball and the confusing "offside," resulting in the referee issuing a yellow card. Red cards can be issued for egregious fouls, or for commiting a second yellow-card-offense, and result in the player being removed from the match. Getting a red card is especially bad for the player's club because that player can't be replaced and they'll continue the match a man down. This leads to an obvious question: Does the number of red cards a club gets affect their chances of winning? I found a slight inverse relationship between how many red cards a club got and how many matches they won over the course of the season (r = -0.30). Interestingly, there was a stronger relationship in how many total fouls a club earned and how many league points the club earned at the end of the season (r = -0.51).

The English Premier League doesn't have playoffs to determine season champions like American sports tend to have. Instead, clubs earn 3 points for each win, 1 point for draws, and 0 points for losses, with the points being tallied at the end of the season. These points are then used to determine which four clubs go on to play in one of several all-Europe championship leagues (UEFA), which clubs stay in the Premier League, and which  three clubs are "relegated," or demoted, and replaced by the three clubs being promoted from the English Football League Championship. :confounded:

### "...where I'm from, you try to end the game in a tie, well, that might as well be the first sign of the Apocalypse."

Since clubs get league points for draws instead of just wins, it seemed possible that a club could still win the league with more draws than wins. While this didn't happen in the 2018-2019 season, I did check to see how many matches ended in a draw. Surprisingly, at least to me, just under 20% of matches ended in draws. Even though 19% of matches isn't a small amount, I still thought draws would be a bit more common (I'll chalk it up to American ignorance).

## "Our goal is to go out like Willie Nelson — on a high!"

Overall this was an interesting project and I'm glad I got to learn more about both football (there it is!) and data analytics.

This repo contains the original .csv file, the Excel workbook I used to analyze the data and mock up the visualizations, and the PowrPoint presentation. GitHub doesn't support files as large as the PowerPoint, so I also have it uploaded as a PDF. The photo I used for the title slide is by <a href="https://unsplash.com/@timmybech?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tim Bechervaise</a> and I found it on <a href="https://unsplash.com/photos/_hjsopbklZ0?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash.</a>

# Stupid barking means it's over, right? :dog:
