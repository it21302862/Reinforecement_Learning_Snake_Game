# Reinforecement_Learning_Snake_Game
This is a project about reinforcement learning attached to snake game 

# 🐍 Reinforcement Learning Snake Game

This project implements a **Snake Game AI** using **Reinforcement Learning (Q-Learning / Deep Q-Network)** with Python. The agent learns to play the classic snake game by interacting with the environment and improving over time based on rewards and penalties.

## 🚀 Features

- Train an AI agent to play Snake autonomously
- Uses **Reinforcement Learning** concepts (Q-learning or DQN)
- Real-time game visualization with `pygame`
- Logging and plotting of training performance
- Model saving and loading capabilities

## 📸 Demo

![Game 01](https://github.com/it21302862/Reinforecement_Learning_Snake_Game/blob/main/images/snake_game_1.png)  

![Game 58](https://github.com/it21302862/Reinforecement_Learning_Snake_Game/blob/main/images/snake_game_58.png) 
 
![Game 68](https://github.com/it21302862/Reinforecement_Learning_Snake_Game/blob/main/images/snake_game_68.png) 

![Game 71](https://github.com/it21302862/Reinforecement_Learning_Snake_Game/blob/main/images/snake_game_71.png) 

![Game 81](https://github.com/it21302862/Reinforecement_Learning_Snake_Game/blob/main/images/snake_game_81.png) 


---

## 🧠 Technologies & Libraries

- **Python 3.x**
- **Pygame** - for game visualization
- **NumPy** - for data manipulation
- **Matplotlib** - for plotting results
- **PyTorch / TensorFlow** *(if using Deep Q-Learning)*

---

## 📂 Project Structure

einforcement-snake/
│
├── game.py # Snake game logic (state, collisions, etc.)
├── agent.py # RL agent logic (e.g., Q-table or DQN)
├── model.py # Deep learning model (for DQN-based)
├── helper.py # Training loop and logging
├── plot.py # Plotting training results
├── requirements.txt # Required libraries
└── README.md # Project documentation


---

## 🕹️ How It Works

1. The agent observes the game state (e.g., danger directions, food location, current direction).
2. It takes actions (left, right, straight) based on its policy.
3. It receives a **reward**:
   - +10 for eating food
   - -10 for dying
   - -0.1 for each step to encourage efficiency
4. The agent updates its Q-values or neural network.
5. Over episodes, it improves and survives longer.

---

## 📦 Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/it21302862/Reinforecement_Learning_Snake_Game.git
   

Install dependencies:
```
pip install -r requirements.txt
```

Run the project
```
python agent.py
```

