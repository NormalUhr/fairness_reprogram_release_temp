# Fairness Reprogramming (NeurIPS 2022)

Repository with code to reproduce the results for fairness-oriented model reprogramming.

Despite a surge of recent advances in promoting machine Learning (ML) fairness, the existing mainstream approaches mostly require training or finetuning the entire weights of the neural network to meet the fairness criteria. However, this is often infeasible in practice for large-scale trained models due to high computational and storage costs, low data efficiency, and model privacy issues. In this work, we propose a new generic post-training fairness learning paradigm, called fairness reprogramming, which incorporates the model reprogramming technique into fairness promoting strategy. Specifically, fairness reprogramming fixes the model weights, and appends to the input a set of perturbations, called the fairness trigger, which is tuned towards the fairness criteria under a min-max formulation.


