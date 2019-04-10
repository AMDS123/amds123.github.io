---
layout: post
title: "MoDL-MUSSELS: Model-Based Deep Learning for Multi-Shot Sensitivity Encoded Diffusion MRI"
date: 2019-04-08 18:42:16
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation
author: Hemant Kumar Aggarwal, Merry P. Mani, Mathews Jacob
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a model-based deep learning architecture termed MoDL-MUSSELS for the correction of phase errors in multishot diffusion-weighted echo-planar MRI images. The proposed algorithm is a generalization of existing MUSSELS algorithm with similar performance but with significantly reduced computational complexity. In this work, we show that an iterative re-weighted least-squares implementation of MUSSELS alternates between a multichannel filter bank and the enforcement of data consistency. The multichannel filter bank projects the data to the signal subspace thus exploiting the phase relations between shots. Due to the high computational complexity of self-learned filter bank, we propose to replace it with a convolutional neural network (CNN) whose parameters are learned from exemplary data. The proposed CNN is a hybrid model involving a multichannel CNN in the k-space and another CNN in the image space. The k-space CNN exploits the phase relations between the shot images, while the image domain network is used to project the data to an image manifold. The experiments show that the proposed scheme can yield reconstructions that are comparable to state of the art methods while offering several orders of magnitude reduction in run-time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08115](http://arxiv.org/abs/1812.08115)

##### PDF
[http://arxiv.org/pdf/1812.08115](http://arxiv.org/pdf/1812.08115)

