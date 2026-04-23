# Graph Transformer for Collide2v

This repository is based on the original repository for processing Collide2v Dataset (https://github.com/pploner/foundation_model_testing). 
Here we investigate some variations of the classification problem: 
- We add MoE to the original transformer 
- We implement a graph version of the dataset together with a gaph transformer econder and MoE
- We test on both version the classification accuracy (compared with MoE and not MoE integrated) 
- In addition we also study the calibration of both approaches following standard calibration metrics
- (optional) Based on the results we introduce calibration techniques 
