---
layout: post
title: "Beyond Forward Shortcuts: Fully Convolutional Master-Slave Networks with Backward Skip Connections for Semantic Segmentation"
date: 2017-07-18 09:31:05
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Prediction
author: Abrar H. Abdulnabi, Stefan Winkler, Gang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep CNNs contain forward shortcut connections; i.e. skip connections from low to high layers. Reusing features from lower layers that have higher resolution (location information) benefit higher layers to recover lost details and mitigate information degradation. However, during inference the lower layers do not know about high layer features, although they contain contextual high semantics that benefit low layers to adaptively extract informative features for later layers. In this paper, we study the influence of backward skip connections which are in the opposite direction to forward shortcuts, i.e. paths from high layers to low layers. To achieve this -- which indeed runs counter to the nature of feed-forward networks -- we propose a new fully convolutional model that consists of a pair of networks. A `Slave' network is dedicated to provide the backward connections from its top layers to the `Master' network's bottom layers. The Master network is used to produce the final label predictions. In our experiments we validate the proposed FCN model on ADE20K (ImageNet scene parsing), PASCAL-Context, and PASCAL VOC 2011 datasets.

##### Abstract (translated by Google)
最近的深度CNN包含前向快捷连接;即跳过从低层到高层的连接。重新使用具有更高分辨率（位置信息）的较低层的特征有利于较高层来恢复丢失的细节并减轻信息劣化。然而，在推理过程中，较低层不知道高层特征，尽管它们包含有利于低层的上下文高语义，以自适应地提取稍后层的信息特征。在本文中，我们研究了向后跳转连接的方向与正向快捷方向相反的方向，即从高层到低层的路径的影响。为了实现这一点 - 这确实与前馈网络的性质背道而驰 - 我们提出了一个由一对网络组成的新的完全卷积模型。 “从属”网络专用于提供从顶层到“主”网络底层的反向连接。主网络被用来产生最终的标签预测。在我们的实验中，我们验证了在ADE20K（ImageNet场景解析），PASCAL-Context和PASCAL VOC 2011数据集上提出的FCN模型。

##### URL
[https://arxiv.org/abs/1707.05537](https://arxiv.org/abs/1707.05537)

##### PDF
[https://arxiv.org/pdf/1707.05537](https://arxiv.org/pdf/1707.05537)

