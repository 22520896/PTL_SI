# PTL-SI: Post-Transfer Learning Statistical Inference in High-Dimensional Regression
**PTL-SI** is a Python package designed for conducting valid statistical inference in high-dimensional regression (HDR) settings with transfer learning (TL). It implements selective inference methods to control the false positive rate (FPR) while maximizing the true positive rate (TPR) in feature selection after transfer learning.


## Requirements & Installation
This package has the following requirements:
- **[numpy](https://numpy.org/doc/stable/)**
- **[mpmath](https://mpmath.org/)** 
- **[skglm](https://contrib.scikit-learn.org/skglm/)**
- **[scipy](https://docs.scipy.org/doc/)** 
- **[matplotlib](https://matplotlib.org/)** 
- **[statsmodels](https://www.statsmodels.org/stable/index.html)**


This package can be installed using pip:
```bash
pip install ptl_si
```

We recommend to install or update anaconda to the latest version and use Python 3 (We used Python 3.11.4).

## Example Notebooks
We provide several Jupyter notebooks demonstrating how to use the `ptl_si` package in our `examples/` directory:

  - `ex1_p_value_TF.ipynb` - Example for computing p-value for TransFusion
  - `ex2_p_value_OTL.ipynb` -  Example for computing p-value for Oracle Trans-Lasso
  - `ex3_pivot.ipynb` - Check the uniformity of the pivot


## Citation
If you use this package or the methodology in your research, please cite our paper: Tam, N.V.K., My, C.H. & Le Duy, V.N. Post-transfer learning statistical inference in high-dimensional regression. Stat Comput 35, 205 (2025). https://doi.org/10.1007/s11222-025-10738-z



```
@article{tam2025post,
  title     = {Post-transfer learning statistical inference in high-dimensional regression},
  author    = {Tam, Nguyen Vu Khai and My, Cao Huyen and Duy, Vo Nguyen Le},
  journal   = {Statistics and Computing},
  volume    = {35},
  pages     = {205},
  year      = {2025},
  publisher = {Springer},
  doi       = {10.1007/s11222-025-10738-z}
}
```