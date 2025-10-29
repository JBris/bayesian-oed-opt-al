# bayesian-oed-opt-al

Testing Bayesian optimal experimental design, optimisation, and active learning with different acquisition functions

## Bayesian optimal experimental design

Maximise information gain for parameters/model using Expected Information Gain

Maximise information gain about system under study. Estimate parameters.

Prioritise samples that lead to greatest reduction in Shannon entropy 

Focus is on exploration of search space

## Active learning

Reduce predictive variance. Prioritise observations with greatest predictive variance (widest prediction intervals)

Prioritise samples/observations that lead to greatest reduction in predictive uncertainty. Often for ML uses.

Focus is on exploration of search space

## Bayesian optimisation

Use ExpectedImprovement and UpperConfidenceBound

Optimise parameters with respect to cost function

Focus is on balancing exploration and exploitation of search space. Aim is to efficiently perform optimisation 

