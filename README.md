## CartPole Deep Q-Network Agent

👋 Welcome to this fun project where I trained a Deep Q-Network (DQN) agent for the OpenAI Gym's CartPole environment.

### Introduction

In this project, I implemented a DQN agent to play the CartPole game. The CartPole environment is a classic reinforcement learning problem where the goal is to balance a pole on a moving cart. You control the cart by applying a force to the left or right, and the objective is to keep the pole from falling over.

Here are the rules of the game:
- You can move the cart by pushing it to the right (+1 force) or to the left (-1 force).
- The pole starts standing straight up.
- You earn a point for each moment the pole stays up.
- The game ends if the pole tilts too much (over 15 degrees) or if the cart moves too far from the middle of the track (more than 2.4 units).

### Project Details

- I trained a Deep Q-Network to learn how to balance the pole on the cart.
- The model took some time to train, but eventually, it started to perform well.

### How to Use

You can check out the Jupyter notebook containing the code and run it yourself. Just click on the link below:

[CartPole DQN Notebook](https://colab.research.google.com/drive/1Id8n02McK-8Ret_esLEkwxwhDim_iZyh?usp=sharing)

[Fully capable trained model](https://drive.google.com/drive/folders/1-o2B_jTodd3xC3yU69nKe2tYsWkQeh8A?usp=sharing)

### Demo

Here's a glimpse of how the trained agent plays the game:

![Demo Video](#https://drive.google.com/file/d/1H5Pr2FOHChS3D_2Tif8dKWRR7yZWwWDC/view?usp=sharing) 

Feel free to explore the code, experiment with different hyperparameters, or adapt the DQN agent for other reinforcement learning tasks. Happy coding and have fun with CartPole! 😄🕹️