---
layout: post
title: "Seesaw-Net: Convolution Neural Network With Uneven Group Convolution"
date: 2019-05-09 14:56:59
categories: arXiv_CV
tags: arXiv_CV NAS CNN Image_Classification Classification
author: Jintao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we are interested in boosting the representation capability of convolution neural networks which utilizing the inverted residual structure. Based on the success of Inverted Residual structure[Sandler et al. 2018] and Interleaved Low-Rank Group Convolutions[Sun et al. 2018], we rethink this two pattern of neural network structure, rather than NAS(Neural architecture search) method[Zoph and Le 2017; Pham et al. 2018; Liu et al. 2018b], we introduce uneven point-wise group convolution, which provide a novel search space for designing basic blocks to obtain better trade-off between representation capability and computational cost. Meanwhile, we propose two novel information flow patterns that will enable cross-group information flow for multiple group convolution layers with and without any channel permute/shuffle operation. Dense experiments on image classification task show that our proposed model, named Seesaw-Net, achieves state-of-the-art(SOTA) performance with limited computation and memory cost. Our code will be open-source and available together with pre-trained models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03672](http://arxiv.org/abs/1905.03672)

##### PDF
[http://arxiv.org/pdf/1905.03672](http://arxiv.org/pdf/1905.03672)

