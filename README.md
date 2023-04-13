# Model Ensemble Mirror Descent Policy Optimization (ME-MDPO)

- **Current Literature**[^1]
  - So far MD-style algorithms have been of model-free learning type
- **Novelty**
  - We propose to learn model-ensemble to generate dynamics rollout, which will be then used to update the policy parameters with MDPO
- **Motivation**[^2]
  - Model-free methods tend to suffer from high sample complexity which hinders their use in real-world domains
  - Model-based methods reduce sample complexity, but tends to require careful tuning


[^1]: Tomar, M. et al. Mirror Descent Policy Optimization.
[^2]: Kurutach, T. et al. Model-Ensemble Trust Region Policy Optimization.

## Tasks

- [x] Reproduce Mirror Descent Policy Optimization (MDPO) results (On Policy Case)
- [ ] Reproduce Model Ensemble Trust Region Policy Optimization (ME-TRPO) results
- [ ] Implement ME-MDPO
