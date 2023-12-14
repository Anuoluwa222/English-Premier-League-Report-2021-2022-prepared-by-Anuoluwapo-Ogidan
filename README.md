**Introduction**

Welcome to a thrilling world of data analysis! In this documentation, we will be analyzing the English Premier League 2021/2022 data which aims to provide an analysis and insights into the performance of teams participating in the league. The report leverages data obtained from Kaggle, a reputable online platform for datasets and machine learning projects. Power BI, a powerful data tool, was utilized to analyze and present the data effectively.

**Data Source**

The data for the English Premier League 2021/2022 report was sourced from Kaggle. The dataset contains detailed information about the matches, teams, goals, cards, and other relevant statistics for the season.

**Task**

Comparison between the Sum of Wins and Losses by Team: This helps analyze the relative performance of teams during the season, identifying the top-performing and struggling teams.

Comparison between Goals For and Goals Against: This will allow easy comparison of offensive and defensive strengths of the teams, highlighting the teams with the highest goal difference.

The total goals scored by each team: This will provide insights into the overall offensive performance of teams, identifying the highest-scoring teams in the league.

The rate of yellow to red cards given in the season to each team: This will showcase the distribution of yellow and red cards across teams and identify the teams with the highest numbers of yellow and red cards.

Highlighting the matches played, wins, draws, losses, goal difference, and points for each team.

**Data Preparation and Transformation**

The initial step in the process involved loading the dataset into Power BI and transforming the data through Power Query. The datasets consist of three tables namely; all match results, all players statistics and the point table. The data was inspected for any missing values, duplicate entries, or inconsistencies. Necessary transformations were performed, such as data type conversions, renaming columns and deleting columns not relevant for the analysis. This stage aimed to ensure the data was clean and ready for analysis.

**Data Modelling**

After transforming and applying the data into Power BI, data modeling techniques were applied to organize and enhance the dataset's structure. I structured the data and established a relationship between the three tables using appropriate keys. This important step will develop cordial interaction across the tables, measures and calculated columns were created to facilitate further analysis and visualization. The relationship established is shown below:

![image](https://github.com/Anuoluwa222/English-Premier-League-Report-2021-2022-prepared-by-Anuoluwapo-Ogidan/assets/141835580/27a1282b-e03c-40ae-bd73-7c5553d4e883)


**Data Exploration and Visualization**

After I have established relationship across the tables, I created important calculations that would help this analysis. These calculations include the following key measures; the total points, total wins, total draws, total losses, total goals, total goals in favor, total goals against, total red cards, total yellow cards. These calculations will provide us more insights to understand the data and find useful information.

Comparison between the sum of wins and losses by team

Based on the problem questions, comparison between sum of wins and losses by team was visualized using area chart. The x-axis represents the teams, while the y-axis represents the number of wins and losses. This chart reveals the variance between wins from losses and helps analyze the relative performance of teams during the season, identifying the top-performing and struggling teams. The result can be shown below:

![image](https://github.com/Anuoluwa222/English-Premier-League-Report-2021-2022-prepared-by-Anuoluwapo-Ogidan/assets/141835580/ce46cbb3-c3e9-4d25-88e1-95c2b7090a1b)


Comparison between Goals For and Goals Against 

I used a clustered column chart to compare goals scored for and against each team. The clustered column chart presents the goal statistics in a visually appealing manner. The x-axis represents the teams, while the y-axis represents the number of goals scored or conceded. This chart allows easy comparison of offensive and defensive strengths of the teams, highlighting the teams with the highest goal difference. The result is seen below:

![image](https://github.com/Anuoluwa222/English-Premier-League-Report-2021-2022-prepared-by-Anuoluwapo-Ogidan/assets/141835580/f0bf815f-0599-445c-967a-37324dac2f71)


Total Goals Scored 

To analyze the total goals scored by teams, I incorporated a clustered bar chart, this illustrates the total goals scored by each team throughout the season. The x-axis represents the total goals scored, while the y-axis represents the teams. This chart provides insights into the overall offensive performance of teams, identifying the highest-scoring teams in the league as shown below:

![image](https://github.com/Anuoluwa222/English-Premier-League-Report-2021-2022-prepared-by-Anuoluwapo-Ogidan/assets/141835580/c85e7337-6f37-4792-909e-8dfe375f0eb6)


The rate of yellow to red cards given in the season to each team

I used a 100% stacked bar chart to visualize the rate of yellow and red cards received by teams . The chart showcases the distribution of yellow and red cards across teams. Each team's proportionate share of yellow and red cards is displayed, allowing for a comparison of discipline levels among the teams. The chart aids in identifying the teams with the highest numbers of yellow and red cards as identified below:

![image](https://github.com/Anuoluwa222/English-Premier-League-Report-2021-2022-prepared-by-Anuoluwapo-Ogidan/assets/141835580/ab79cabc-e389-47c2-aa0e-df52fe43e11b)


Matches Played, Win, Draw, Loss, Goal Difference, and Points 

I used a table to visualize and present the matches played, wins, draws, losses, goal difference, and points for each team in the English Premier League 2021/2022. The table allows for a comprehensive overview of team performance and allows users to filter based on different criteria such as highest points, lowest points, highest goal difference, etc. The result can be shown below:

![image](https://github.com/Anuoluwa222/English-Premier-League-Report-2021-2022-prepared-by-Anuoluwapo-Ogidan/assets/141835580/f02a0bde-889e-478d-9dc1-f568da160644)


The table incorporated can also act as a slicer to navigate across teams and generate results needed. Also, an overview of the report is highlighted below:

![image](https://github.com/Anuoluwa222/English-Premier-League-Report-2021-2022-prepared-by-Anuoluwapo-Ogidan/assets/141835580/fe4fa62f-e1d6-4388-b1a8-fce070027030)


Insights and Recommendations


1. Teams with the highest points should be acknowledged for their excellent performance.
2. Analysis of goal difference can help identify the most effective offensive and defensive teams in the league.
3. Teams with a high number of yellow and red cards may need to focus on improving discipline on the field.
4. Observing the distribution of wins, draws, and losses can uncover interesting trends and patterns.
These insights can help teams identify their strengths and weaknesses, evaluate their performance, and develop strategies for improvement.

Conclusions

In conclusion, I have been able to analyze the English Premier League 2021/2022 datasets through the use of Power BI and its various functionalities to transform, model, explore, and visualize the data obtained from Kaggle. I was able to establish measures, provide careful analysis, meaningful insights, recommendations which will enable teams to make informed decisions. This report provides a comprehensive overview of team performance, facilitates performance evaluation, and assists in identifying areas for improvement.
