# Reinforcement-Models
The trial model is about a simple game on 6x6 grid. It has a custom environment.In the game the player denoted by number 1 must reach the target 2 while the number 3 acts as a trap reaching which loses the player the game. The reward system has been set up so that the model finds the shortest path using the actions up, down, right and left . I ran into some issues regarding the stablebaselines integration to train the model.

The main model acts on the ready made lunar lander game from the open ai gym. I used a DQNA agent which learns the game based upon the exploitation vs exploration strategy. It stores the results from training and thereby updates the q-learning tables.A neural network with a hidden layer made of 128 neurons was used for the model, with the purpose of optimizing the q learning table. Some issues were faced regarding the shape of action states which were fixed by avoiding usage of map function and instead using individual for loops the process the variables havind different shapes
