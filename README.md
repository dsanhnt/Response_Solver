# Response_Solver
---
Python Source Code for the article ***Extraction method for response functions from X-ray light curves of AGN by optimization algorithm*** (Deesamutara et al. 2026)
Article: [DOI 10.3847/1538-4357/ae5b9d](https://iopscience.iop.org/article/10.3847/1538-4357/ae5b9d)
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
BibTeX of Article : 
```
@article{Deesamutara_2026,
      doi = {10.3847/1538-4357/ae5b9d},
      url = {https://doi.org/10.3847/1538-4357/ae5b9d},
      year = {2026},
      month = {apr},
      publisher = {The American Astronomical Society},
      volume = {1002},
      number = {2},
      pages = {118},
      author = {Deesamutara, Sanhanat and Worrakitpoonpon, Tirawut and Chainakun, Poemwai and Luangtip, Wasutep and Jiang, Jiachen and Pozo Nuñez, Francisco and Young, Andrew J.},
      title = {Extraction Method for Response Functions from X-Ray Light Curves of Active Galactic Nuclei by an Optimization Algorithm},
      journal = {The Astrophysical Journal},
}

```
