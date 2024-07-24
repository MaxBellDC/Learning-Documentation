# A Survey of Computer Architecture Simulation Techniques and Tools

**Authors:** Ayaz Akram, Lina Sawalha
**URL:** https://ieeexplore.ieee.org/document/8718630

## Summary

This is an article that aims to take an in depth look at six computer architechture simulators: gem5, MARSSx86, Multi2Sim, PTLsim, Sniper, and ZSim. In the article it is mentioned that there is not enough published material that compares and categorizes these simulators, and that is what they hope to accomplish in this publication. Moreover, this article hopes to give a detailed breakdown of the experimental error (defined as: any variance between a measurement taken during an experiment and the established values). Considering the goal of running a computer architecture simulator is to experiment with performance and power consumption of new component ideas, experimental error is a great metric to consider when choosing the simulator that best fits the use case of the experiment. This article goes a step beyond other computer architecture simulator surveys and compares the simulation data to real hardware runs to highlights the innacuracies. 

### Classification of Simulators

The article mentions three classification prinicples that are considered when evaluating the simulators:

1. Detail of simulation
2. Scope of the target
3. Input to the simulator

#### Classifying Simulators Based on the Detail of Simulation

This section highlights that the level of detail in a simulator can be classified into three main categories.

i. Functional Simulators
ii. Timing Simulators
iii. Integrated Timing and Functional Simulators

i. Functional Simulators
- Only represents the architecture and aims to achieve an accurate representation of the modeled architecture
- Behaves like an emulator
- Typically fasted than other types of simulators
- Unable to keep track of detailed microarchitectural parameters
- Useful for testing the purposes of new instruction sets

This image shows a block diagram of a functional simulator
<img src="images/Functional.png">


