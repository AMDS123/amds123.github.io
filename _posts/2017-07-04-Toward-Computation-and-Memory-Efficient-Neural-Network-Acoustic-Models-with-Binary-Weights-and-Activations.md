---
layout: post
title: "Toward Computation and Memory Efficient Neural Network Acoustic Models with Binary Weights and Activations"
date: 2017-07-04 17:03:20
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Inference Recognition
author: Liang Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network acoustic models have significantly advanced state of the art speech recognition over the past few years. However, they are usually computationally expensive due to the large number of matrix-vector multiplications and nonlinearity operations. Neural network models also require significant amounts of memory for inference because of the large model size. For these two reasons, it is challenging to deploy neural network based speech recognizers on resource-constrained platforms such as embedded devices. This paper investigates the use of binary weights and activations for computation and memory efficient neural network acoustic models. Compared to real-valued weight matrices, binary weights require much fewer bits for storage, thereby cutting down the memory footprint. Furthermore, with binary weights or activations, the matrix-vector multiplications are turned into addition and subtraction operations, which are computationally much faster and more energy efficient for hardware platforms. In this paper, we study the applications of binary weights and activations for neural network acoustic modeling, reporting encouraging results on the WSJ and AMI corpora.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.09453](https://arxiv.org/abs/1706.09453)

##### PDF
[https://arxiv.org/pdf/1706.09453](https://arxiv.org/pdf/1706.09453)

