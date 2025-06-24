# Car_Racing_RL_Project

## 🥇 The goal of the project
- Compare RL algorithms (PPO, SAC, DQN, DDPG, A2C) on exploration, stability, and domain generalization

## 📢 Contributions
- Quantitative and Qualitative comparison of leading RL algorithms under challenging conditions.
- Discrete action wrapping enables DQN vs actor-critic RL comparison in continuous control.
- Domain Generalization Test: testing in low-light environments after training with original/grayscale images.

## 📢 Methods
### ⭐ MDP and Discrete Action Wrapping
![image](https://github.com/user-attachments/assets/6c378422-cecb-4c2f-8c13-a91272d2a807)

- We designed a Discrete Action Wrapper mapping discrete actions to continuous controls, enabling DQN to learn in CarRa:cing-v2.

### 🌙 Domain Generalization Test (Day to Night)
- Training: Trained with Original images/Grayscale images with Resizing
- Night Driving Test Environment: Reduced image brightness and altered track area color palettes to dark blue to decrease color correlations from training.

## 💡 Evaluations
- Exploraiton performance
  
![image](https://github.com/user-attachments/assets/780135b9-f4b2-4097-8f63-12312701b49b)

- Model Performance Comparison
  
![image](https://github.com/user-attachments/assets/cb8ba30d-1994-4d2a-a8bc-bf0c97d32b5d)


## 🔍 Project Poster


![image](https://github.com/user-attachments/assets/bf7d9fd1-5028-4db8-8ffe-f8f3ebeb1c53)
