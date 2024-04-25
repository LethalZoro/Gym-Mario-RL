# Gym Mario RL



## Introduction:
The study explores machine learning and deep learning algorithms in game learning. Various neural network architectures are tested, and a comparative analysis is conducted based on task-specific performance metrics. State-of-the-art models are discussed, and their results are analyzed.


### Game Learning:
In the game learning task, agents are trained to play the Super Mario Bros2-v1 game. Two models are explored: Double Deep Q-Network (DDQN) and ResNet50, both fine-tuned for the game environment. Metrics such as average reward, game score, and training time are used for evaluation.

#### The models used for the image-text matching task are:
 1. Double Deep Q-Network (DDQN):
 1. ResNet50:
 1. MobileNet:


### Results and Analysis:
Each model is trained for 50 episodes, and evaluation metrics are compared. The complete analysis is summarized in Table.

### Table: Average Metrics for 50 Episodes
| Model         | Avg. Reward | Avg. Game Score | 
|---------------|-------------|-----------------|
| DDQN          | 3.267       | 164.33          | 
| ResNet50      | 3.162       | 158             | 
| MobileNet     | 0.915       | 45.74           | 

