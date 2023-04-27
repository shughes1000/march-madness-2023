# March Madness 2023

Using previous college basketball games, I aimed to accurately pick the results of the 2023 Men's and Women's March Madness tournament. However, creating a successful March Madness bracket involves much more than simply selecting the team with the best chance of winning. Many competitors will enter their bracket into a tournament pool with the sole objective of finishing as a top entry against potentially thousands of competitors' bracket entries. Thus, one must accurately predict upsets in order to win their pool. With this in mind, I used the following process to generate a 93rd percentile bracket: 

1. Create a machine learning model that predicts results of potential March Madness matchups
2. Convert matchup probabilities to probabilities that a team advances to a certain round in the tournament
3. Simulate generated brackets against hypothetical public brackets to find the bracket with the highest chance of winning a tournament pool

Data was supplied by the following Kaggle competition: https://www.kaggle.com/competitions/march-machine-learning-mania-2023

Public odds were scraped from ESPN: https://fantasy.espn.com/tournament-challenge-bracket/2023/en/whopickedwhom and https://fantasy.espn.com/tournament-challenge-bracket-women/2023/en/whopickedwhom

Because the file sizes are large, it is unfortunately not feasible to upload all datasets used in the project. However, I have uploaded all relevant code. 
