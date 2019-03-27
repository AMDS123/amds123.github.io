---
layout: post
title: "Object Localization with a Weakly Supervised CapsNet"
date: 2019-03-26 00:21:16
categories: arXiv_CV
tags: arXiv_CV Sparse Weakly_Supervised Transfer_Learning
author: Weitang Liu, Emad Barsoum, John D. Owens
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by CapsNet's routing-by-agreement mechanism with its ability to learn object properties, we propose a CapsNet architecture with object coordinate atoms and a modified routing-by-agreement algorithm with unevenly distributed initial routing probabilities. The model is based on CapsNet but uses a routing algorithm to find the objects' approximate positions in the image coordinate system. We also discussed how to derive the property of translation through coordinate atoms and we discover the importance of sparse representation. We train our model on the single moving MNIST dataset with class labels. Our model can learn and derive the coordinates of the digits better than its convolution counterpart that lacks a routing-by-agreement algorithm, and can also perform well when testing on the multi-digit moving MNIST datasets. When deriving the coordinates, our model performs at least 13\%, 24\%, and 51\% better than the convNet counterpart and ResNet 20 benchmarks on 1-digit, 2-digit, and 3-digit moving MNIST datasets. This shows our method has better transfer learning properties on unseen scenarios of the new but related datasets. We also achieve slightly better performance than the ResNet benchmark in the KTH dataset; these results show our method reaches the state-of-art performance on object localization without any extra localization techniques and modules as in prior work.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07706](http://arxiv.org/abs/1805.07706)

##### PDF
[http://arxiv.org/pdf/1805.07706](http://arxiv.org/pdf/1805.07706)

