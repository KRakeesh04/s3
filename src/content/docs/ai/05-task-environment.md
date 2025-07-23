---
title: Task Environment
sidebar:
  order: 5
---

The problems to which an agent attempts to provide solutions for. Must be specified as fully as possible before implementing an agent.

Consists of PEAS:
- [Performance Measure](/ai/performance-measure)
- Environment
- Actuators
- Sensors

## Properties

### Obervability   

- Fully Observable   
  Agent's sensors give access to the complete state of the environment at each point in time.  
- Partially Observable   
  Agent's sensors give access to a subset of the complete state of the environment at each point in time. Can be caused by noise, uncertainty, or incomplete information.
  
If the sensors detect all the information relevant to the choice of action, the environment is said to be fully observable.

### Single or More 

- Single Agent   
- Multiple Agents   
  One agent's actions will affect the environment, and the other agents' actions will be affected. Can either be cooperative or competitive.
  - Cooperative means that the agents' actions will benefit each other
  - Competitive means that the agents' actions will harm each other
  
### Deterministic or not

- Deterministic   
  The environment's next state is completely determined by the agent's actions and the environment's initial state.
- Non-deterministic   
  The environment's next state is not completely determined by the agent's actions and the environment's initial state.
  - Stochastic   
    The environment's next state is probabilistic, with some randomness introduced by chance events. Subset of non-deterministic.

### Episodic or Sequential

- Episodic   
  Agent's experience is divided into atomic episodes. Once a certain condition is met, the episode ends, and a new one begins. Sensory data is not passed inter-episode. Simple because the agent doesn't think ahead.
- Sequential   
  Current decision could affect all future decisions.

### Dynamic or Static

- Dynamic   
  The environment's state changes while the agent's delibrerating or not. 
- Static   
  The environment's state stays the same.

### Continuous or Discrete

- Continuous   
  When the environment's state, the time, the percepts and the actions are continuous.
- Discrete   
  When the environment's state, the time, the percepts and the actions are discrete.
