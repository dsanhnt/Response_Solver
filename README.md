# Response_Solver
---
Python Source Code for the article ***Extraction method for response functions from X-ray light curves of AGN by optimization algorithm*** (Accepted by ApJ, Preprint available)
Preprint : [arXiv:2604.04014](https://arxiv.org/abs/2604.04014)

**Prerequisits**
- Matplotlib
- Numpy
- Pandas
- PyTorch
- Scipy
- Scikit-Learn
- Time Series filter code (https://github.com/statefb/ts-spatial-filter)  
---
Users may change these following variables to make it suits your projects
- Initial Guess
- Signal-to-Noise Ratio
- Lagranage Multiplier (Learning Rate)
- Number of Iteration

Checkpoint file will be written every 100 iterations. At the end of the computation, optimized kernels shall be saves as `.json` format.

---
BibTeX of Preprint : 
```
@misc{deesamutara2026,
      title={Extraction method for response functions from X-ray light curves of AGN by optimization algorithm}, 
      author={Sanhanat Deesamutara and Tirawut Worrakitpoonpon and Poemwai Chainakun and Wasutep Luangtip and Jiachen Jiang and Francisco Pozo Nuñez and Andrew J. Young},
      year={2026},
      eprint={2604.04014},
      archivePrefix={arXiv},
      primaryClass={astro-ph.HE},
      url={https://arxiv.org/abs/2604.04014}, 
}
```
