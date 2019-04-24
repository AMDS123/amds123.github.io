---
layout: post
title: "Dynamic Multi-Context Segmentation of Remote Sensing Images based on Convolutional Networks"
date: 2019-04-23 02:01:11
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Keiller Nogueira, Mauro Dalla Mura, Jocelyn Chanussot, William R. Schwartz, Jefersson A. dos Santos
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation requires methods capable of learning high-level features while dealing with large volume of data. Towards such goal, Convolutional Networks can learn specific and adaptable features based on the data. However, these networks are not capable of processing a whole remote sensing image, given its huge size. To overcome such limitation, the image is processed using fixed size patches. The definition of the input patch size is usually performed empirically (evaluating several sizes) or imposed (by network constraint). Both strategies suffer from drawbacks and could not lead to the best patch size. To alleviate this problem, several works exploited multi-context information by combining networks or layers. This process increases the number of parameters resulting in a more difficult model to train. In this work, we propose a novel technique to perform semantic segmentation of remote sensing images that exploits a multi-context paradigm without increasing the number of parameters while defining, in training time, the best patch size. The main idea is to train a dilated network with distinct patch sizes, allowing it to capture multi-context characteristics from heterogeneous contexts. While processing these varying patches, the network provides a score for each patch size, helping in the definition of the best size for the current scenario. A systematic evaluation of the proposed algorithm is conducted using four high-resolution remote sensing datasets with very distinct properties. Our results show that the proposed algorithm provides improvements in pixelwise classification accuracy when compared to state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.04020](http://arxiv.org/abs/1804.04020)

##### PDF
[http://arxiv.org/pdf/1804.04020](http://arxiv.org/pdf/1804.04020)

