### What types of data am I working with?
The dataset presents **19 features** about **1199 players**, ranging from baseball-related statistics to general information such as name and the team they played for during the 2010 season.

Furthermore, of the 19 columns in the dataset, **3 are categorical features**, while the other **16 are numeric**, referring to percentages or direct data.

**Note:** descriptions of what each feature means are in the **analise_dados_mlb** notebook, so for more details, just check that notebook for more information.


### Exploratory data analysis (EDA)

#### Players above average vs Players below avarage

Analyzing the average of above-average and below-average players, it is concluded that proportional metrics (which take into account the number of games played by each player) are more suitable for identifying patterns.

Although absolute values ​​indicate that most players accumulate fewer total offensive statistics, proportional metrics reveal that the average performance per game is solid. **This suggests that the group is efficient in the opportunities it receives, but there is significant variation in game participation among the athletes**.

Below is a graph showing the difference between above-average and below-average players for each numerical feature. It shows that the proportional features **obp**, **slg**, and **bat_avg** are the only ones with more above-average players than below-average players. In the other features, the presence of star players distorts the overall average, overshadowing the performance of average and consistent players.

![mean-analysis-features](../graphs/feature-mean-analysis.png)

<sub><sup>Font: Author<sub><sup>

<sub>Note: The **analise_dados_mlb** notebook displays the percentages for each of the features (above and below), in cases where you want to analyze the data in more detail.<sub>

### Questions I aim to answer based on data analysis:

Regarding the players:
* ***Who were the best offensive players of the season?***
* ***Who were the best defensive players of the season?***
* ***Which players were the most complete (offensive and defensive) of the season?***
* ***Which players were the most efficient?***

