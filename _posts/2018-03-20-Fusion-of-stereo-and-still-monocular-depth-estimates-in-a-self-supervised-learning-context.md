---
layout: post
title: "Fusion of stereo and still monocular depth estimates in a self-supervised learning context"
date: 2018-03-20 16:24:21
categories: arXiv_CV
tags: arXiv_CV CNN SLAM
author: Diogo Martins, Kevin van Hecke, Guido de Croon
mathjax: true
---

* content
{:toc}

##### Abstract
We study how autonomous robots can learn by themselves to improve their depth estimation capability. In particular, we investigate a self-supervised learning setup in which stereo vision depth estimates serve as targets for a convolutional neural network (CNN) that transforms a single still image to a dense depth map. After training, the stereo and mono estimates are fused with a novel fusion method that preserves high confidence stereo estimates, while leveraging the CNN estimates in the low-confidence regions. The main contribution of the article is that it is shown that the fused estimates lead to a higher performance than the stereo vision estimates alone. Experiments are performed on the KITTI dataset, and on board of a Parrot SLAMDunk, showing that even rather limited CNNs can help provide stereo vision equipped robots with more reliable depth maps for autonomous navigation.

##### Abstract (translated by Google)
我们研究自主机器人如何自行学习以提高其深度估计能力。特别是，我们调查了一个自我监督学习设置，其中立体视觉深度估计作为卷积神经网络（CNN）的目标，将单个静止图像转换为密集深度图。训练后，立体声和单声道估计与融合方法融合，保留了高置信立体声估计，同时利用低置信区域的CNN估计。文章的主要贡献是，它表明融合估计导致比单独的立体视觉估计更高的性能。在KITTI数据集和Parrot SLAMDunk上进行了实验，表明即使相当有限的CNN也可以为配备立体视觉的机器人提供更可靠的自动导航深度图。

##### URL
[http://arxiv.org/abs/1803.07512](http://arxiv.org/abs/1803.07512)

##### PDF
[http://arxiv.org/pdf/1803.07512](http://arxiv.org/pdf/1803.07512)

