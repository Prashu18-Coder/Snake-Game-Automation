Snake Game Automation (Deep Q‑Learning)
🔧 Tech Stack
- Language: Python
- Libraries:
- Pygame → game environment and rendering
- PyTorch → neural network + reinforcement learning
- NumPy / Matplotlib → state representation & training visualization

🧠 Model
- Algorithm: Deep Q‑Network (DQN)
- Architecture: Feedforward neural network approximating the Q‑function
- Key Concepts:
- State space: snake position, food location, direction, obstacles
- Action space: up, down, left, right
- Reward function:
- +ve reward for eating food
- −ve reward for hitting walls or itself
- Training loop: agent interacts with environment, stores experiences, updates Q‑values

🚀 Features
- RL agent learns to play Snake autonomously
- Experience replay buffer for stable training
- Epsilon‑greedy exploration strategy
- Real‑time visualization of training progress with Pygame



