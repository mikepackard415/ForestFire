# Forest Fire Model
This repository contains an implementation of the Forest Fire Agent-Based Model using the Python package Mesa. The concept of the Forest Fire Model relates to dynamical systems and self-organized criticality (see: [Wikipedia](https://en.wikipedia.org/wiki/Forest-fire_model)). The agent-based model was originally written by Uri Wilenski and can be found in the NetLogo Models Library. I wrote this implementation as a practice exercise to help me learn Mesa. 

I wrote two different model implementations. The first represents each tree as an agent. The second limits agents to only those trees that have been or are burning. This second implementation improved the efficiency of the code significantly, and is more closely aligned with the NetLogo implementation.

The jupyter notebook contains plots that show the phase transition as forest density increases, as well as a simple animation of the model.

### References:
Wilensky, U. (1997). NetLogo Fire model. http://ccl.northwestern.edu/netlogo/models/Fire. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.

Wilensky, U. (1999). NetLogo. http://ccl.northwestern.edu/netlogo/. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.