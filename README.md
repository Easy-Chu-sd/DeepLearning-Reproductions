##  About The Project

This repository documents my extracurricular, self-directed journey into Deep Learning and Reinforcement Learning. Rather than simply using high-level APIs, the focus here is on **implementation-driven understanding**—translating theoretical concepts and mathematical formulas from classic papers into explicit PyTorch code.

The project is structured hierarchically, from foundational tensor operations to advanced Reinforcement Learning algorithms.

##  Current Repository Contents

This repository is structured hierarchically to reflect my learning path. All folders contain explicit PyTorch implementations and functional training scripts.

### Layer 1: Deep Learning Foundations (PyTorch)
Contains foundational scripts demonstrating the core deep learning pipeline, built without relying on high-level wrappers.
- [x] Tensor manipulation and dimension management (`view`, `reshape`, device allocation)
- [x] Explicit forward and backward training loops
- [x] Basic neural network architecture construction using `nn.Module`

### Layer 2: Computer Vision 
Focusing on image classification architectures and addressing gradient vanishing issues in deep networks.
- [x] **ResNet:** Implementation of residual blocks and bottleneck architectures, demonstrating practical intuition for skip connections.

### Layer 3: Reinforcement Learning (RL)
Functional reproductions of classic RL algorithms. Models are designed to be evaluated in standard continuous and discrete state spaces.
- **Value-Based Methods:**
  - [x] DQN (Deep Q-Network)
- **Policy-Based & Actor-Critic Methods:**
  - [x] REINFORCE
  - [x] Actor-Critic (Base Architecture)
  - [x] TRPO (Trust Region Policy Optimization)
  - [x] PPO (Proximal Policy Optimization)
  - [x] DDPG (Deep Deterministic Policy Gradient)
  - [x] SAC (Soft Actor-Critic)

##  Environment & Dependencies

The code has been successfully tested and compiled across dual environments to ensure cross-platform compatibility:

- **macOS:** Apple Silicon M4 (MPS backend enabled)
- **Windows:** NVIDIA RTX 4060 (CUDA 12.8 enabled)

All dependencies installed is listed in the environment.yml file
