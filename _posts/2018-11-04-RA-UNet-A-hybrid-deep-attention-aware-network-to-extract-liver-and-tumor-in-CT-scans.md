---
layout: post
title: "RA-UNet: A hybrid deep attention-aware network to extract liver and tumor in CT scans"
date: 2018-11-04 06:18:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN
author: Qiangguo Jin, Zhaopeng Meng, Changming Sun, Leyi Wei, Ran Su
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic extraction of liver and tumor from CT volumes is a challenging task due to their heterogeneous and diffusive shapes. Recently, 2D and 3D deep convolutional neural networks have become popular in medical image segmentation tasks because of the utilization of large labeled datasets to learn hierarchical features. However, 3D networks have some drawbacks due to their high cost on computational resources. In this paper, we propose a 3D hybrid residual attention-aware segmentation method, named RA-UNet, to precisely extract the liver volume of interests (VOI) and segment tumors from the liver VOI. The proposed network has a basic architecture as a 3D U-Net which extracts contextual information combining low-level feature maps with high-level ones. Attention modules are stacked so that the attention-aware features change adaptively as the network goes "very deep" and this is made possible by residual learning. This is the first work that an attention residual mechanism is used to process medical volumetric images. We evaluated our framework on the public MICCAI 2017 Liver Tumor Segmentation dataset and the 3DIRCADb dataset. The results show that our architecture outperforms other state-of-the-art methods. We also extend our RA-UNet to brain tumor segmentation on the BraTS2018 and BraTS2017 datasets, and the results indicate that RA-UNet achieves good performance on a brain tumor segmentation task as well.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01328](http://arxiv.org/abs/1811.01328)

##### PDF
[http://arxiv.org/pdf/1811.01328](http://arxiv.org/pdf/1811.01328)

