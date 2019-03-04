---
layout: post
title: "A Deep DUAL-PATH Network for Improved Mammogram Image Processing"
date: 2019-03-01 11:51:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Relation
author: Heyi Li, Dongdong Chen, William H. Nailon, Mike E. Davies, Dave Laurenson
mathjax: true
---

* content
{:toc}

##### Abstract
We present, for the first time, a novel deep neural network architecture called \dcn with a dual-path connection between the input image and output class label for mammogram image processing. This architecture is built upon U-Net, which non-linearly maps the input data into a deep latent space. One path of the \dcnn, the locality preserving learner, is devoted to hierarchically extracting and exploiting intrinsic features of the input, while the other path, called the conditional graph learner, focuses on modeling the input-mask correlations. The learned mask is further used to improve classification results, and the two learning paths complement each other. By integrating the two learners our new architecture provides a simple but effective way to jointly learn the segmentation and predict the class label. Benefiting from the powerful expressive capacity of deep neural networks a more discriminative representation can be learned, in which both the semantics and structure are well preserved. Experimental results show that \dcn achieves the best mammography segmentation and classification simultaneously, outperforming recent state-of-the-art models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00001](http://arxiv.org/abs/1903.00001)

##### PDF
[http://arxiv.org/pdf/1903.00001](http://arxiv.org/pdf/1903.00001)

