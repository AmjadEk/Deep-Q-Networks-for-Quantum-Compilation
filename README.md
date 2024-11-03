# Quantum Gate Compilation with Deep Q Networks

Quantum computers are only able to physically generate a specific number of quantum gates (unitary matrices). They rely on this set of quantum gates to compile/generate all possible quantum gates : therefore, finding an efficient way to approximate unitary matrices is a fundamental problem of quantum compilation. This project explores the use of **Deep Q Networks (DQN)** for the compilation of quantum gates using a discrete set of gates. Although the project is still in progress, the following key components have been successfully implemented:

## Accomplished
- **Gym Environment**: Developed a custom Gym environment to simulate the quantum gate compilation process.
- **Replay Memory**: Built a replay memory system for the training of the DQN agent.
- **Feedforward Neural Network Architecture**: Implemented a feedforward neural network to serve as the function approximator for the DQN.

## Future Work
Planned tasks to complete the project include:
- Implementing the DQN algorithm for training the agent.
- Evaluating the performance of the agent in compiling quantum gates.
