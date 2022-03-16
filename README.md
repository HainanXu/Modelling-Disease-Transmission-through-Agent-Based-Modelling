# Modelling Disease Transmission through Agent-Based Modelling 

Modeled the infection process of contagious disease based on Markov chain.

Two parts:  
1.Transition Matrix part  
Generated 3000 agents with different health habits using normal distribution (a better distribution can be considered).
Since each on of them have different health habits, each agent have different risk of being infected/recovered/dead.
Each agents has four possible states as time goes: Suspected-Infected-Recovered-Dead  

2.Random walk( intervention included)    
Each agent do random walk with in the cube( can be considered as a enclosure space)
Each agent interact with each other. A infected agent may infect a susceptible agent within the infectious its radius.

3.Govornment intervention
Here the govornment intervention indicates a propaganda may raise the awareness of the public, so people may begin to wear a change health habbit/wear masks/star social distancing.
The starting timepoint of govornment intervention can be modified as we want.
