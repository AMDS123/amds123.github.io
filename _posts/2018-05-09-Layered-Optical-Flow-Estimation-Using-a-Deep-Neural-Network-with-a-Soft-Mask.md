---
layout: post
title: "Layered Optical Flow Estimation Using a Deep Neural Network with a Soft Mask"
date: 2018-05-09 15:45:48
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Xi Zhang, Di Ma, Xu Ouyang, Shanshan Jiang, Lin Gan, Gady Agam
mathjax: true
---

* content
{:toc}

##### Abstract
Using a layered representation for motion estimation has the advantage of being able to cope with discontinuities and occlusions. In this paper, we learn to estimate optical flow by combining a layered motion representation with deep learning. Instead of pre-segmenting the image to layers, the proposed approach automatically generates a layered representation of optical flow using the proposed soft-mask module. The essential components of the soft-mask module are maxout and fuse operations, which enable a disjoint layered representation of optical flow and more accurate flow estimation. We show that by using masks the motion estimate results in a quadratic function of input features in the output layer. The proposed soft-mask module can be added to any existing optical flow estimation networks by replacing their flow output layer. In this work, we use FlowNet as the base network to which we add the soft-mask module. The resulting network is tested on three well-known benchmarks with both supervised and unsupervised flow estimation tasks. Evaluation results show that the proposed network achieve better results compared with the original FlowNet.

##### Abstract (translated by Google)
使用分层表示进行运动估计具有能够应对不连续性和遮挡的优点。在本文中，我们学习通过将分层运动表示与深度学习相结合来估计光流。所提出的方法不是将图像预分割成层，而是使用所提出的软掩模模块自动生成光流的分层表示。软掩模模块的基本组件是maxout和熔丝操作，这使得光流的不连续分层表示和更精确的流量估计成为可能。我们表明，通过使用蒙版，运动估计结果在输出层中的输入要素的二次函数。所提出的软掩模模块可以通过替换它们的流输出层而被添加到任何现有的光流估计网络中。在这项工作中，我们使用FlowNet作为我们添加软掩模模块的基础网络。最终的网络在三个众所周知的基准上进行测试，包括监督和非监督流量估计任务。评估结果表明，与原始的FlowNet相比，所提出的网络取得了更好的结果。

##### URL
[http://arxiv.org/abs/1805.03596](http://arxiv.org/abs/1805.03596)

##### PDF
[http://arxiv.org/pdf/1805.03596](http://arxiv.org/pdf/1805.03596)

