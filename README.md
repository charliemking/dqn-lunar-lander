# Lunar Lander with Deep Reinforcement Learning

In this project, I built a Deep Q-Network (DQN) using PyTorch to train an agent to solve the `LunarLander-v3` environment from OpenAI Gym. I implemented key reinforcement learning techniques including epsilon-greedy exploration, experience replay, and a target network. Over 1000+ training episodes, the agent learned to land the spacecraft successfully.

Through this project, I gained hands-on experience with deep reinforcement learning and a stronger understanding of how neural networks can be used to approximate value functions in dynamic environments.

---

## Key Components

- **Environment**: OpenAI Gym `LunarLander-v3`
- **Algorithm**: Deep Q-Network (DQN)
- **Techniques**:
  - Epsilon-greedy exploration
  - Experience replay buffer
  - Target network for stable Q-value updates

---

## Training Results

- The agent learns to land successfully in most episodes by the end of training
- Rewards increase significantly across training as the policy improves
