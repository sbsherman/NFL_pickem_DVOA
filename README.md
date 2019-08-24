# NFL Defense-Adjusted Value Over Average (DVOA)

The Defense-Adjusted Value Over Average (DVOA) is a way of measuring the success of both the offense and the defense for an NFL team (or individual players). The basic idea of this statistis is that it assigns higher weight to plays of more importance. As an example, gaining two yards on 3rd and 10 is far from a successful play, but gaining two yards on 3rd and 1 is extremely important and would be a sucessful play. At its most basic level, in a head to head matchup the team with higher DVOA should win.

For a much more in depth description of DVOA (and its caveats) see:[Football Outsiders](https://www.footballoutsiders.com/info/methods)

# Can DVOA help win a pick 'em pool?
For the past two years I have been participating in an NFL pick-em pool (hosted by the Shir Ami Mens' Club and benefiting their charitable organizations) where we do straight-up pick 'em (you get a point for picking the correct winner of a game). Each week of the regular season, the top three competitors win money. There are also prizes for the top three competitors across the whole regular season, which is decided by the total number of games picked correctly. 

My first year competing, I picked winners by my gut instinct, which proved to be a VERY bad way of doing things. In my second year I turned to the experts of [CBS](https://www.cbssports.com/nfl/features/writers/expert/picks/straight-up/17) and [NFLpickwatch](https://nflpickwatch.com) and picked with the majority of expert analysts. This proved to be a much better method and I went from being ranked 89th out of 90 participants in 2017 (terrible, I know) to being tied for 8th out of 89 participants in 2018. What I want to know now is if using DVOA can further improve my ranking and put me in the running for weekly and end-of-season prizes. 

Comparing the DVOA of two teams competing each week seems like a great way to pick a winner because it rewards teams that can make the correct play at the correct time. I'll use the DVOA computed by Football Outsiders for each game of the 2017 and 2018 seasons (and the predictions made before the first game of the season) to see if selecting teams by DVOA alone is enough to beat the competition in the pick 'em pool for each week and the season as a whole. Football Outsiders gives several measures of DVOA (some adjusted for early season games, others weighted by most recent games) and I'll also see how those would have fared in the pool. 

# Data
- [NFL Results by year](https://www.pro-football-reference.com/years/2017/games.htm)
- [DVOA Values](https://www.footballoutsiders.com/dvoa-ratings)
- Pool results are included in this repository