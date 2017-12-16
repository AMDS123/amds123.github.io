---
layout: post
title: "Depth from Monocular Images using a Semi-Parallel Deep Neural Network Hybrid Architecture"
date: 2017-11-06 11:01:12
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Optimization Detection
author: S. Bazrafkan (1), H. Javidnia (1), J. Lemley (1), P. Corcoran (1) ((1) Department of Electrical & Electronic Engineering, College of Engineering and Informatics, National University of Ireland, Galway)
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Network (CNN) techniques are applied to the problem of determining the depth from a single camera image (monocular depth). Fully connected CNN topologies preserve all details of the input images, enabling the detection of fine details, but miss larger features; networks that employ 2x2, 4x4 and 8x8 max-pooling operators can determine larger features at the expense of finer details. After designing, training and optimising a set of topologies, these networks may be combined into a single network topology using graph optimization techniques. This "Semi Parallel Deep Neural Network (SPDNN)" eliminates duplicate common network layers, reducing network size and computational effort significantly, and can be further optimized by retraining to achieve an improved level of convergence over the individual topologies. In this study, four models are trained and have been evaluated at 2 stages on the KITTI dataset. The ground truth images in the first part of the experiment come from the benchmark, and for the second part, the ground truth images are the depth map results from applying a state-of-the-art stereo matching method. The results of this evaluation demonstrate that using post-processing techniques to refine the target of the network increases the accuracy of depth estimation on individual mono images. The second evaluation shows that using segmentation data as the input can improve the depth estimation results to a point where performance is comparable with stereo depth estimation. The computational time is also discussed in this study.

##### Abstract (translated by Google)
卷积神经网络（CNN）技术被应用于从单个相机图像（单目深度）确定深度的问题。完全连接的CNN拓扑保留了输入图像的所有细节，使得能够检测细节，但错过了更大的特征;使用2x2,4x4和8x8最大池运营商的网络可以确定更大的功能，但需要更多细节。在设计，训练和优化一组拓扑之后，可以使用图优化技术将这些网络组合成单个网络拓扑。这种“半并行深度神经网络（SPDNN）”消除了重复的公共网络层，显着减少了网络规模和计算工作量，并且可以通过重新训练进一步优化，以实现各个拓扑结构的更好的收敛水平。在这项研究中，四个模型被训练，并且已经在KITTI数据集的两个阶段进行了评估。实验的第一部分的地面真实图像来自基准，而第二部分的地面真实图像是应用最新的立体匹配方法的深度图结果。该评估的结果证明使用后处理技术来改善网络的目标增加了单个单色图像的深度估计的准确性。第二个评估显示，使用分割数据作为输入可以将深度估计结果提高到与立体深度估计性能相当的点。计算时间也在这个研究中讨论。

##### URL
[https://arxiv.org/abs/1703.03867](https://arxiv.org/abs/1703.03867)

##### PDF
[https://arxiv.org/pdf/1703.03867](https://arxiv.org/pdf/1703.03867)

