# lsmdps_demo
Tutorial of Linearly Solvable (Discrete) MDPs (Todorov et al., 2009)
The whole method revolves around a desirability function that quantifies how relatively desirable each state is in the MDP. Given the desirability function, optimal action can be computed directly without additional iterative costs.
Tutorial structure:
Part 1: Z-Iteration: A fast method (orders faster than policy iteration) to approximate the desirability function given the associated costs and MDP.
Part 2: The simpler case of Z-Iteration (Linear equation): With additional domain knowledge of terminal states and terminal costs, the desirability function can be found with a one-step linear equation (computational complexity of half a step in policy iteration!).
Part 3: Z-Learning: Without model and cost knowledge, an online method to learn desirability function from transitions and reward.
