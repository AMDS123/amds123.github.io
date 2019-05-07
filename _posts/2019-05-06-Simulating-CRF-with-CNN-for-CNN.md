---
layout: post
title: "Simulating CRF with CNN for CNN"
date: 2019-05-06 17:27:32
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Knowledge Segmentation Optimization
author: Lena Gorelick, Olga Veksler
mathjax: true
---

* content
{:toc}

##### Abstract
Combining CNN with CRF for modeling dependencies between pixel labels is a popular research direction. This task is far from trivial, especially if end-to-end training is desired. In this paper, we propose a novel simple approach to CNN+CRF combination. In particular, we propose to simulate a CRF regularizer with a trainable module that has standard CNN architecture. We call this module a CRF Simulator. We can automatically generate an unlimited amount of ground truth for training such CRF Simulator without any user interaction, provided we have an efficient algorithm for optimization of the actual CRF regularizer. After our CRF Simulator is trained, it can be directly incorporated as part of any larger CNN architecture, enabling a seamless end-to-end training. In particular, the other modules can learn parameters that are more attuned to the performance of the CRF Simulator module. We demonstrate the effectiveness of our approach on the task of salient object segmentation regularized with the standard binary CRF energy. In contrast to previous work we do not need to develop and implement the complex mechanics of optimizing a specific CRF as part of CNN. In fact, our approach can be easily extended to other CRF energies, including multi-label. To the best of our knowledge we are the first to study the question of whether the output of CNNs can have regularization properties of CRFs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02163](http://arxiv.org/abs/1905.02163)

##### PDF
[http://arxiv.org/pdf/1905.02163](http://arxiv.org/pdf/1905.02163)

