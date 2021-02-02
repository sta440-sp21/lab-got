# Instructions

Today's lab will help you with visualization, inference, and modeling of 
survival data. There is **no graded work** and your lab will not be 
evaluated.

### Data

Today's data come from Lystad and Brown's 2018 paper in *Injury Epidemiology*,
available [here](https://injepijournal.biomedcentral.com/articles/10.1186/s40621-018-0174-7).
In it, they examine time-to-death of Game of Thrones characters from seasons
1 through 7 (i.e., observations are censored at the end of season 7). Data
were originally found on the Rakesh Chintha's GitHub repository 
[here](https://github.com/genielab/got_survival_analysis).

### Example questions

**Suppose failure time in episodes is continuous.**

1. Create a Kaplan-Meier plot of all named characters in the dataset (i.e.,
all observations). What is the 75th percentile of survival time (in episodes)?
What is the median? If you cannot estimate it, why?
2. Create a Kaplan-Meier plot stratified by gender. Which gender appears to have
better survival? What is their estimated 30-day survival probability?
3. Is there evidence of differential survival by gender? Support your analysis
with a formal statistical test.
4. Create a Cox proportional hazards model incorporating screentime and
gender. Interpret the coefficients corresponding to all predictors. Is there
evidence of an association between gender and survival, after accounting for
screentime?