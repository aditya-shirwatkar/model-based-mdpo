# Model Ensemble Mirror Descent Policy Optimization (ME-MDPO)

- **Current Literature**[^1]
  - So far MD-style algorithms have been of model-free learning type
- **Novelty**
  - We propose to learn ensemble of system dynamics, which will be then used to generate rollouts and update the policy parameters with MDPO
- **Motivation**[^2]
  - Model-free methods tend to suffer from high sample complexity, and Model-based methods reduce sample complexity, but tend to require careful tuning
  - An ensemble of models maintains the model uncertainty and regularizes the learning process


[^1]: Tomar, M. et al. Mirror Descent Policy Optimization.
[^2]: Kurutach, T. et al. Model-Ensemble Trust Region Policy Optimization.

## Tasks

- [x] Reproduce Mirror Descent Policy Optimization (MDPO) results (On Policy Case)
- [ ] Reproduce Model Ensemble Trust Region Policy Optimization (ME-TRPO) results
- [ ] Implement ME-MDPO
