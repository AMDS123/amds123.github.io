---
layout: post
title: "Single Image Super-Resolution Using Lightweight CNN with Maxout Units"
date: 2018-12-13 02:30:29
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge CNN Classification
author: Jae-Seok Choi, Munchurl Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Rectified linear units (ReLU) are well-known to be helpful in obtaining faster convergence and thus higher performance for many deep-learning-based applications. However, networks with ReLU tend to perform poorly when the number of filter parameters is constrained to a small number. To overcome it, in this paper, we propose a novel network utilizing maxout units (MU), and show its effectiveness on super-resolution (SR) applications. In general, the MU has been known to make the filter sizes doubled in generating the feature maps of the same sizes in classification problems. In this paper, we first reveal that the MU can even make the filter sizes halved in restoration problems thus leading to compaction of the network sizes. To show this, our SR network is designed without increasing the filter sizes with MU, which outperforms the state of the art SR methods with a smaller number of filter parameters. To the best of our knowledge, we are the first to incorporate MU into SR applications and show promising performance results. In MU, feature maps from a previous convolutional layer are divided into two parts along channels, which are then compared element-wise and only their max values are passed to a next layer. Along with some interesting properties of MU to be analyzed, we further investigate other variants of MU and their effects. In addition, while ReLU have a trouble for learning in networks with a very small number of convolutional filter parameters, MU do not. For SR applications, our MU-based network reconstructs high-resolution images with comparable quality compared to previous deep-learning-based SR methods, with lower filter parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.02321](http://arxiv.org/abs/1711.02321)

##### PDF
[http://arxiv.org/pdf/1711.02321](http://arxiv.org/pdf/1711.02321)

