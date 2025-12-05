# 144-Persona-Project
relationship between volleyball stats

## Motivation
As a Division III volleyball player, I spend every day surrounded by the strategy, rhythm, and competitive dynamics of the sport. Playing at the collegiate level has not only deepened my love for volleyball, but has also sparked an interest in the statistical patterns behind team success. Because I regularly analyze match film and scout reports, I became increasingly curious about which measurable factors truly contribute to high-level performance across Division I volleyball. This project is motivated by that curiosity. By examining NCAA Division I team statistics, I aim to identify the offensive metrics most strongly associated with team success. Ultimately, I hope that uncovering these patterns can help illuminate what makes a great volleyball team and provide insights that extend beyond my own division and experience.

Dataset: https://github.com/mauramcausland/144-Persona-Project/blob/main/Book%206(Sheet1).csv

## Visualization
![Hitting vs Win%](144-PDP-Graph.png)
**Figure 1.** This scatterplot shows the relationship between each Division I volleyball team's win percentage and their team hitting percentage ((#kills - #errors)/total attempts). Each point represents a team, with a color legend for number of hitting errors made by a team. The visualization suggests a positive association: teams with higher win percentages tend to have a higher hitting percentage. However, with the gradient legend, you can see that teams who make more hitting errors tend to have a higher win percentages compared to teams with the same hitting percentage. This could be due to those teams playing more sets, more chances to make errors, or those teams are willing to take more risks with swings leading to higher error but also higher kills. This supports the intuition that strong offensive performance (more successful attacks) contributes to overall team success.

## Summary Statistics for Kills

| Statistic | Value |
|----------|-------|
| Min      | 591   |
| Q1       | 1007  |
| Median   | 1094  |
| Mean     | 1083  |
| Q3       | 1164  |
| Max      | 1401  |

### Analysis: Summary Statistics + Outlier Identification

I chose to perform exploratory data analysis by computing summary statistics for the kills variable and then identifying potential outliers. I selected this technique because kills are one of the core offensive metrics in volleyball, and understanding their distribution helps reveal how teams differ in offensive output. 

The analysis showed that 50% of the teams cluster between 1007 and 1164, with just one outlier exceeding expectations and about a dozen teams not quite meeting the offensive mark. This high-kill outlier represents Nebraska Volleyball, an elite offensive program, the starting setter was just named BIG10 player and setter of the year. This analysis helped contextualize the visualization by confirming that the highest-performing offensive teams also tend to be the winningest teams overall.
