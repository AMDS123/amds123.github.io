---
layout: post
title: "Large-scale mammography CAD with Deformable Conv-Nets"
date: 2019-02-19 22:18:22
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Stephen Morrell, Zbigniew Wojna, Can Son Khoo, Sebastien Ourselin, Juan Eugenio Iglesias
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art deep learning methods for image processing are evolving into increasingly complex meta-architectures with a growing number of modules. Among them, region-based fully convolutional networks (R-FCN) and deformable convolutional nets (DCN) can improve CAD for mammography: R-FCN optimizes for speed and low consumption of memory, which is crucial for processing the high resolutions of to 50 micrometers used by radiologists. Deformable convolution and pooling can model a wide range of mammographic findings of different morphology and scales, thanks to their versatility. In this study, we present a neural net architecture based on R-FCN / DCN, that we have adapted from the natural image domain to suit mammograms -- particularly their larger image size -- without compromising resolution. We trained the network on a large, recently released dataset (Optimam) including 6,500 cancerous mammograms. By combining our modern architecture with such a rich dataset, we achieved an area under the ROC curve of 0.879 for breast-wise detection in the DREAMS challenge (130,000 withheld images), which surpassed all other submissions in the competitive phase.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07323](http://arxiv.org/abs/1902.07323)

##### PDF
[http://arxiv.org/pdf/1902.07323](http://arxiv.org/pdf/1902.07323)

