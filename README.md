# Udacity - Deep Reinforcement Learning Nanodegree

Hi all,  

I am pleased to share my work from the **Udacity Deep Reinforcement Learning Nanodegree**.

Throughout this programme, I designed, implemented, and evaluated several reinforcement learning agents across **three** progressively more complex settings: 
- **single-agent discrete control**, 
- **multi-agent continuous control** with distributed training, 
- and **cooperative multi-agent learning** using **centralised training with decentralised execution** in the **Unity ML-Agents** environment. 

These projects together demonstrate the progression from **value-based methods** to advanced **policy-gradient** and **multi-agent** learning systems, with a strong emphasis on training stability, evaluation rigour, and reproducibility.

All projects are briefly summarised below.



The Deep Reinforcement Learning's certificate can be found [here](udacity_drl_cerificate.pdf).


---

## 🧠 Nanodegree Projects

_Click the links below to explore each project in detail._

### 1. **Navigation — Banana Collector (Double DQN)**

In this project, I solved the Unity **Banana Collector** environment using a **Double Deep Q-Network**.  
The agent learns to collect yellow bananas while avoiding blue bananas in a discrete action space.  
The learning process uses experience replay, target networks, ε-greedy exploration, Huber loss, and gradient clipping for stability.  
The environment was solved in **785 episodes**, exceeding Udacity’s performance benchmark. :contentReference[oaicite:3]{index=3}

---

### 2. **Continuous Control — Reacher (DDPG, 20 Agents)**

This project addresses the Unity **Reacher** environment with **20 parallel agents** using **Deep Deterministic Policy Gradient (DDPG)**.  
All agents share a common actor and critic and contribute experience to a shared replay buffer, forming a distributed training setup.  
The task was solved in **100 episodes**, well below the required 163 episodes, with highly stable performance and strong final evaluation. :contentReference[oaicite:4]{index=4}

---

### 3. **Multi-Agent Collaboration — Tennis (MADDPG)**

In this project, I implemented a **Multi-Agent DDPG (MADDPG)** solution for the Unity **Tennis** environment.  
The two agents learn cooperatively using **centralised training with decentralised execution**, a shared actor, and a central critic.  
A shaped **team reward** was introduced to encourage cooperation, while evaluation and early stopping remained based on the raw environment rewards.  
The environment was solved in **1136 episodes**, significantly outperforming Udacity’s reference solution. :contentReference[oaicite:5]{index=5}

---


