# Reinforcement Learning Project 
## _Calculating Optimum path for Agent using Monte Carlo Learning Method in N × N grid world_

## Short briefing about Monte Carlo Method
Monte Carlo (MC) methods are able to learn directly from experience or episodes rather than relying on the prior knowledge of the environment dynamics.

This program has 2 class: `Env` for environment and `MCAgent` for the agent.
When you start the program,  the agent's seed value, reward, state, and environment are set. This code runs up to the 1000th episode. For each episode, the program calculates the values ​​for each grid, predicts the next state, and calculates the reward. When the rectangle successfully reaches the circle or hits the triangle, the rectangle ends and moves on to the  next episode.

Using Monte-Carlo algorithm, the time that had to grow to be converge nation is range on every occasion we run it. In in advance episode, the agent will movements at random. As it receives praise, it's going to examine what to do. Because it's far reinforcement learning, the agent does many exploration withinside the beginning. Agent locate top approach via way of means of hazard and examine the approach. Reward is given from the environment. According to the environment, the agent can get distinctive praise despite the fact that it's far withinside the equal nation and does the equal action.

### Results
This result (From Animation) shows that initially (In episode 2) the agent was unaware about the environment but till reaching episode 60 it becomes aware about it's environment and found it's optimum policy.

| Episode 2 | Episode 60 |
|--|--|
| ![enter image description here](https://github.com/himanshyouyadav/MonteCarlo-RL/blob/main/Images/FirstEpisode.gif) | ![enter image description here](https://github.com/himanshyouyadav/MonteCarlo-RL/blob/main/Images/FinalEpisode.gif)|

