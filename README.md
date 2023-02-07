# Adapool
This is the code for paper "AdaPool: Adaptive Graph Pooling via Reinforced Hybrid Graph
Coarsening Networks"
# Data preparation
The datasets used in this paper are from [TUDatasets](https://chrsmrrs.github.io/datasets/docs/datasets/), can be directly accessed through pytorch geometric.
# Requirements
- torch == 1.10.2+cu113
- torch-cluster == 1.5.9
- torch-geometric == 2.0.3
- torch-scatter == 2.0.9
- torch-sparse == 0.6.12
# Train
1. make `data` directory
2. train 
```python
python main.py --dataset PROTEINS --max_timesteps 20 --epoch_num 50
```