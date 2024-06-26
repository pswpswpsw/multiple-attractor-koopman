# Data-Efficient Approach in Learning Koopman Operator for Nonlinear Systems with Multiple Invariant Sets
This repo contains code for https://arxiv.org/abs/2304.11860

The idea is simple: you can leverage symmetry in your system for a better learning outcome for Koopman operator. 

# Instructions

1. `conda create -n pykoopman python=3.10`
2. `conda activate pykoopman`
3. `python -m pip install -r requirements.txt`
4. `jupyter notebook example.ipynb`

Run the [notebook](https://github.com/pswpswpsw/multiple-attractor-koopman/blob/main/example.ipynb) then you will see all the figures reproduced in the paper. 

# How to cite

If you find this idea is helpful to your research, you can cite our paper in following bibtex format

   ```
@article{pan2023lifting,
  title={On the lifting and reconstruction of dynamical systems with multiple attractors},
  author={Pan, Shaowu and Duraisamy, Karthik},
  journal={arXiv preprint arXiv:2304.11860},
  year={2023}
}
   ```


