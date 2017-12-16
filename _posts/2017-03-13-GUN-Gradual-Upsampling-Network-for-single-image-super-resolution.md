---
layout: post
title: "GUN: Gradual Upsampling Network for single image super-resolution"
date: 2017-03-13 04:34:12
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yang Zhao, Ronggang Wang, Weisheng Dong, Wei Jia, Jianchao Yang, Xiaoping Liu, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an efficient super-resolution (SR) method based on deep convolutional neural network (CNN), namely gradual upsampling network (GUN). Recent CNN based SR methods either preliminarily magnify the low resolution (LR) input to high resolution (HR) and then reconstruct the HR input, or directly reconstruct the LR input and then recover the HR result at the last layer. The proposed GUN utilizes a gradual process instead of these two kinds of frameworks. The GUN consists of an input layer, multistep upsampling and convolutional layers, and an output layer. By means of the gradual process, the proposed network can simplify the difficult direct SR problem to multistep easier upsampling tasks with very small magnification factor in each step. Furthermore, a gradual training strategy is presented for the GUN. In the proposed training process, an initial network can be easily trained with edge-like samples, and then the weights are gradually tuned with more complex samples. The GUN can recover fine and vivid results, and is easy to be trained. The experimental results on several image sets demonstrate the effectiveness of the proposed network.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于深度卷积神经网络（CNN）的渐进式采样网络（GUN）的高效超分辨率（SR）方法。最近基于CNN的SR方法或者初步将低分辨率（LR）输入放大到高分辨率（HR），然后重建HR输入，或者直接重建LR输入，然后恢复最后一层的HR结果。建议的GUN采用逐步过程而不是这两种框架。 GUN由输入层，多步上采样和卷积层以及输出层组成。通过渐进过程，所提出的网络可以将困难的直接SR问题简化为在每个步骤中具有非常小的放大倍数的多步更容易的上采样任务。此外，为GUN提供了一个渐进的培训战略。在所提出的训练过程中，初始网络可以很容易地用边缘样本训练，然后用更复杂的样本逐渐调整权重。 GUN可以恢复精细和生动的结果，并且容易被训练。在几个图像集上的实验结果证明了所提出的网络的有效性。

##### URL
[https://arxiv.org/abs/1703.04244](https://arxiv.org/abs/1703.04244)

##### PDF
[https://arxiv.org/pdf/1703.04244](https://arxiv.org/pdf/1703.04244)

