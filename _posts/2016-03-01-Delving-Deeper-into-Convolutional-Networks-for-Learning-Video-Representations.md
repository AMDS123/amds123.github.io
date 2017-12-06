---
layout: post
title: 'Delving Deeper into Convolutional Networks for Learning Video Representations'
date: 2016-03-01 18:54:11
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Action_Recognition CNN Recognition
author: Nicolas Ballas, Li Yao, Chris Pal, Aaron Courville
---

* content
{:toc}

##### Abstract
We propose an approach to learn spatio-temporal features in videos from intermediate visual representations we call "percepts" using Gated-Recurrent-Unit Recurrent Networks (GRUs).Our method relies on percepts that are extracted from all level of a deep convolutional network trained on the large ImageNet dataset. While high-level percepts contain highly discriminative information, they tend to have a low-spatial resolution. Low-level percepts, on the other hand, preserve a higher spatial resolution from which we can model finer motion patterns. Using low-level percepts can leads to high-dimensionality video representations. To mitigate this effect and control the model number of parameters, we introduce a variant of the GRU model that leverages the convolution operations to enforce sparse connectivity of the model units and share parameters across the input spatial locations. We empirically validate our approach on both Human Action Recognition and Video Captioning tasks. In particular, we achieve results equivalent to state-of-art on the YouTube2Text dataset using a simpler text-decoder model and without extra 3D CNN features.

##### Abstract (translated by Google)
我们提出了一种方法来学习中间视觉表示视频中的时空特征，我们称之为“感知”，使用门控循环单元递归网络（GRUs）。我们的方法依赖于从深层卷积网络在大的ImageNet数据集上。虽然高级知觉包含高度区别性信息，但它们往往具有低空间分辨率。另一方面，低级别感知能够保持更高的空间分辨率，从而可以对更精细的运动模式进行建模。使用低级别感知可以导致高维视频表示。为了减轻这种影响并控制参数的模型数量，我们引入了一个GRU模型的变体，它利用卷积运算来实现模型单元的稀疏连接，并跨输入空间位置共享参数。我们凭经验验证了我们在人体识别和视频字幕任务上的方法。特别是，我们使用更简单的文本解码器模型，无需额外的3D CNN功能，就可以在YouTube2Text数据集上实现与现有技术相当的效果。

##### URL
[https://arxiv.org/abs/1511.06432](https://arxiv.org/abs/1511.06432)

