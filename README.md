# AdaPool
Code for the KDD 2023 paper "AdaPool: Adaptive Graph Pooling via Reinforced Hybrid Graph
Coarsening Networks".

![](pics/adapool.png)
# Data preparation
The datasets used in this paper are from [TUDatasets](https://chrsmrrs.github.io/datasets/docs/datasets/), can be directly accessed through pytorch geometric.
# Requirements
This code run with Python 3. 
- torch == 1.10.2+cu113
- torch-cluster == 1.5.9
- torch-geometric == 2.0.3
- torch-scatter == 2.0.9
- torch-sparse == 0.6.12
- magic-graph
```
git clone https://github.com/phanein/magic-graph.git
cd magic-graph
python setup.py install
```
# Train
```
git clone git@github.com:ot4f/Adapool
cd Adapool
mkdir data
python main.py --dataset PROTEINS --max_timesteps 20 --epoch_num 50
```