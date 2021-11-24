# OESjava
OESjava is the Java implementation of the Object Event Simulation (OES) core simulators OES Core 0-2, developed by Yevhenii Samorodov for his Master thesis [Object Event Simulation of Activity Networks with Java and AnyLogic](https://gwagner57.github.io/oes/Java/Master-Thesis-Yevhenii-Samorodov-2021.pdf).

The minimal version of an OES simulator is *OES Core 0*,
supporting models with (global) model variables and functions, object types, event types, and simple simulation experiments. 

The simulators OES Core 1-2 incrementally extend OES Core 0 by adding further features:

1. OES Core 1 adds a seedable random number generator, a set of sampling functions from various probability distributions 
(uniform, triangular, normal, exponential, etc.), multiple scenarios per model, multiple experiment types per model, model parameters, 
parameter variation experiments, as well as persistent storage and export of experiment results.

2. OES Core 2 adds the concept of *activities*, which are composite events that have some duration and typically depend on resources,
together with the concepts of *resource roles*, *resource constraints* and *resource pools*. For an activity-based simulation model,
the simulator can automatically compute (a) throughput, (b) queue length, (c) cycle time, and (d) resource utilization statistics per activity type.

For more about OES core simulators, see the [project website](https://gwagner57.github.io/oes/).
