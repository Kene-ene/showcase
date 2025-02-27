# Reinforcement Learning for Industrial PID Control Systems.

This thesis builds on the work of Lawrence et al. (2020) where a proportional-integral-derivative (PID) controller is represented by a shallow neural network. This legacy work was completed using the Deep Deterministic Policy Gradient (DDPG) reinforcement learning (RL) algorithm and implemented via the Spinning Up RL library. This project migrates "legacy" work to the more up-to-date Stable Baselines 3 repository with the implemententation of the Twin Delayed DDPG algorithm (TD3), the direct successor of DDPG. In doing so, earlier work benefits from the clipped double-Q networks of TD3 which address overestimation in the DDPG algorithm and the more intuitive PyTorch deep RL framework for building neural networks.

Supplementary code to be provided. 

Resources:
1. Open AI Spinning Up: https://spinningup.openai.com/en/latest/
2. Open AI Stable Baselines 3: https://stable-baselines3.readthedocs.io/en/master/
3. Reinforcement Learning in 3 Hours | Full Course using Python, by Nicolas Renotte: https://www.youtube.com/watch?v=Mut_u40Sqz4&t=9306s&pp=ygUgcmVpbmZvcmNlbWVudCBsZWFybmluZyB0dXRvcmlhbCA%3D
4. Sutton and Barton - Reinforcement Learning: An Introduction
5. David Silver UCL Reinforcement Learning Series: https://www.davidsilver.uk/teaching/
6. More to come...
