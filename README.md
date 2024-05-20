# mlb-bat-tracking
MLB home run prediction 

In Major League Baseball (MLB), players are constantly striving to develop and grow through training, seeking to gain an edge over their opponents. With the growth of baseball data via Baseball Savant, the sport has evolved significantly in both hitting and pitching. For example, the increased awareness of launch angle and exit velocity has led to a rise in both home runs and strikeouts. While this isn't a direct result of the hyper focus on data, it is related to factors such as the fascination with home runs and the associated increase in contract amounts for higher baseball statistics.

MLB has recently implemented a tracking system in stadiums called the Hawk-Eye tracking system, which uses 12 cameras, including five that run at 300 frames per second, to log data across the diamond with every pitch. The league spent two years developing a bat-tracking model with this system and released its findings via Statcast on Monday, May 13th.
With the newly released measures of swings from MLB players, such as swing length and swing speed, batters in the MLB will undoubtedly use this data to adjust and refine their swings. Therefore, our main question is: which of the new characteristics measured are key to achieving a "good" batting average (batting average of .300+)? We aim to build a model to predict batting average using the new Statcast data and quality of swing data. An extension of this work will be to perform similar analysis for on-base percentage and slugging percentage.


Data: 
The data is gathered from Baseball Savant using the notebook MLB-ScrappingData.ipynb.  

Stakeholders:
MLB training staff and players to have a better idea of what things to focus on when doing batting training. 
Those interested in MLB fantasy.

KPI:
Accuracy of predicted batters statistics

