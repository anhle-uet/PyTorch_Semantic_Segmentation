# PyTorch_Semantic_Segmentation

Implement some models of semantic segmentation in PyTorch, easy to run.

## Introduction

1. This repo includes some networks for **Semantic Segmentation** implemented in **pytorch 0.4.0** and **python3**. See each directory for more information.
2. I **only provide architecture of network** here. Dataset and train/test files aren't available here, for I think  it can be added according to individual needs.
3. The code file containing the network structure can be **run directly** with the set simulation data.
4. ResNet101 used in this repo is the one which **PSPNet** used. The difference between this resnet and the original resnet is that the first 7*7 conv layer in the old version is replaced by three small-kernel convs. Pretrained model can be downloaded from [here](https://drive.google.com/file/d/1bUzCKazlh8ElGVYWlABBAb0b0uIqFgtR/view).



## Has finished

### FCN8s

<img src='FCN_PyTorch/net.png' width='450'>

### RefineNet

<img src='RefineNet_PyTorch/net.png' width='450'>

### RDFNet

<img src='RDFNet_PyTorch/net.png' width='450'>

### DeepLab V3

<img src='DeepLabV3_PyTorch/net.png' width='600'>

### DeepLab V3+

<img src='DeepLabV3plus_PyTorch/net.png' width='400'>

### PointNet (CVPR 2017)

<img src='PointNet_PyTorch/net.png'>

### 3DGNN (ICCV 2017)

<img src='3DGNN_PyTorch/net.png' width='660'>