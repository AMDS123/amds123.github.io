---
layout: post
title: "Matrix and tensor decompositions for training binary neural networks"
date: 2019-04-16 17:57:27
categories: arXiv_AI
tags: arXiv_AI Pose_Estimation CNN Inference Classification
author: Adrian Bulat, Jean Kossaifi, Georgios Tzimiropoulos, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is on improving the training of binary neural networks in which both activations and weights are binary. While prior methods for neural network binarization binarize each filter independently, we propose to instead parametrize the weight tensor of each layer using matrix or tensor decomposition. The binarization process is then performed using this latent parametrization, via a quantization function (e.g. sign function) applied to the reconstructed weights. A key feature of our method is that while the reconstruction is binarized, the computation in the latent factorized space is done in the real domain. This has several advantages: (i) the latent factorization enforces a coupling of the filters before binarization, which significantly improves the accuracy of the trained models. (ii) while at training time, the binary weights of each convolutional layer are parametrized using real-valued matrix or tensor decomposition, during inference we simply use the reconstructed (binary) weights. As a result, our method does not sacrifice any advantage of binary networks in terms of model compression and speeding-up inference. As a further contribution, instead of computing the binary weight scaling factors analytically, as in prior work, we propose to learn them discriminatively via back-propagation. Finally, we show that our approach significantly outperforms existing methods when tested on the challenging tasks of (a) human pose estimation (more than 4% improvements) and (b) ImageNet classification (up to 5% performance gains).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07852](http://arxiv.org/abs/1904.07852)

##### PDF
[http://arxiv.org/pdf/1904.07852](http://arxiv.org/pdf/1904.07852)

