This repository contains the code associated with the scientific publication:  
**"Neighbor-Aware Informal Settlement Mapping with Graph Convolutional Networks"**  
_Hallopeau et al., 2025_

## 📂 Overview

This repository provides training and inference pipelines for the three models evaluated in the paper:
- **MLP baseline (no neighbor)**
- **MLP baseline (with neighbors)**
- **Graph Convolutional Network (GCN)**

**Data preprocessing and feature engineering** (e.g., vegetation indices, DEM features, road network statistics) are handled in a separate repository:  
[https://github.com/Hallopeau/ensemble-learning-rio](https://github.com/Hallopeau/ensemble-learning-rio)  
Specifically, see the directories:  
- `data/` 
- `1_preprocessing/`  
- `2_feature_engineering/`

**Additional metrics**: Tables showing full evaluation metrics beyond Kappa scores (e.g., Precision, Recall, F1-score) are provided in the supplementary PDF included in this repository.

## 📄 Citation

If you use this code or build upon this work, please cite:

> Hallopeau, T., et al. (2025). _Neighbor-Aware Informal Settlement Mapping with Graph Convolutional Networks_.

BibTeX:
```bibtex
@article{hallopeau2025gcn,
  title={Neighbor-Aware Informal Settlement Mapping with Graph Convolutional Networks},
  author={Hallopeau, Guérin and others},
  year={2025},
  journal={To appear}
}
