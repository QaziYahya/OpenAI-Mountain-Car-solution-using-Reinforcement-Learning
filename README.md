# OpenAI-Mountain-Car-solution-using-Reinforcement-Learning
Reinforcement Learning DQN - using OpenAI mountain car environment 

<li>Tensorflow</li>
<li>Keras</li>
<li>gym</li>
</br>

The OpenAI mountain car environment consists of car at the feet of a slope. The goal is to get the car to the flag pole at the top of the slope as fast as possible. The car is controlled using three discrete actions, namely:

<li>0: Accelerate to the left</li>
<li>1: Don’t accelerate</li>
<li>2: Accelerate to the right</li>
</br>

![Screenshot from 2022-09-26 19-53-24](https://user-images.githubusercontent.com/74414105/192309557-e8662326-1da9-4974-b2be-f14f136f18b4.png)

The agent was trained using Deep-Q-Learning. It took a total of 1500 episodes for the model to train. The time taken was about 10 minutes.

# Preview:

https://user-images.githubusercontent.com/74414105/192310225-c278a4ca-0092-4c91-8449-ce11f69456b9.mp4

# Training & Testing
The agent can be trained by running the "train.py" file keep in mind that it takes some time for the agent to train. The model can be tested by running the
"test.py" file it'll create and save a video of the agent playing the game. 
