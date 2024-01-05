# Landing-AI
- Trying to implement an AI to land a rocket in Gymnasium successfully 
- Creating AI brain on principles of Deep Q Learning
- Most important class is the Brain, it constitutes the neural network architecture
- Agent is created which uses the attributes of the brain to perform actions
- A memory class is created in ReplayMemory, it stores all the our previous actions upto a mini batch size before removing it if necessary to make space.
- I've figured out how to work the stepping action, control action and more
- yet to figure how it will act after receiving all the necessary information.


- So worked on the act method, by getting argmax of action values against comparison with epsilon value I put in, or returning random out of either of the 4 in action_size.
- Developed the softmax function too, in the end to update our model's parameters at every step.

- Training the DQN agent took a while, I had to first decide through the coursework and experimentation what exaclty to keep my epsilon values.
- Then moved on to the loop part in finally displaying how my Average score improves through my ai's training. 
- I learned how to dynamically print the results as they are being updated through each episode, this was the most intuitive thing in the project so far XD.

- Our final step would be visualizing the result in Gym env to see how our lander performed. too da loo.