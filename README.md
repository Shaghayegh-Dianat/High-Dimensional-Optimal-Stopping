
# Deep Learning for High-Dimensional Optimal Stopping Problems

## Overview

This repository contains the implementation and numerical investigation of two deep learning approaches for solving high-dimensional optimal stopping problems. The project is based on the research of Becker, Cheridito, and Jentzen (2019, 2021) and was developed as part of a Master's thesis in Applied Mathematics at Sharif University of Technology.

The main objective is to investigate the application of deep neural networks to Bermudan option pricing problems, particularly in high-dimensional settings where conventional numerical methods may face significant computational challenges.

## Methods

### 1. Deep Optimal Stopping (2019)

Based on:

Becker, S., Cheridito, P., & Jentzen, A. (2019). *Deep Optimal Stopping*.

This approach uses a recursive learning procedure in which neural networks are trained backward in time to approximate optimal stopping decisions at successive exercise dates.

Implementation: `Deep_Optimal_Stopping_2019/`

### 2. High-Dimensional Optimal Stopping (2021)

Based on:

Becker, S., Cheridito, P., & Jentzen, A. (2021). *Solving High-Dimensional Optimal Stopping Problems Using Deep Learning*.

This approach employs a global learning framework to approximate randomized stopping strategies over the entire time horizon.

Implementation: `High_Dimensional_Optimal_Stopping_2021/`

## Numerical Experiments

The numerical experiments focus on Bermudan max-call option pricing under a multidimensional Black–Scholes model.

The implementations are investigated through Monte Carlo simulation and neural network training. The experimental study examines the performance of the two approaches under different problem dimensions and model configurations.

## Performance Comparison

The two methods are compared in terms of:

- Estimated option prices and numerical accuracy.
- Computational runtime.
- Memory requirements.
- Numerical stability.
- Scalability with increasing problem dimension.

The purpose of this comparison is to investigate the computational characteristics, advantages, and limitations of the recursive and global learning approaches.



## Technologies

- Python
- NumPy
- TensorFlow
- Monte Carlo Simulation
- Deep Neural Networks

## References

- Becker, S., Cheridito, P., & Jentzen, A. (2019). Deep Optimal Stopping.
- Becker, S., Cheridito, P., & Jentzen, A. (2021). Solving High-Dimensional Optimal Stopping Problems Using Deep Learning.

