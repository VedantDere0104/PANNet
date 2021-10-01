# Path Aggregation Network for Instance Segmentation :- 

Pytorch implementation of PANNet

## Abstract :- 
The way that information propagates in neural networks
is of great importance. In this paper, we propose Path Aggregation Network (PANet) aiming at boosting information
flow in proposal-based instance segmentation framework.
Specifically, we enhance the entire feature hierarchy with
accurate localization signals in lower layers by bottom-up
path augmentation, which shortens the information path between lower layers and topmost feature. We present adaptive feature pooling, which links feature grid and all feature levels to make useful information in each feature level
propagate directly to following proposal subnetworks. A
complementary branch capturing different views for each
proposal is created to further improve mask prediction.
These improvements are simple to implement, with subtle extra computational overhead. Our PANet reaches the
1
st place in the COCO 2017 Challenge Instance Segmentation task and the 2
nd place in Object Detection task without large-batch training.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/135566175-81809520-6f6c-4ae7-88e5-5486cc1894e0.png)

### Mask Branch :- 
![image](https://user-images.githubusercontent.com/76057253/135566234-4da2fbbf-cc6e-446e-b548-74170919cb2e.png)

## Results :- 


![2021-10-01 (1)](https://user-images.githubusercontent.com/76057253/135566592-b193d2a0-fbb7-420b-8500-e034012f73b4.png)
![2021-10-01](https://user-images.githubusercontent.com/76057253/135566596-f8d87f95-59b5-4657-bf9c-d2f5724cd187.png)

```
@misc{liu2018path,
      title={Path Aggregation Network for Instance Segmentation}, 
      author={Shu Liu and Lu Qi and Haifang Qin and Jianping Shi and Jiaya Jia},
      year={2018},
      eprint={1803.01534},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
