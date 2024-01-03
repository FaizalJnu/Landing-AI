# Landing-AI
- Trying to implement an AI to land a rocket in Gymnasium successfully 
- Creating AI brain on principles of Deep Q Learning
- Most important class is the Brain, it constitutes the neural network architecture
- Agent is created which uses the attributes of the brain to perform actions
- A memory class is created in ReplayMemory, it stores all the our previous actions upto a mini batch size before removing it if necessary to make space.
- I've figured out how to work the stepping action, control action and more
- yet to figure how it will act after receiving all the necessary information