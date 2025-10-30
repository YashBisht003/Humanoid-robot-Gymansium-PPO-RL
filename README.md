# Humanoid-robot-Gymansium-PPO-RL
🤖 Deep Reinforcement Learning for humanoid robot locomotion using custom PPO implementation. Features mixed precision training, GAE, parallel environments, and comprehensive monitoring with TensorBoard. 

🌟 Features

Custom PPO Implementation: Built from scratch with PyTorch for continuous control
Mixed Precision Training: Automatic mixed precision (AMP) for faster training
Advanced Learning Rate Scheduling:

Warmup phase for stable initial training
Cosine annealing for optimal convergence


Generalized Advantage Estimation (GAE): Efficient advantage calculation with bias-variance tradeoff
Parallel Environment Training: Vectorized environments for efficient data collection
Real-time Monitoring:

TensorBoard integration for live metrics
Video logging of agent performance
Comprehensive loss and reward tracking


Early Stopping: KL divergence-based early stopping to prevent policy collapse

📋 Requirements
torch>=2.0.0
gymnasium>=0.29.0
numpy>=1.21.0
tensorboardX>=2.6
tqdm>=4.65.0
imageio>=2.31.0
imageio-ffmpeg>=0.4.8
🚀 Installation

Clone the repository:

bashgit clone https://github.com/yourusername/humanoid-rl.git
cd humanoid-rl
