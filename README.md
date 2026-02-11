# GNN-fraud-detector
This project aims to build a deployable, graph-based AI system that integrates financial transaction graphs with device and behavioral signals using public, well-documented datasets. 

## Data Setup
Due to size constraints and privacy, the `data/` directory is ignored by Git. 
Please download the datasets manually and place them in the following structure:

- **Elliptic Bitcoin Dataset**: [Download here](https://www.kaggle.com/datasets/ellipticco/elliptic-data-set)
  - Place in `data/elliptic_bitcoin_dataset/`
- **LANL Auth Logs**: [Download here](https://csr.lanl.gov/data/cyber1/)
  - Place in `data/cyber_dataset/`
- **Keystroke Dynamics**: [Download here](https://www.cs.cmu.edu/~keystroke/)
  - Place in `data/keystroke_dynamics_dataset/`