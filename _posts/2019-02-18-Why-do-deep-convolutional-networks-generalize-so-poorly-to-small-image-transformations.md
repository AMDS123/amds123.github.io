---
layout: post
title: "Why do deep convolutional networks generalize so poorly to small image transformations?"
date: 2019-02-18 11:33:27
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Aharon Azulay, Yair Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional network architectures are often assumed to guarantee generalization for small image translations and deformations. In this paper we show that modern CNNs (VGG16, ResNet50, and InceptionResNetV2) can drastically change their output when an image is translated in the image plane by a few pixels, and that this failure of generalization also happens with other realistic small image transformations. Furthermore, the deeper the network the more we see these failures to generalize. We show that these failures are related to the fact that the architecture of modern CNNs ignores the classical sampling theorem so that generalization is not guaranteed. We also show that biases in the statistics of commonly used image datasets makes it unlikely that CNNs will learn to be invariant to these transformations. Taken together our results suggest that the performance of CNNs in object recognition falls far short of the generalization capabilities of humans.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.12177](http://arxiv.org/abs/1805.12177)

##### PDF
[http://arxiv.org/pdf/1805.12177](http://arxiv.org/pdf/1805.12177)

