# From A2C to SAC: RL Algorithm and Neural Architecture Performance in CarRacing-v2

## 🥇 Motivation
- CarRacing-v2: A challenging RL benchmark for continuous control and high-dimensional image observations.
- Goal: Compare RL algorithms (PPO, SAC, DQN, DDPG, A2C) on exploration, stability, and domain generalization.

## 📢 Contributions
- Quantitative and Qualitative comparison of leading RL algorithms under challenging conditions.
- Discrete action wrapping enables DQN vs actor-critic RL comparison in continuous control.
- Domain Generalization Test: testing in low-light environments after training with original/grayscale images.

## 💡 Methods
### ⭐ MDP and Discrete Action Wrapping
![image](https://github.com/user-attachments/assets/e0b45dcf-eb04-48f0-8d7f-bbdbc3a96383)

- We designed a Discrete Action Wrapper mapping discrete actions to continuous controls, enabling DQN to learn in CarRa:cing-v2.

### 🌙 Domain Generalization Test (Day to Night)
![image](https://github.com/user-attachments/assets/812a2ed6-c170-4cae-bed5-2e9b09cff7f3)

- Training: Trained with Original images/Grayscale images with Resizing
- Night Driving Test Environment: Reduced image brightness and altered track area color palettes to dark blue to decrease color correlations from training.

## 📊 Evaluations
- Exploration performance
  
![image](https://github.com/user-attachments/assets/780135b9-f4b2-4097-8f63-12312701b49b)

- Model Performance Comparison
  
![image](https://github.com/user-attachments/assets/cb8ba30d-1994-4d2a-a8bc-bf0c97d32b5d)

## 🎧 Conclusions
- PPO outperformed other algorithms due to its stable, incremental policy updates and robust learning structure.
- Agents trained with grayscale and resized images showed better adaptation and higher scores in night driving environments.
- These results highlight PPO's effectiveness in domain generalization from day to night conditions.


## 🔍 Project Poster


![image](https://github.com/user-attachments/assets/bf7d9fd1-5028-4db8-8ffe-f8f3ebeb1c53)
