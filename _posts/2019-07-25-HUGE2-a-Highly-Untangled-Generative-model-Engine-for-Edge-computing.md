---
layout: post
title: "HUGE2: a Highly Untangled Generative-model Engine for Edge-computing"
date: 2019-07-25 17:21:52
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Semantic_Segmentation Deep_Learning
author: Feng Shi, Ziheng Xu, Tao Yuan, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
As a type of prominent studies in deep learning, generative models have been widely investigated in research recently. Two research branches of the deep learning models, the Generative Networks (GANs, VAE) and the Semantic Segmentation, rely highly on the upsampling operations, especially the transposed convolution and the dilated convolution. However, these two types of convolutions are intrinsically different from standard convolution regarding the insertion of zeros in input feature maps or in kernels respectively. This distinct nature severely degrades the performance of the existing deep learning engine or frameworks, such as Darknet, Tensorflow, and PyTorch, which are mainly developed for the standard convolution. Another trend in deep learning realm is to deploy the model onto edge/ embedded devices, in which the memory resource is scarce. In this work, we propose a Highly Untangled Generative-model Engine for Edge-computing or HUGE2 for accelerating these two special convolutions on the edge-computing platform by decomposing the kernels and untangling these smaller convolutions by performing basic matrix multiplications. The methods we propose use much smaller memory footprint, hence much fewer memory accesses, and the data access patterns also dramatically increase the reusability of the data already fetched in caches, hence increasing the localities of caches. Our engine achieves a speedup of nearly 5x on embedded CPUs, and around 10x on embedded GPUs, and more than 50% reduction of memory access.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11210](http://arxiv.org/abs/1907.11210)

##### PDF
[http://arxiv.org/pdf/1907.11210](http://arxiv.org/pdf/1907.11210)

