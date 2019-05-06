---
layout: post
title: "GP-CNAS: Convolutional Neural Network Architecture Search with Genetic Programming"
date: 2018-11-26 17:44:15
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition NAS CNN Recognition
author: Yiheng Zhu, Yichen Yao, Zili Wu, Yujie Chen, Guozheng Li, Haoyuan Hu, Yinghui Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) are effective at solving difficult problems like visual recognition, speech recognition and natural language processing. However, performance gain comes at the cost of laborious trial-and-error in designing deeper CNN architectures. In this paper, a genetic programming (GP) framework for convolutional neural network architecture search, abbreviated as GP-CNAS, is proposed to automatically search for optimal CNN architectures. GP-CNAS encodes CNNs as trees where leaf nodes (GP terminals) are selected residual blocks and non-leaf nodes (GP functions) specify the block assembling procedure. Our tree-based representation enables easy design and flexible implementation of genetic operators. Specifically, we design a dynamic crossover operator that strikes a balance between exploration and exploitation, which emphasizes CNN complexity at early stage and CNN diversity at later stage. Therefore, the desired CNN architecture with balanced depth and width can be found within limited trials. Moreover, our GP-CNAS framework is highly compatible with other manually-designed and NAS-generated block types as well. Experimental results on the CIFAR-10 dataset show that GP-CNAS is competitive among the state-of-the-art automatic and semi-automatic NAS algorithms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.07611](https://arxiv.org/abs/1812.07611)

##### PDF
[https://arxiv.org/pdf/1812.07611](https://arxiv.org/pdf/1812.07611)

