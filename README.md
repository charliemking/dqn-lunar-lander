# Lunar Lander with Deep Reinforcement Learning

In this project, I built a Deep Q-Network using PyTorch to train an agent to solve the `LunarLander-v3` environment from OpenAI Gym. I implemented key reinforcement learning techniques including epsilon-greedy exploration, experience replay, and a target network. Over 1000+ training episodes, the agent learned to land the spacecraft successfully.

Through this project, I gained hands-on experience with deep reinforcement learning and a stronger understanding of how neural networks can approximate value functions in sequential decision-making tasks.

---

## Key Components

- **Environment**: OpenAI Gym `LunarLander-v3`
- **Algorithm**: Deep Q-Network
- **Techniques**:
  - Epsilon-greedy exploration
  - Experience replay buffer
  - Target network for stable Q-value updates

---

## Training Results

- The agent learns to land successfully in most episodes by the end of training
- Rewards increase significantly across training as the policy improves

<p align="center">
  Training Performance
  <img src="training_results.png" width="900" alt="Episode returns and lengths during training">
</p>

- **Left**: Episode Returns – shows reward increasing over 1000 episodes
- **Right**: Episode Lengths – shows agent learning more efficient landings
