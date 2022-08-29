# Example DQN implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_dqn_example/blob/master/dqn_tutorial.ipynb) of deep q-network (DQN) with ReLAx.

DQN actor was trained on Atlantis-v0 Atari Gym environment for 3m env-steps. 

__!Note:__ For demonstration purposes training was run only for 3m steps. In papers, DQN and its augmentations are trained for 200m steps, which may require several days of learning. That is why performance is lower than reported in papers.

The graph of average return vs environment step is shown below (logs done every 50k steps):

![dqn_training](https://github.com/nslyubaykin/relax_dqn_example/blob/master/dqn_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![dqn_q_func](https://github.com/nslyubaykin/relax_dqn_example/blob/master/dqn_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187164243-2189d1ec-8472-4e87-8f2a-82f85d276027.mp4
