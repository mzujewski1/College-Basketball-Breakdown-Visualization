# Data Visualization Project

## Data


The [College Basketball Team Performance Dataset](https://www.kaggle.com/datasets/andrewsundberg/college-basketball-dataset) provides a detailed breakdown of team performance during the 2024 college basketball season. It includes advanced metrics that evaluate offensive and defensive efficiency, shooting percentages, rebounding statistics, and other key indicators of team success.

### Dataset Breakdown:

- **TEAM**: The name of the team.
- **CONF**: The conference the team belongs to.
- **G**: Number of games played.
- **W**: Number of games won.
- **ADJOE**: Adjusted Offensive Efficiency (points per 100 possessions).
- **ADJDE**: Adjusted Defensive Efficiency (points allowed per 100 possessions).
- **EFG%**: Effective Field Goal Percentage (adjusted for 3-point shots).
- **3P%**: Three-point shooting percentage.
- **2P%**: Two-point shooting percentage.
- **ORB**: Offensive Rebound Percentage.
- **DRB**: Defensive Rebound Percentage.
- **FTR**: Free Throw Rate (free throws made per field goal attempt).
- **WAB**: Wins Above Bubble (a measure of performance relative to tournament qualification).
- **SEED**: The team's tournament seed.



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

1. **How do different conferences compare and stack up?**  
   Visualize and compare the number of tournament teams and their seeds across different conferences to see which conferences perform best.

2. **Are conferences top-heavy or balanced in their team performance?**  
   Examine whether conferences have a few top teams that dominate or if performance is more evenly distributed across teams.

3. **What is the distribution of tournament teams within and across conferences?**  
   Explore how tournament teams are spread within each conference and compare that to the overall distribution.

4. **How do different seeded teams compare within a conference and across all conferences?**  
   Analyze how teams with different seeds perform within a single conference and compare this to other conferences.

5. **What do conference stat averages look like?**  
   Calculate and visualize average stats (e.g., offensive/defensive efficiency, shooting percentages) for each conference to provide a holistic view of conference strengths.


## Sketches
[![Sketch](https://lh3.googleusercontent.com/pw/AP1GczPNMogbMspJSh9ucclf6xDOiCJ14V725D5VTRJqjtmmCuFufjMsxgi6hyI8iogMp44Zzm5NBddTTBauuCCFBxrbCjpJ_2fQatbmwLK63QhmVENybQ=w2400)](https://lh3.googleusercontent.com/pw/AP1GczPNMogbMspJSh9ucclf6xDOiCJ14V725D5VTRJqjtmmCuFufjMsxgi6hyI8iogMp44Zzm5NBddTTBauuCCFBxrbCjpJ_2fQatbmwLK63QhmVENybQ=w2400)

The sketch represents the second design iteration where interlocking boxes are used. The whole square area represents all the teams in the conferences, allowing the viewer to easily compare different conferences. The teams are placed inside the conference blocks, displaying their seed numbers and potentially a team logo. This layout aims to make comparisons clearer by grouping teams within their respective conferences. 

I also plan to create a deeper view where the user can focus on a single conference to compare teams in detail. Hovering over a team will reveal additional statistics, such as adjusted offensive and defensive efficiency.


### Prototype
[![Prototype](https://lh3.googleusercontent.com/pw/AP1GczPm4kL3t0wYScnUbDJL8TPLS9JZTcyapq_o92RO-3LskB5G5TZvlL5kZ7Vn7qYm5yGjAeSLAt4YPc-5DDbL1tmxxbSsUUcL-MwBZmxIJxu1FfQ2Fw=w2400)](https://lh3.googleusercontent.com/pw/AP1GczPm4kL3t0wYScnUbDJL8TPLS9JZTcyapq_o92RO-3LskB5G5TZvlL5kZ7Vn7qYm5yGjAeSLAt4YPc-5DDbL1tmxxbSsUUcL-MwBZmxIJxu1FfQ2Fw=w2400)

With the second design, I implemented interlocking boxes to represent conferences, allowing for an easy comparison of conferences by visually organizing teams within each block. I’m still refining the layout for conference and team blocks, including scaling and colors, to make sure the visualization is clear and informative.

Some potential features include:
- **Conference Views**: Allowing users to view a single conference independently.
- **Hover Interactions**: Showing detailed stats when hovering over a team.
- **Conference Stat Averages**: Displaying summary stats for each conference.
- **Animation**: Potentially animating teams based on their seed order.


## Open Questions

(describe any fear, uncertainty, or doubt you’re having about the feasibility of implementing the sketched system. For example, “I’m not sure where to get the geographic shapes to build a map from this data” or “I don’t know how to resolve the codes to meaningful names” … Feel free to delete this section if you’re confident.)

## Milestones

(for each week, estimate what would be accomplised)
