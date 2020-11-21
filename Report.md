Project Report

Problem solved:
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent had to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment.

INFO:unityagents:
'Academy' started successfully!
Unity Academy name: Academy
        Number of Brains: 1
        Number of External Brains : 1
        Lesson number : 0
        Reset Parameters :
		
Unity brain name: BananaBrain
        Number of Visual Observations (per agent): 0
        Vector Observation space type: continuous
        Vector Observation space size (per agent): 37
        Number of stacked Vector Observation: 1
        Vector Action space type: discrete
        Vector Action space size (per agent): 4
        Vector Action descriptions: , , , 

Parameters used:
        n_episodes (int): 2000 -> maximum number of training episodes
        max_t (int): 1000 -> maximum number of timesteps per episode
        eps_start (float): 1.0 -> starting value of epsilon, for epsilon-greedy action selection
        eps_end (float): 0.01 -> minimum value of epsilon
        eps_decay (float): 0.998 -> multiplicative factor (per episode) for decreasing epsilon

Neural Network Layers used:
1. Fully Connected Layer -> Input: 37 (state size); Output: 64
2. Fully Connected Layer -> Input: 64; Output:64
3. Fully Connected Layer -> Input: 64; Output:64
2. Fully Connected Layer -> Input: 64; Output:64
2. Fully Connected Layer -> Input: 64; Output:64 (action size)

Results:

Episode 100 -> Average Score: 0.18
Episode 200 -> Average Score: 1.90
Episode 300	Average Score: 4.03
Episode 400	Average Score: 5.49
Episode 500	Average Score: 7.13
Episode 600	Average Score: 8.29
Episode 700	Average Score: 8.97
Episode 800	Average Score: 10.65
Episode 900	Average Score: 12.48
Episode 1000	Average Score: 12.09
Episode 1100	Average Score: 12.12
Episode 1200	Average Score: 13.41
Episode 1300	Average Score: 13.12
Episode 1400	Average Score: 14.79
Episode 1500	Average Score: 15.24
Episode 1600	Average Score: 15.66
Episode 1700	Average Score: 15.78
Episode 1800	Average Score: 15.18
Episode 1900	Average Score: 14.00
Episode 2000	Average Score: 14.38




