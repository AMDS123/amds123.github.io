---
layout: post
title: "Fooling a Real Car with Adversarial Traffic Signs"
date: 2019-06-30 12:42:09
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Attention Image_Classification Classification Recognition
author: Nir Morgulis, Alexander Kreines, Shachar Mendelowitz, Yuval Weisglass
mathjax: true
---

* content
{:toc}

##### Abstract
The attacks on the neural-network-based classifiers using adversarial images have gained a lot of attention recently. An adversary can purposely generate an image that is indistinguishable from a innocent image for a human being but is incorrectly classified by the neural networks. The adversarial images do not need to be tuned to a particular architecture of the classifier - an image that fools one network can fool another one with a certain success rate.The published works mostly concentrate on the use of modified image files for attacks against the classifiers trained on the model databases. Although there exists a general understanding that such attacks can be carried in the real world as well, the works considering the real-world attacks are scarce. Moreover, to the best of our knowledge, there have been no reports on the attacks against real production-grade image classification systems.In our work we present a robust pipeline for reproducible production of adversarial traffic signs that can fool a wide range of classifiers, both open-source and production-grade in the real world. The efficiency of the attacks was checked both with the neural-network-based classifiers and legacy computer vision systems. Most of the attacks have been performed in the black-box mode, e.g. the adversarial signs produced for a particular classifier were used to attack a variety of other classifiers. The efficiency was confirmed in drive-by experiments with a production-grade traffic sign recognition systems of a real car.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00374](http://arxiv.org/abs/1907.00374)

##### PDF
[http://arxiv.org/pdf/1907.00374](http://arxiv.org/pdf/1907.00374)

