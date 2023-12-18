
# Fantasy Football

Fantasy Football is a popular math-based game that engages approximately 29.2 million (Statista Research) participants each year. This standard league involves assembling a roster of real-life athletes whose on-field performances determine the scoring of your team. Competing head-to-head against other league members each week, the goal is to compile the team with the most points to secure weekly victories. Win enough weeks to make the playoffs. Win the Playoffs to become Champion!

A Fantasy season begins on draft day, when teams take turns selecting players to fill out their roster. Drafting strategy is crucial as it lays the foundation for your season. A successful fantasy team requires a strategic balance of players.

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/4e46c4ce-04de-4256-8c28-52c78dd4570c)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/6da89ae8-59e2-47b4-b084-566f3587e3b3)

Once teams are set, the real action begins. Teams face off against each other weekly, setting the lineup that they think will score the most points. 

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/b2f8edc9-8a4f-4e20-ad5d-cd43a37c4b30)

With the actions taken on field reflected in the scores, Fantasy players can spend endless time analyzing data to try and find an edge. Matchups, Injuries, most recent Performances, Bye Weeks, Weather and Location, Offensive and Defensive philosophies are just some of the factors that can impact what a player may score that week. This leads to endless opportunities to find an edge!

One of the great data gathering events for Football is the NFL Combine. It is a week-long invitation only showcase where college football players perform physical and mental test in front of NFL coaches, General Managers, and Scouts. 
Some of the events include: 40 yard dash, Bench Press, Vertical Jump, Broad Jump, 3 Cone Drill, Shuttle Run. 

Using the Combine data, we wanted to investigate if there was any correlation between Combine Performance and Fantasy Points scored. 



## Analysis
### Are Combine results correlated to an increase in Fantasy Points?

Combine Athlete Position:
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/5abcb179-75da-4257-9285-2036bd13a389)

Fantasy Points Scored by Year Breakdown:
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/efac36a2-e073-4f26-b31f-2d30b32a94a8)

Fantasy Pts Scored has a pvalue 0.0 and does not follow a normal distribution.

A dip in points occured in 2017 and 2020. 2017 had low QBR and rushing yards per attempt. 2020 had special Covid rules enacted.

Combine Data:
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/034d7e8a-49d4-4a46-a27d-6dccfd773339)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/36a10283-44f3-45a5-a04e-612170c3e853)


Kicking data is lacking, while the althetic profiles of various positions is similar.
The 40 yard dash has a pvalue= 3.657943670686471e-49. A lower 40 time is good, leaving to potentially skewed data.

Fantasy Points per Combine Event:

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/a45b8c39-27a7-42c4-a155-c9ba4790eac1)

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/5451a75f-726e-4bd6-8561-5fd125fa3cb9)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/0f98ad52-4d6f-48ff-8f6d-0542ceb52133)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/9fc71ee7-e5ed-44cd-b384-1e4b005f4d1d)

After scatter plot and regression analysis of combine results measured against fantasy points. 
WR Fantasy Production by Shuttle Time: R-squared = .004
WR Fantasy Production by 3 Cone Drill
R-squared = .006
WR Fantasy Production by 40 Time 
R-squared = .006
RB Fantasy Production by Shuttle Time
R-Squared= .005
RB Fantasy Production by 3 Cone Drill:
R-Squared= .002 
RB Fantasy Production by 40 Time:
R-Squared= .002 

With the r² at less than .00 for the charts. There is little correlation between Combine Results and fantasy points over a career.


With much correlation, we began breaking the data down further.

Age and Fantasy Points:

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/beee2a1c-655e-4cc8-9e6b-670516837043)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/414aca6a-5b70-4b9f-8b5a-6f2bf6cb242a)

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/c0984205-3867-4a35-ad73-95b0893aaba8)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/f5d572c0-b567-40d5-9649-a511db935d3f)



## Group Members:
Avani Patel
Clarke Allan
Matt Owens
Banesa Casillas

## Data Sets: 
Fantasy Points: Fantasy CSV Data https://github.com/bendominguez0111/fantasy-csv-data?tab=readme-ov-file
NFL Combine Results: Kaggle NFL Combine Results https://www.kaggle.com/datasets/mitchellweg1/nfl-combine-results-dataset-2000-2022

