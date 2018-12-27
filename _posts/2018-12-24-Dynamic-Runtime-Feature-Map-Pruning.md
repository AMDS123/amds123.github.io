---
layout: post
title: "Dynamic Runtime Feature Map Pruning"
date: 2018-12-24 13:54:50
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Tailin Liang, Lei Wang, Shaobo Shi, John Glossner
mathjax: true
---

* content
{:toc}

##### Abstract
High bandwidth requirements are an obstacle for accelerating the training and inference of deep neural networks. Most previous research focuses on reducing the size of kernel maps for inference. We analyze parameter sparsity of six popular convolutional neural networks - AlexNet, MobileNet, ResNet-50, SqueezeNet, TinyNet, and VGG16. Of the networks considered, those using ReLU (AlexNet, SqueezeNet, VGG16) contain a high percentage of 0-valued parameters and can be statically pruned. Networks with Non-ReLU activation functions in some cases may not contain any 0-valued parameters (ResNet-50, TinyNet). We also investigate runtime feature map usage and find that input feature maps comprise the majority of bandwidth requirements when depth-wise convolution and point-wise convolutions used. We introduce dynamic runtime pruning of feature maps and show that 10% of dynamic feature map execution can be removed without loss of accuracy. We then extend dynamic pruning to allow for values within an epsilon of zero and show a further 5% reduction of feature map loading with a 1% loss of accuracy in top-1.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09922](http://arxiv.org/abs/1812.09922)

##### PDF
[http://arxiv.org/pdf/1812.09922](http://arxiv.org/pdf/1812.09922)

