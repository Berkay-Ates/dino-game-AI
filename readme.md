 **# README.md**

**Chrome Dino AI:** Training an AI Agent to Play the Chrome Dino Game

**This project explores the development of an AI agent capable of playing the Chrome Dino game autonomously using reinforcement learning techniques.**

**Key Steps:**

1. **Install Dependencies:**
   - Ensure you have the necessary libraries for Python, OpenAI Gym, Stable Baselines3, and additional tools like MSS, PyDirectInput, and PyTesseract.

2. **Build the Environment:**
   - Create a custom Gym environment to interface with the Chrome Dino game, enabling the AI agent to interact with it.
   - Define actions (jump, duck, no-op) for the agent to take.
   - Capture game frames and process them into observations for the model.
   - Detect game-over states using OCR.

3. **Train the Model:**
   - Employ a Deep Q-Network (DQN) algorithm from Stable Baselines3 for training the AI agent.
   - Implement a custom callback for saving model checkpoints and logging progress.
   - Initiate model training with defined hyperparameters.

4. **Test the Model:**
   - Load a trained model and evaluate its performance over multiple episodes.
   - Observe the agent's actions and decision-making in real-time.

**Additional Information:**

- **Environment:** The code assumes the Chrome Dino game is running in a specific window location and resolution.
- **Reward Function:** The current reward structure simply grants a point for every frame the agent survives.
- **Hyperparameters:** Experiment with different hyperparameters to potentially improve performance.

**Future Work:**

- **Explore Diverse Actions:** Examine different action combinations or continuous controls.
- **Refine Reward Function:** Design a more sophisticated reward function to guide behavior strategically.
- **Optimize Training:** Adjust hyperparameters and training procedures for enhanced learning efficiency.
- **Transfer Learning:** Investigate the potential of applying the model to similar games or environments.
