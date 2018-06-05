---
layout: post
title: "ProFlow: Learning to Predict Optical Flow"
date: 2018-06-03 14:38:17
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Daniel Maurer, Andr&#xe9;s Bruhn
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal coherence is a valuable source of information in the context of optical flow estimation. However, finding a suitable motion model to leverage this information is a non-trivial task. In this paper we propose an unsupervised online learning approach based on a convolutional neural network (CNN) that estimates such a motion model individually for each frame. By relating forward and backward motion these learned models not only allow to infer valuable motion information based on the backward flow, they also help to improve the performance at occlusions, where a reliable prediction is particularly useful. Moreover, our learned models are spatially variant and hence allow to estimate non-rigid motion per construction. This, in turns, allows to overcome the major limitation of recent rigidity-based approaches that seek to improve the estimation by incorporating additional stereo/SfM constraints. Experiments demonstrate the usefulness of our new approach. They not only show a consistent improvement of up to 27% for all major benchmarks (KITTI 2012, KITTI 2015, MPI Sintel) compared to a baseline without prediction, they also show top results for the MPI Sintel benchmark -- the one of the three benchmarks that contains the largest amount of non-rigid motion.

##### Abstract (translated by Google)
时间相干性是光流估计背景下的重要信息来源。但是，找到合适的运动模型来利用这些信息是一项不重要的任务。在本文中，我们提出了一种基于卷积神经网络（CNN）的无监督在线学习方法，该方法可以针对每个帧单独估计这种运动模型。通过将前向和后向运动相关联，这些学习模型不仅可以基于逆向流推断有价值的运动信息，而且还有助于提高遮挡处的性能，其中可靠的预测特别有用。此外，我们的学习模型是空间变化的，因此可以估计每个建筑的非刚性运动。这反过来又可以克服近来基于刚性的方法的主要局限性，这些方法试图通过引入附加的立体声/ SfM约束来改进估计。实验证明了我们新方法的有用性。他们不仅预测所有主要基准（KITTI 2012，KITTI 2015，MPI Sintel）与未预测的基准相比最高可达27％，而且还显示MPI Sintel基准的最佳结果 - 三个基准中的一个包含最大量的非刚性运动的基准。

##### URL
[http://arxiv.org/abs/1806.00800](http://arxiv.org/abs/1806.00800)

##### PDF
[http://arxiv.org/pdf/1806.00800](http://arxiv.org/pdf/1806.00800)

