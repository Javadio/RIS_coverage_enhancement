# RIS coverage enhancement Using Differentiable Ray Tracing 
--------------------------------------------------------------------------------
This repository contains code to reproduce some of the results from the paper [Physically Consistent RIS: From Reradiation Mode Optimization to Practical Realization](<https://arxiv.org/abs/2409.17738>) Using a [Sionna Link-level Simuator](<https://nvlabs.github.io/sionna/>).

# Abstract
-------------------------------------------------------------------------------------
Reconfigurable Intelligent Surfaces (RIS) are pivotal in next-generation wireless networks, providing a virtual line-of-sight connection between transmitters and users. In this repository, we demonstrate how RIS, integrated into the Sionna Ray Tracer, can be used to manipulate coverage maps in specific areas.
Our approach involves optimizing the amplitude of RIS reradiation modes using a gradient-based learning technique. This optimization is applied to a section of Cape Town, addressing three distinct coverage enhancement scenarios.
However, the generated $\Gamma$ in Sionna does not directly correspond to the practical realization of RIS. In our paper, we propose a practical optimization framework based on a surface impedance model, bridging this gap for real-world implementation.

Running this code requires Sionna 0.16 or later. To run the notebooks on your machine, you also need Jupyter.

# Files
-------------------------------------------------------------------------------------
Cape town_coverage_learning.ipynb demonstrates how the amplitude of the RIS reradiation modes in a scene can be learned by gradient descent. You need to download the cape town xml file to import the scene.  

# References
-------------------------------------------------------------------------------------
[A] [Shabanpour, J., Simovski, C., & Geraci, G. (2024). Physically Consistent RIS: From Reradiation Mode Optimization to Practical Realization. arXiv preprint arXiv:2409.17738](<https://arxiv.org/abs/2409.17738>).


