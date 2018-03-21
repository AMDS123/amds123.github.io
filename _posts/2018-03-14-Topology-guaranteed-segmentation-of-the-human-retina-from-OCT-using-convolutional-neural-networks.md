---
layout: post
title: "Topology guaranteed segmentation of the human retina from OCT using convolutional neural networks"
date: 2018-03-14 03:21:01
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Yufan He, Aaron Carass, Bruno M. Jedynak, Sharon D. Solomon, Shiv Saidha, Peter A. Calabresi, Jerry L. Prince
mathjax: true
---

* content
{:toc}

##### Abstract
Optical coherence tomography (OCT) is a noninvasive imaging modality which can be used to obtain depth images of the retina. The changing layer thicknesses can thus be quantified by analyzing these OCT images, moreover these changes have been shown to correlate with disease progression in multiple sclerosis. Recent automated retinal layer segmentation tools use machine learning methods to perform pixel-wise labeling and graph methods to guarantee the layer hierarchy or topology. However, graph parameters like distance and smoothness constraints must be experimentally assigned by retinal region and pathology, thus degrading the flexibility and time efficiency of the whole framework. In this paper, we develop cascaded deep networks to provide a topologically correct segmentation of the retinal layers in a single feed forward propagation. The first network (S-Net) performs pixel-wise labeling and the second regression network (R-Net) takes the topologically unconstrained S-Net results and outputs layer thicknesses for each layer and each position. Relu activation is used as the final operation of the R-Net which guarantees non-negativity of the output layer thickness. Since the segmentation boundary position is acquired by summing up the corresponding non-negative layer thicknesses, the layer ordering (i.e., topology) of the reconstructed boundaries is guaranteed even at the fovea where the distances between boundaries can be zero. The R-Net is trained using simulated masks and thus can be generalized to provide topology guaranteed segmentation for other layered structures. This deep network has achieved comparable mean absolute boundary error (2.82 {\mu}m) to state-of-the-art graph methods (2.83 {\mu}m).

##### Abstract (translated by Google)
光学相干断层扫描（OCT）是一种无创成像模式，可用于获取视网膜的深度图像。因此可以通过分析这些OCT图像来量化变化的层厚度，而且已经显示这些变化与多发性硬化症中的疾病进展相关。最近的自动视网膜层分割工具使用机器学习方法来执行像素方式标记和图形方法以保证图层分层结构或拓扑结构。然而，像距离和平滑度约束等图形参数必须通过视网膜区域和病理进行实验指定，从而降低整个框架的灵活性和时间效率。在本文中，我们开发了级联深度网络，以在单一前馈传播中提供拓扑正确的视网膜层分割。第一个网络（S-Net）执行按像素标记，第二个回归网络（R-Net）采用拓扑不受约束的S-Net结果，并输出每层和每个位置的层厚度。 Relu激活被用作R-Net的最终操作，其保证了输出层厚度的非负性。由于分割边界位置是通过对相应的非负层厚度求和而获得的，所以即使在边界之间的距离可以为零的中心凹处也保证了重构边界的层次排序（即，拓扑结构）。 R-Net使用模拟掩模进行训练，因此可以推广到为其他分层结构提供拓扑保证分割。这个深度网络已经达到可比较的平均绝对边界误差（2.82微米）到最先进的图形方法（2.83微米）。

##### URL
[https://arxiv.org/abs/1803.05120](https://arxiv.org/abs/1803.05120)

##### PDF
[https://arxiv.org/pdf/1803.05120](https://arxiv.org/pdf/1803.05120)

