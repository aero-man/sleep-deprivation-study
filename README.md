# Effects of Sleep Deprivation on Reaction Time

This is a replication of the analysis on the effects of sleep deprivation on athlete reaction time from [Belenky et al. (2003)](https://pubmed.ncbi.nlm.nih.gov/12603781/).

This analysis shows how reaction time to the [Psychomotor Vigilance Test (PVT)](https://www.sciencedirect.com/topics/medicine-and-dentistry/psychomotor-vigilance-task) increased in 18 participants over 9 days of sleep deprivation. Participants were tested on day 0, with no supposed deficits in sleep. Then over the next 9 days, they were instructed to spend 7 hours total time in bed (TIB) per night. Note that the data was modified slightly for illustrative purposes and does not include the original groups of participants who were instructed to have 3, 5, and 9 hours total TIB.

The **Psychomotor Vigilance Task** is a reaction time task, where a person clicks a button after they see an image or text appear on a computer screen. Because of it's simplicity, effects of learning from day to day are assume to be negligible.

A linear regression model showed a 10.5 ms increase in reaction time for every night of sleep deprivation (95% CI [7.5, 13.1]; *p < 0.05*).

**Source**. 
Belenky G, Wesensten NJ, Thorne DR, Thomas ML, Sing HC, Redmond DP, Russo MB, Balkin TJ. Patterns of performance degradation and restoration during sleep restriction and subsequent recovery: a sleep dose-response study. J Sleep Res. 2003 Mar;12(1):1-12. doi: 10.1046/j.1365-2869.2003.00337.x. PMID: 12603781.

## Installation
```
install.packages("infer")
install.packages("moderndive")
library(tidyverse)
library(moderndive)
library(infer)
```