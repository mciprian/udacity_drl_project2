# Solution to Udacity - Deep Reinforcement Learning Project 2: Continuous Control

This repository contains the solution that I have proposed to the Continuous Control project, which is based on the material presented in the DDPG lesson. The repository consists of the following files:
- **Continuous_Control.ipynb:** Notebook that contains the adaptation of the DDPG Agent to solve the proposed problem.
- **ddpg_agent.py:** Implementation of the DDPG Agent, based on the material provided in previous lessons.
- **workspace_utils.py:** Workspace utilities, It was used to keep alive the workspace for long periods.
- **Report.pdf:** Document describing the details of the implementation
- **checkpoint_actor.pt:** Actor Model trained during the development of the project.
- **checkpoint_critic.pt:** Critic Model trained during the development of the project.

The code solves the Reacher (Version 2), which is described as (Taken from Project description): 

"a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1." 

## Instructions 

- Make sure that the Continuous_Control.ipynb, ddpg_agent.py, workspace_utils.py, checkpoint_actor.pt and checkpoint_critic.pt files are in the same folder.
- The notebook was built using the course Workspace, so it must be reproduced in a kernel that has the same libraries installed.

