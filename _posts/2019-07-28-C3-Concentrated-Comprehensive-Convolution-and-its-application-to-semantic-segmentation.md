---
layout: post
title: "C3: Concentrated-Comprehensive Convolution and its application to semantic segmentation"
date: 2019-07-28 13:56:06
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Hyojin Park, Youngjoon Yoo, Geonseok Seo, Dongyoon Han, Sangdoo Yun, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
One of the practical choices for making a lightweight semantic segmentation model is to combine a depth-wise separable convolution with a dilated convolution. However, the simple combination of these two methods results in an over-simplified operation which causes severe performance degradation due to loss of information contained in the feature map. To resolve this problem, we propose a new block called Concentrated-Comprehensive Convolution (C3) which applies the asymmetric convolutions before the depth-wise separable dilated convolution to compensate for the information loss due to dilated convolution. The C3 block consists of a concentration stage and a comprehensive convolution stage. The first stage uses two depth-wise asymmetric convolutions for compressed information from the neighboring pixels to alleviate the information loss. The second stage increases the receptive field by using a depth-wise separable dilated convolution from the feature map of the first stage. We applied the C3 block to various segmentation frameworks (ESPNet, DRN, ERFNet, ENet) for proving the beneficial properties of our proposed method. Experimental results show that the proposed method preserves the original accuracies on Cityscapes dataset while reducing the complexity. Furthermore, we modified ESPNet to achieve about 2% better performance while reducing the number of parameters by half and the number of FLOPs by 35% compared with the original ESPNet. Finally, experiments on ImageNet classification task show that C3 block can successfully replace dilated convolutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04920](http://arxiv.org/abs/1812.04920)

##### PDF
[http://arxiv.org/pdf/1812.04920](http://arxiv.org/pdf/1812.04920)

