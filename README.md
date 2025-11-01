This repository contains the code associated with the scientific publication:  
**"Neighbor-Aware Informal Settlement Mapping with Graph Convolutional Networks"**  

## 📂 Overview

This repository provides training and inference pipelines for the three models evaluated in the paper:
- **MLP baseline (no neighbor)**
- **MLP baseline (with neighbors)**
- **Graph Convolutional Network (GCN)**

**Data preprocessing and feature engineering** are handled in a separate repository:  
[https://github.com/thallop/balise-rio](https://github.com/thallop/balise-rio)  

**Additional metrics**: Tables showing full evaluation metrics beyond Kappa scores (e.g., Precision, Recall, F1-score) are provided in the supplementary PDF included in this repository.

## 📄 Citation

If you use this code or build upon this work, please cite:

```bibtex
@inproceedings{hallopeau2025gcn,
  title     = {Neighbor-Aware Informal Settlement Mapping with Graph Convolutional Networks},
  author    = {Hallopeau, Thomas and Gu{\'e}rin, Joris and Demagistri, Laurent and Barcellos, Christovam and Dessay, Nadine},
  booktitle = {Proceedings of the ECML PKDD 2025 Workshop on Machine Learning for Earth Observation},
  year      = {2025},
  address   = {Porto, Portugal},
  doi       = {10.48550/arXiv.2509.26171},
  url       = {https://arxiv.org/abs/2509.26171},
  note      = {arXiv:2509.26171 [cs.LG]}
}
