---
layout: post
title: "Residual Convolutional Neural Network Revisited with Active Weighted Mapping"
date: 2018-11-16 15:51:20
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Jung HyoungHo, Lee Ryong, Lee Sanghwan, Hwang Wonjun
mathjax: true
---

* content
{:toc}

##### Abstract
In visual recognition, the key to the performance improvement of ResNet is the success in establishing the stack of deep sequential convolutional layers using identical mapping by a shortcut connection. It results in multiple paths of data flow under a network and the paths are merged with the equal weights. However, it is questionable whether it is correct to use the fixed and predefined weights at the mapping units of all paths. In this paper, we introduce the active weighted mapping method which infers proper weight values based on the characteristic of input data on the fly. The weight values of each mapping unit are not fixed but changed as the input image is changed, and the most proper weight values for each mapping unit are derived according to the input image. For this purpose, channel-wise information is embedded from both the shortcut connection and convolutional block, and then the fully connected layers are used to estimate the weight values for the mapping units. We train the backbone network and the proposed module alternately for a more stable learning of the proposed method. Results of the extensive experiments show that the proposed method works successfully on the various backbone architectures from ResNet to DenseNet. We also verify the superiority and generality of the proposed method on various datasets in comparison with the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06878](http://arxiv.org/abs/1811.06878)

##### PDF
[http://arxiv.org/pdf/1811.06878](http://arxiv.org/pdf/1811.06878)

