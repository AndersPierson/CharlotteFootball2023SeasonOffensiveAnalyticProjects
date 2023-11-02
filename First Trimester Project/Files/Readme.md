### Introduction:

The 2023 season for Charlotte Football started off rocky to say the least. A new coaching staff and half of the team being fresh on the roster has put us in an awkward position. 
While we won our first game against South Carolina State, we have failed to secure a win against our next three opponenets. This has been a debated topic of where the blame lies, and the facts show from the box score alone that the offense shares a significant share of the blame.

The problem we want to address in this project is where has the offense failed from a persepctive of the playbook. Can we just not execute on all cylinders? Do we favor an offensive scheme that our players tend to be less usccessful with?

Here we take a deep dive into our personnel and formation usage in our frist trimester of games. These two variables are significant to the foundation of a lethal offense not only in college football but also on the professional stage, just ask Mike McDaniel, Head Coach of the Miami Dolphins.
In this project we attempt to visualize the performance of the offense based on these two foundational blocks and potentially gain some insight into where we are failing and what we can possibly do to tweak the current playbook.

### Data/operation abstraction design:

I prepared my data by first scraping data from two sources:
1) The in-house database system, Catapult, that Charlotte Football uses to track all kinds of things such as player reps on plays and logging play calls made in games.
2) Pro Football Focus. Charlotte Football has given me access to the premium software from this company that allows me to scrape play data from any game in college football from the past decade.

From here, I cleaned the data through an extensive python and SQL script in Hex. I was able to get rid of null values and plays logged that resulted in a penalty or timeout that would muddle the results we have from the Tableau story. The link to this process is as follows:

### Future work:

Future work I plan to keep doing to improve my Tableau story and further my analysis is quite extensive. First, I hope to gain approval to use more data than just the first trimester as most of this data is extremely sensitive and using the full extent of the data would compromise the team and the future of their program.
Next, I want to go deeper in the analysis of how the offensive front office has effectively used the playbook. This includes an analysis of pass and run concepts, their efficiency, usage rates, and more.
