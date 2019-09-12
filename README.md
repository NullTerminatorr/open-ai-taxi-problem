# open-ai-taxi-problem

A notebook detailing how to work through the Open AI taxi reinforcement learning problem in Python 3. Below you'll find a link to the Open AI environment page and description.

[source](https://gym.openai.com/envs/Taxi-v2/)

This task was introduced in [Dietterich2000] to illustrate some issues in hierarchical reinforcement learning. There are 4 locations (labeled by different letters) and your job is to pick up the passenger at one location and drop him off in another. You receive +20 points for a successful dropoff, and lose 1 point for every timestep it takes. There is also a 10 point penalty for illegal pick-up and drop-off actions.

[Dietterich2000]	T Erez, Y Tassa, E Todorov, "Hierarchical Reinforcement Learning with the MAXQ Value Function Decomposition", 2011.
