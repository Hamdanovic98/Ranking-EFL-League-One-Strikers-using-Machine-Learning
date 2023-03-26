# Ranking EFL League One Striker using Machine Learning
# This is project that aims to rank strikers from EFL League One from best to worst using Machine Learning.
# This is a project on a real case study for a club in the EFL League one.
# The methodology is explained in the report but the dataset could be a little complex.
# An explanation to some difficult features:
[1] Dispossed: Number of times a player loses the ball by getting tackled.
[2] Turnovers: How often a player loses the ball via a miscontrol or a failed dribble.
[3] Over/Underperformance: Goals and assists above expectation. The difference between scoring contribution (actual contribution to goals) and xG & xG Assisted (expected contribution to goals).
[4] Goal Conversion%: Percentage of non-penalty shots a player takes that are converted into goals.
[5] Post Shot xG: Post Shot xG earned from on-target shots.
[6] Shooting%: The percentage of total shots by a player that are on target (includes goals, saved, and cleared off line).
[7] Shot Touch%: The amount of shots a player takes as a proportion of their touches of the ball.
[8] Aggressive Actions: Tackles, pressure events and fouls recorded within 2 seconds of an opposition ball receipt.
[9] Counterpressures: Number of counterpressures. Counterpressures are pressures exerted within 5 seconds of a turnover.
[10] Crossing%: Percentage of attempted crosses that are successful and received by a teammate.
[11] Deep Completions: Successful passes within 20 metres of the opposition goal.
[12] Carry%: Percentage of a player's carries that were successful.
[13] Deep Progressions: Passes and dribbles/carries into the opposition final third.
[14] xGBuildup: A model that attributes the xG value of the final shot to all players involved in the entire possession. The buildup version omits xG and xG Assisted to focus on possession work prior to the end of the chain.
[15] xGChain: A model that attributes the xG value of the final shot to all players involved in the entire possession.
For OBV Metrics:
https://statsbomb.com/articles/soccer/introducing-on-ball-value-obv/ 
