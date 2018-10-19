---
layout: post
title: "LadderNet: Multi-path networks based on U-Net for medical image segmentation"
date: 2018-10-17 21:33:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Detection
author: Juntang Zhuang
mathjax: true
---

* content
{:toc}

##### Abstract
U-Net has been providing state-of-the-art performance in many medical image segmentation problems. Many modifications have been proposed for U-Net, such as attention U-Net, recurrent residual convolutional U-Net (R2-UNet), and U-Net with residual blocks or blocks with dense connections. However, all these modifications have an encoder-decoder structure with skip connections, and the number of paths for information flow is limited. We propose LadderNet in this paper, which can be viewed as a chain of multiple U-Nets. Instead of only one pair of encoder branch and decoder branch in U-Net, a LadderNet has multiple pairs of encoder-decoder branches, and has skip connections between every pair of adjacent decoder and decoder branches in each level. Inspired by the success of ResNet and R2-UNet, we use modified residual blocks where two convolutional layers in one block share the same weights. A LadderNet has more paths for information flow because of skip connections and residual blocks, and can be viewed as an ensemble of Fully Convolutional Networks (FCN). The equivalence to an ensemble of FCNs improves segmentation accuracy, while the shared weights within each residual block reduce parameter number. Semantic segmentation is essential for retinal disease detection. We tested LadderNet on two benchmark datasets for blood vessel segmentation in retinal images, and achieved superior performance over methods in the literature.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.07810](https://arxiv.org/abs/1810.07810)

##### PDF
[https://arxiv.org/pdf/1810.07810](https://arxiv.org/pdf/1810.07810)

