# PPO-Agent-For_Mario-1-1

<img width="256" height="240" alt="mario_1_1" src="https://github.com/user-attachments/assets/76db06c7-c366-4859-a24e-8e81881b0b96" />

🍄 Super Mario Bros PPO Agent

A reinforcement learning agent trained with Proximal Policy Optimization to beat World 1-1 of Super Mario Bros using only raw pixels. The agent learns entirely on its own with no hardcoded rules or game state access — just frames and rewards. It uses a convolutional Actor-Critic network trained with GAE and custom reward shaping that incentivizes moving right, collecting score, and reaching the flag.

Trained from scratch on a free Kaggle T4 GPU over 2.56 million steps, the agent achieves a 40% win rate on World 1-1 with a peak reward of 312 on flag completions.
Here is a link to watch it in action: https://youtu.be/f62p6zTKea8
