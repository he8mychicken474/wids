This is the repository for the WiDs project of using RL in Supply Chain Analysis.
So far, 

- **Assignment 1 – FrozenLake (Tabular Reinforcement Learning):**  
  Implemented and compared **Q-Learning (off-policy)** and **SARSA (on-policy)** in the FrozenLake environment to analyze the effects of **ε-greedy exploration (fixed vs decaying)** and key hyperparameters (**learning rate α and discount factor γ**). The experiments highlighted how decaying ε improves exploration–exploitation balance, lower α stabilizes learning over long training runs, and higher γ favors long-term reward optimization.

- **Assignment 2 – Circular Track Driving (Continuous Control with PPO):**  
  Designed a **custom physics-based continuous control environment** for driving a car on an annular track by defining the **state space, continuous action space, and a structured reward function**. Trained the agent using **Proximal Policy Optimization (PPO)**, chosen for its ability to handle continuous actions and provide stable on-policy learning, resulting in efficient lap completion with minimal radial deviation.

Studied MARL Algorithms and analysed MADRL For Inventory Management to understand the existing research done behind this project and the potential applications of the same.

This project, as instructed by my mentor is a project oriented towards research and is not a traditional WiDs course.

