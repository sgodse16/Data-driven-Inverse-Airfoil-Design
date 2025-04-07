# Data-driven-Inverse-Airfoil-Design
Final project for 24786 - Bayesian Machine Learning, Spring 2023 by Prof. Venkat Viswanathan.

Generated airfoils using Autoencoders and predicted their lift-drag coefficient ratio using a trained convolutional neural network.
![generated_predictions](https://github.com/sgodse16/Data-driven-Inverse-Airfoil-Design/assets/109099769/62275583-9630-447b-9722-ebb932830c3a)

This creates a differentiable mapping between latent representation of airfoil images and the lift-drag coefficient ratio, which enables an inverse design appraoch. Essentially, we can vary the parameters in the latent representation, to obtain an airfoil design with a desired lift-drag coefficient ratio.
