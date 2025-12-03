# Response_Solver
---
Python Source Code for the Extraction method for response functions from X-ray light curves of AGN by optimization algorithm

**Prerequisits**
- Matplotlib
- Numpy
- Pandas
- PyTorch
- Scipy
- Scikit-Learn
  
---
Users may change these following variables to make it suits your projects
- Initial Guess
- Signal-to-Noise Ratio
- Lagranage Multiplier (Learning Rate)
- Number of Iteration

Checkpoint file will be written every 100 iterations. At the end of the computation, optimized kernels shall be saves as `.json` format.
