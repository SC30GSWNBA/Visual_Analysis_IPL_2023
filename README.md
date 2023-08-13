**Problem Statement:**

Visualize the performance of various teams in the 2023 edition of the IPL played between different teams in the group stages of the tournament using Seaborn Library in Python.

**Why Seaborn?**

Seaborn is one of the most powerful visualization library in Python. Seaborn is used to analyse and depict results with meaningful charts. It is built on top of matplotlib library and supports most of the functionalities of matplotlib.

**API Link:** https://seaborn.pydata.org/index.html

**Datasets**

There are five sets of data -

**1) Batsman_Data.csv** : Runs scored by players in each innings of each match in the group stages of the tournament. Attributes -

Match_No : Match number in the tournament
Innings : Innings in the match
Batsman : Name of the batter
Mode of Dismissal : How was the batter dismissed
Runs : Runs scored by the batter
Balls_Faced : Balls faced by the batter
4s : Number of fours hit by the batter
6s : Number of sixes hit by the batter
Strike_Rate : Rate at which the batter scored runs as compared to falls faced
Byes : Extras scored by the team in the form of byes
Leg_Byes : Extras scored by the team in the form of leg byes
No_Ball : Extras scored by the team in the form of No Balls
Wides : Extras scored by the team in the form of Wides
Impact_Sub : If the batter is an impact substitute
Captain : Is the batter the skipper of the team
Team : Name of the team

**2) Bowler_Data.csv** : Bowling Performance of players in each innings of each match in the group stages of the tournament. Attributes -

Match_No : Match number in the tournament
Innings : Innings in the match
Team : Name of the team
Batsman : Name of the bowler
Overs_Bowled : Number of overs bowled by the bowler
Maidens : Number of maiden overs bowled by the bowler
Runs_Scored : Number of runs conceded by the bowler
Wickets : Number of wickets taken the bowler
Economy_Rate : Rate at which the bowler conceded runs in each overs bowled by him.
0s : Number of zeros conceded by the bowler
4s : Number of fours conceded by the bowler
6s : Number of sixes conceded by the bowler
Wides : Number of wides bowled by the bowler
No_Balls : Number of no balls bowled by the bowler
Impact_Sub : If the bowler is an impact substitute

**3) Match_Details.csv** : Outcome of each match in the group stages of the tournament. Attributes -

Match_No : Match number in the tournament
Match_Date : Date on which the match was played
Home_Team : Name of the home team
Visiting_Team : Name of the visiting team
Ground : Name of the cricket ground where the match was played
Toss : Name of the team who won the toss
Winner : Name of the winning team

**4) Powerplay_Score.csv** : Runs scored by each team in the first 6 overs of the match in the group stages of the tournament. Attributes -

Match_No : Match number in the tournament
Innings : Innings in the match
Team : Name of the team
Powerplay_Score : Runs scored in the first 6 overs of the match by the team.
Wickets_Lost : Wickets lost in the first 6 overs of the match by the team.

**5) Team_Wise_Player_Profile.csv** : Squad details of each team in IPL 2023. Attributes -

Team : Name of the team
Player_Name : Name of the player
Role : Role of the player in the team
Batter_Type : Right handed or left handed batter
Bowler_Style : Type of Bowler
Bowler_Type : Left handed or right handed bowler
Seamer_or_Spinner : If the bowler is seamer or spinner
Overseas_Player : If the player is an overseas player

**Data Source:** https://www.espncricinfo.com/
