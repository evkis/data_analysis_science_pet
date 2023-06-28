## Patterns that determine the success of games
[Link](https://github.com/evkis/data_analysis_science_pet/blob/main/patterns_that_determine_the_success_of_games/03_patterns_that_determine_the_success_of_games_en.ipynb)

### Description

Using historical data on sales of computer games, user and expert ratings, genres and platforms, task is to identify patterns that determine the success of the game.

### Keywords

gamedev, internet shops, marketing analysis, EDA, descriptive statistics, statistical hypotheses analysis, t-test

### Stack

python, pandas, numpy,matplotlib

### Input Data 

Analysis for  an online store that sells computer games all over the world. Historical data on game sales, user and expert ratings, genres and platforms (for example, Xbox or PlayStation) are available from open sources. It is needed to be identify the patterns that determine the success of the game. This will allow  to bet on a potentially popular product and plan advertising campaigns.

Here is the data up to 2016. Let's imagine that it's December 2016, and you're planning a campaign for 2017. We need to work out the principle of working with data. It does not matter whether you forecast sales for 2017 according to 2016 data or 2027 according to 2026 data.
*Input file*

 games.csv
 
*Description*

- *Name* — name of the game;
- *Platform* — platform;
- *Year_of_Release* — year of release;
- *Genre* — genre of the game;
- *NA_sales* — sales in North America (million dollars);
- *EU_sales* — sales in Europe Union (million dollars);
- *JP_sales* — sales in  Japan (million dollars);
- *Other_sales* — sales in other countries (million dollars);
- *Critic_Score* — critic score (max 100);
- *User_Score* — user score (max 10);
- *Rating* — ESRB rating(Entertainment Software Rating Board).

### Conclusion

The parameters determining the success of the game in different regions of the world are revealed.
Based on this, a report has been prepared for a computer game store for planning
advertising campaigns. Data preprocessing and analysis were carried out. The current
period for analysis is selected. Portraits of users of each region have been compiled.
Hypotheses have been tested: the average user ratings of the Xbox One and PC platforms are the same;
the average user ratings of the Action and Sports genres are different. The Student's criterion for independent samples was used in the analysis.
