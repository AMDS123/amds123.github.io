---
layout: post
title: "GUN: Gradual Upsampling Network for Single Image Super-Resolution"
date: 2018-07-04 01:49:33
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yang Zhao, Guoqing Li, Wenjun Xie, Wei Jia, Hai Min, Xiaoping Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, an efficient super-resolution (SR) method based on deep convolutional neural network (CNN) is proposed, namely Gradual Upsampling Network (GUN). Recent CNN based SR methods often preliminarily magnify the low resolution (LR) input to high resolution (HR) and then reconstruct the HR input, or directly reconstruct the LR input and then recover the HR result at the last layer. The proposed GUN utilizes a gradual process instead of these two commonly used frameworks. The GUN consists of an input layer, multiple upsampling and convolutional layers, and an output layer. By means of the gradual process, the proposed network can simplify the direct SR problem to multistep easier upsampling tasks with very small magnification factor in each step. Furthermore, a gradual training strategy is presented for the GUN. In the proposed training process, an initial network can be easily trained with edge-like samples, and then the weights are gradually tuned with more complex samples. The GUN can recover fine and vivid results, and is easy to be trained. The experimental results on several image sets demonstrate the effectiveness of the proposed network.

##### Abstract (translated by Google)
本文提出了一种基于深度卷积神经网络（CNN）的高效超分辨率（SR）方法，即渐进上采样网络（GUN）。最近基于CNN的SR方法通常初步将低分辨率（LR）输入放大到高分辨率（HR），然后重建HR输入，或者直接重建LR输入，然后在最后一层恢复HR结果。建议的GUN使用渐进过程而不是这两个常用框架。 GUN由输入层，多个上采样和卷积层以及输出层组成。通过渐进过程，所提出的网络可以在每个步骤中以非常小的放大因子将直接SR问题简化为多步骤更容易的上采样任务。此外，还为GUN提出了逐步的培训策略。在所提出的训练过程中，可以使用类似边缘的样本轻松地训练初始网络，然后使用更复杂的样本逐渐调整权重。 GUN可以恢复精细而生动的结果，并且易于训练。几个图像集的实验结果证明了所提出的网络的有效性。

##### URL
[http://arxiv.org/abs/1703.04244](http://arxiv.org/abs/1703.04244)

##### PDF
[http://arxiv.org/pdf/1703.04244](http://arxiv.org/pdf/1703.04244)

