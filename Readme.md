```
date: 2019-08-26 09:44:22
tags: 
- CNN 
- CNN3D
- DNN
- Video Representation
- Action Recognition
- Video Classification
- Spatiotemporal 
```

##  3D-CNN Method

|                      |        |           |
| -------------------- | ------ | --------- |
| iDT                  |        |           |
| LRCN                 |        | CVPR 2015 |
| LSTM composite model |        |           |
| C3D                  |        | 2015      |
| TSN                  |        | ECCV 2016 |
| R3DCNN               | NVIDIA | 2016      |
| P3D                  | MSRA   | ICCV 2017 |
| R3D/2.5D             |        | 2017      |
| T3D                  |        | 2017      |
| R2+1D                |        | 2018      |



<!-- more -->

--

----

General LIb:

[ video model zoo (caffe2) ] https://github.com/facebookresearch/VMZ

Currently, this codebase supports the following models:

- R(2+1)D, MCx models [[1\]](https://research.fb.com/wp-content/uploads/2018/04/a-closer-look-at-spatiotemporal-convolutions-for-action-recognition.pdf).
- CSN models [[2\]](https://arxiv.org/pdf/1904.02811.pdf).
- R(2+1)D and CSN models pre-trained on large-scale (65 million!) weakly-supervised public Instagram videos (**IG-65M**) [[3\]](https://research.fb.com/wp-content/uploads/2019/05/Large-scale-weakly-supervised-pre-training-for-video-action-recognition.pdf).

### C3D

[github caffe ]https://github.com/facebook/C3D

[ github tensorflow ]https://github.com/hx173149/C3D-tensorflow

[github pytorch] https://github.com/jfzhang95/pytorch-video-recognition

3x3x3  Kernel

![img](CV_3D/v2-e51c8770654a1eb92f984e8cc2cf0cd8_hd.jpg)

![img](CV_3D/v2-5eda0b0b2967fba1d8b6f31f04ef9d49_hd.jpg)

### P3D

[ caffe ] https://github.com/ZhaofanQiu/pseudo-3d-residual-networks

[ pytorch ] https://github.com/jfzhang95/pytorch-video-recognition

Learning spatio-temporal representation with pseudo-3d residual networks. In ICCV, 2017.

![1567834917557](CV_3D/1567834917557.png)

![1567834970578](CV_3D/1567834970578.png)



### T3D*

Architecture: DenseNet + 3D

[ github pytorch] https://github.com/MohsenFayyaz89/T3D

![img](CV_3D/v2-b1d256a551911be85f445b16bdca5b5c_hd.jpg)

![img](CV_3D/v2-d24ee52c0f5ddc3bdf5614c52841692f_hd.jpg)

### Res3D/R3D

architecture:	ResNet + 3DConv

[github pytorch] https://github.com/jfzhang95/pytorch-video-recognition



![img](CV_3D/v2-e2dd2daf56bfc15d1b24fd0456258c3a_hd.jpg)

![img](CV_3D/v2-e0c6cb5e2b7022930f736d4d63a272a7_hd.jpg)

#### R2.5D

![1567836996218](CV_3D/1567836996218.png)

### R2+1D 

[ offical video model zoo (caffe2) ] https://github.com/facebookresearch/VMZ

[ github PyTorch] https://github.com/leftthomas/R2Plus1D-C3D

![Figure 2](CV_3D/closer_fig2-1567133357920.png)

### R3DCNN

[NVIDIA]https://research.nvidia.com/sites/default/files/publications/NVIDIA_R3DCNN_cvpr2016.pdf

[tensorflow ]https://github.com/breadbread1984/R3DCNN

[tensorflow ] https://github.com/kilsenp/R3DCNN-tensorflow

architecture: C3D + RNN



### TSN

[github caffe ] https://github.com/yjxiong/temporal-segment-networks

[ caffe opensource ] https://github.com/yjxiong/caffe

[Paper] https://arxiv.org/pdf/1608.00859.pdf

![1568038064174](CV_3D/1568038064174.png)



### I3D

Architecture: Inception base

[git keras ] https://github.com/OanaIgnat/i3d_keras

[Paper ] https://arxiv.org/pdf/1705.07750.pdf

![1568037268584](CV_3D/1568037268584.png)

![1568037351528](CV_3D/1568037351528.png)

