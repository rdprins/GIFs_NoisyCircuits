# GIFs_NoisyCircuits
Animated versions of some figures in the paper
"A Quadratic Speedup in the Optimization of Noisy Quantum Optical Circuits".<br />
DOI: https://doi.org/10.22331/q-2023-08-29-1097.
Published in Quantum under CC-BY 4.0.

The paper shows a novel approach to simulating quantum optical circuits that contain photon-number-resolving detectors. Traditionally, including real-world factors like loss and noise would slow down such calculations quadratically. This paper shows how to evade that hurdle! Moreover, our techniques allow us to calculate gradients, opening the door to faster circuit optimization. This means we can simulate and optimize realistic circuits with the same effort as ideal ones.

## Contents:
- **Figure 3:** State vector simulations
  - [fig3a_stateVector_1mode.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig3a_stateVector_1mode.gif):
    1-mode circuit
  - [fig3b_stateVector_2modes.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig3b_stateVector_2modes.gif):
    2-mode circuit

- **Figure 5:** Density matrix simulations of a 1-mode GBS circuit
  - [fig5a_densityMatrix_GBS_1mode_withoutDisplacement.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig5a_densityMatrix_GBS_1mode_withoutDisplacement.gif):
    circuit without displacement gates
  - [fig5b_densityMatrix_GBS_1mode_withDisplacement.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig5b_densityMatrix_GBS_1mode_withDisplacement.gif):
    circuit with displacement gates
  - [fig5b_densityMatrix_GBS_1mode_withDisplacement_bufferStrategy.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig5b_densityMatrix_GBS_1mode_withDisplacement_bufferStrategy.gif):
    circuit with displacement gates, with buffer strategy [^1]

- **Figure 7:** Density matrix simulations of a 2-mode GBS circuit
  - [fig7_densityMatrix_GBS_2modes.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig7_densityMatrix_GBS_2modes.gif)
  - [fig7_densityMatrix_GBS_2modes_bufferStrategy.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig7_densityMatrix_GBS_2modes_bufferStrategy.gif):
    with buffer strategy [^1]

- **Figure 9:** Density matrix simulation of a 2-mode circuit for conditional state generation
  - [fig9_densityMatrix_stateGeneration_2modes.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig9_densityMatrix_stateGeneration_2modes.gif):
    
- **Figure 11:** Density matrix simulations of a 3-mode GBS circuit
  - [fig11_densityMatrix_GBS_3modes.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig11_densityMatrix_GBS_3modes.gif)
  - [fig11_densityMatrix_GBS_3modes_bufferStrategy.gif](https://github.com/rdprins/GIFs_NoisyCircuits/blob/main/fig11_densityMatrix_GBS_3modes_bufferStrategy.gif):
    with buffer strategy [^1]

[^1]: The buffer strategy is intriduced in section 3.1.4 of the manuscript. When applying this strategy, the off-diagonal amplitudes are removed from memory once they have been used.
