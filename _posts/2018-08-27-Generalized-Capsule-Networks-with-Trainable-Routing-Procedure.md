---
layout: post
title: "Generalized Capsule Networks with Trainable Routing Procedure"
date: 2018-08-27 05:44:19
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Zhenhua Chen, David Crandall
mathjax: true
---

* content
{:toc}

##### Abstract
CapsNet (Capsule Network) was first proposed by~\citet{capsule} and later another version of CapsNet was proposed by~\citet{emrouting}. CapsNet has been proved effective in modeling spatial features with much fewer parameters. However, the routing procedures in both papers are not well incorporated into the whole training process. The optimal number of routing procedure is misery which has to be found manually. To overcome this disadvantages of current routing procedures in CapsNet, we embed the routing procedure into the optimization procedure with all other parameters in neural networks, namely, make coupling coefficients in the routing procedure become completely trainable. We call it Generalized CapsNet (G-CapsNet). We implement both "full-connected" version of G-CapsNet and "convolutional" version of G-CapsNet. G-CapsNet achieves a similar performance in the dataset MNIST as in the original papers. We also test two capsule packing method (cross feature maps or with feature maps) from previous convolutional layers and see no evident difference. Besides, we also explored possibility of stacking multiple capsule layers. The code is shared on \hyperlink{https://github.com/chenzhenhua986/CAFFE-CapsNet}{CAFFE-CapsNet}.

##### Abstract (translated by Google)
CapsNet（胶囊网络）最初由〜\ citet {capsule}提出，后来另一个版本的CapsNet由〜\ citet {emrouting}提出。已经证明CapsNet在用更少的参数建模空间特征方面是有效的。但是，两篇论文中的路由程序都没有很好地融入整个培训过程。路由过程的最佳数量是必须手动找到的痛苦。为了克服CapsNet中当前路由过程的这些缺点，我们将路由过程嵌入到神经网络中所有其他参数的优化过程中，即，使路由过程中的耦合系数变得完全可训练。我们称之为广义CapsNet（G-CapsNet）。我们实施了G-CapsNet的“全连接”版本和G-CapsNet的“卷积”版本。 G-CapsNet在数据集MNIST中实现了与原始论文中类似的性能。我们还测试了来自先前卷积层的两种胶囊包装方法（交叉特征图或具有特征图），并且没有看到明显的差异。此外，我们还探索了堆叠多个胶囊层的可能性。代码在\ hyperlink {https://github.com/chenzhenhua986/CAFFE-CapsNet} {CAFFE-CapsNet}上共享。

##### URL
[http://arxiv.org/abs/1808.08692](http://arxiv.org/abs/1808.08692)

##### PDF
[http://arxiv.org/pdf/1808.08692](http://arxiv.org/pdf/1808.08692)

