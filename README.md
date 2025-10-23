# CCRNFLRL_FINALPROJECT
This repository contains the implementation of a reinforcement learning project for COM221 class. The project aims to develop a model that trains an agent in a Flappy Bird environment.
paper: https://docs.google.com/document/d/1WXXv8CaucmfGqLvCreipgK94XnGlyUJc9kIKjVxv79U/edit?tab=t.0
# 🐦 Flappy Bird - Dueling Double DQN (State-Based)

A reinforcement learning project that trains an AI agent to play **Flappy Bird** using a **Dueling Double Deep Q-Network (DQN)** architecture.  
Built with **PyTorch**, **Gymnasium**, and **FlappyBird-gym**.  
This implementation focuses on **state-based observation**, **reward shaping**, and **stable training** - with built-in **video recording** of the trained agent.

---

## 🚀 Features

- ✅ **Dueling DQN + Double DQN** for more stable and efficient learning  
- 🧠 **State-based representation**
- 🎥 **Automatic gameplay recording** (top 10 episodes merged into a single video)  
- 💾 **Replay buffer** experience sampling  
- 📉 **Epsilon-greedy exploration with decay**  
- ⚙️ **Target network updates** for stability  
- 🧩 **Reward shaping** using survival and progress bonuses  
- 🔥 **GPU acceleration** (CUDA supported)

---

## 📦 Requirements

Make sure you have a working **Anaconda** or **Python (3.8–3.11)** environment.

Install dependencies:

```bash
pip install torch torchvision torchaudio
pip install gymnasium
pip install flappy-bird-gymnasium
pip install opencv-python
pip install imageio
pip install matplotlib

```
---
# 🎮 DEMO
<p align="center">
  <img src="https://github.com/teejx/Flappy-Bird/blob/main/asset/flappy-bird-demo.gif" alt="Flappy Bird AI Demo" width="400">
</p>
