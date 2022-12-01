# ModelCompression: Pruning

## Overview
Implementation of [Learning both Weights and Connections for Efficient Neural Networks](https://arxiv.org/abs/1506.02626) by Han S., Pool J., et al.

Pruning is a Model Compression Technique which allows the user to compress the model to a smaller size while maintaining marginal loss in accuracy. Pruning also allows the model to be optimized for real time inference for resource-constrained devices.

For more information on Model Compression and Pruning, please read [Model Compression via Pruning](https://towardsdatascience.com/model-compression-via-pruning-ac9b730a7c7b)

## Concepts Utilised
* **Magnitude Based Pruning**

## Explanation
This implementation utilizes a **dataset which is not available for public usage**. But this implementation can be utilized on other datasets. 

[Code](https://github.com/parthmalpathak/Model_Compression_Pruning/blob/main/Magnitude%20Pruning.ipynb) has two different implementations:
* Retrain Attempt:
Inducing sparsity every iteration while retraining.

* Baseline Attempt:
Inducing sparsity by making the weight values beyond a certain threshold equal to 0.0.
