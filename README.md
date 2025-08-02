# 🤖 BipedalWalker-v3 Reinforcement Learning Agent

This project demonstrates how to train an AI agent to walk using Reinforcement Learning on the [BipedalWalker-v3](https://www.gymlibrary.dev/environments/box2d/bipedal_walker/) environment from OpenAI Gymnasium.

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzg4YjMyZDIxZTQzM2VhZTY0MjllMzI1YTAyNzZiMTMxNjI3N2QzNCZjdD1n/6uMqzK2gkLmC4/giphy.gif" alt="Bipedal Walker" width="500"/>
</p>

## 🚀 Project Overview

In this notebook-based project, we trained a reinforcement learning agent using the **Proximal Policy Optimization (PPO)** algorithm from `Stable-Baselines3` to solve the BipedalWalker-v3 environment. The goal is for the agent to learn how to walk on two legs through trial and error.

## 📦 Tools & Libraries

- 🧠 `Stable-Baselines3`
- 🎮 `Gymnasium` (for environment)
- 📊 `Matplotlib` (for reward tracking)
- 🎥 `MoviePy` + `Matplotlib` (for rendering agent videos)
- 🐍 Python 3.10+

## 📈 Training Summary

- **Environment**: BipedalWalker-v3
- **Algorithm**: PPO (Proximal Policy Optimization)
- **Timesteps**: 500,000+
- **Observation space**: 24-dimensional
- **Action space**: 4-dimensional continuous

The trained agent successfully learns to walk on uneven terrain.

## 🧠 How It Works

- The agent interacts with the environment by taking actions and observing rewards.
- PPO updates the policy network to maximize long-term rewards.
- After training, we evaluate and record the agent walking.

## 🖥️ Usage

### ✅ Installation
Install required packages (preferably in Colab or a virtual environment):

```bash
pip install gymnasium[box2d]
pip install stable-baselines3
pip install moviepy
