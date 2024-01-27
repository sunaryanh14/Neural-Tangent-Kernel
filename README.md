## <p style="text-align: center;">Neural Tangent Kernel</p> 
### <p style="text-align: center;">How do neural network learn and generalise well?</p> 

<p align="center">
    <img src=".\NTK.png"> 
</p>

**Neural Tangent Kernel (NTK)** is a kernel that describes the training dynamics of a neural network, allowing one to study the learning process and generalisation features of the network.

In this code, we will study **Neural Networks with non-Gaussian Initialisation** through NTK with the following results:

1. **The limiting NTK**, that is the deterministic NTK in the infinite width limit of neural network, **can be derived recursively for non-Gaussian initialisation**.
2. **The limiting NTK does not depend on the choice of weight distributions in the hidden layers**, given the initial distribution for bias parameters in the hidden layers is Gaussian.
3. **The limiting NTK approximates the finite-width neural network**, and as a result, it is possible to approximate the result of a trained neural network with non-Gaussian initialisation.

This respository is the implementation of my master dissertation.
