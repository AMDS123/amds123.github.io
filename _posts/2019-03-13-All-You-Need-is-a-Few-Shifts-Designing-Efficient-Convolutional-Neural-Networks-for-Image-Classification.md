---
layout: post
title: "All You Need is a Few Shifts: Designing Efficient Convolutional Neural Networks for Image Classification"
date: 2019-03-13 01:44:39
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Image_Classification Optimization Inference Classification
author: Weijie Chen, Di Xie, Yuan Zhang, Shiliang Pu
mathjax: true
---

* content
{:toc}

##### Abstract
Shift operation is an efficient alternative over depthwise separable convolution. However, it is still bottlenecked by its implementation manner, namely memory movement. To put this direction forward, a new and novel basic component named Sparse Shift Layer (SSL) is introduced in this paper to construct efficient convolutional neural networks. In this family of architectures, the basic block is only composed by 1x1 convolutional layers with only a few shift operations applied to the intermediate feature maps. To make this idea feasible, we introduce shift operation penalty during optimization and further propose a quantization-aware shift learning method to impose the learned displacement more friendly for inference. Extensive ablation studies indicate that only a few shift operations are sufficient to provide spatial information communication. Furthermore, to maximize the role of SSL, we redesign an improved network architecture to Fully Exploit the limited capacity of neural Network (FE-Net). Equipped with SSL, this network can achieve 75.0% top-1 accuracy on ImageNet with only 563M M-Adds. It surpasses other counterparts constructed by depthwise separable convolution and the networks searched by NAS in terms of accuracy and practical speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05285](http://arxiv.org/abs/1903.05285)

##### PDF
[http://arxiv.org/pdf/1903.05285](http://arxiv.org/pdf/1903.05285)

