---
layout: post
title: "Weakly supervised learning of indoor geometry by dual warping"
date: 2018-08-10 16:31:51
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Prediction
author: Pulak Purkait, Ujwal Bonde, Christopher Zach
mathjax: true
---

* content
{:toc}

##### Abstract
A major element of depth perception and 3D understanding is the ability to predict the 3D layout of a scene and its contained objects for a novel pose. Indoor environments are particularly suitable for novel view prediction, since the set of objects in such environments is relatively restricted. In this work we address the task of 3D prediction especially for indoor scenes by leveraging only weak supervision. In the literature 3D scene prediction is usually solved via a 3D voxel grid. However, such methods are limited to estimating rather coarse 3D voxel grids, since predicting entire voxel spaces has large computational costs. Hence, our method operates in image-space rather than in voxel space, and the task of 3D estimation essentially becomes a depth image completion problem. We propose a novel approach to easily generate training data containing depth maps with realistic occlusions, and subsequently train a network for completing those occluded regions. Using multiple publicly available dataset~\cite{song2017semantic,Silberman:ECCV12} we benchmark our method against existing approaches and are able to obtain superior performance. We further demonstrate the flexibility of our method by presenting results for new view synthesis of RGB-D images.

##### Abstract (translated by Google)
深度感知和3D理解的一个主要元素是能够预测场景的3D布局及其包含的对象以获得新颖的姿势。室内环境特别适合于新颖的视图预测，因为这种环境中的对象集是相对受限的。在这项工作中，我们通过仅仅利用弱监督来解决3D预测的任务，尤其是室内场景。在文献中，3D场景预测通常通过3D体素网格来解决。然而，这种方法仅限于估计相当粗糙的3D体素网格，因为预测整个体素空间具有大的计算成本。因此，我们的方法在图像空间而不是在体素空间中操作，并且3D估计的任务基本上变成深度图像完成问题。我们提出了一种新方法，可以轻松生成包含具有真实遮挡的深度图的训练数据，并随后训练网络以完成那些遮挡区域。使用多个公开可用的数据集〜\ cite {song2017semantic，Silberman：ECCV12}，我们将方法与现有方法进行对比，并且能够获得卓越的性能。我们通过呈现RGB-D图像的新视图合成的结果进一步证明了我们方法的灵活性。

##### URL
[http://arxiv.org/abs/1808.03609](http://arxiv.org/abs/1808.03609)

##### PDF
[http://arxiv.org/pdf/1808.03609](http://arxiv.org/pdf/1808.03609)

