---
layout: post
title: "BS-Nets: An End-to-End Framework For Band Selection of Hyperspectral Image"
date: 2019-04-17 13:41:38
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Relation
author: Yaoming Cai, Xiaobo Liu, Zhihua Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral image (HSI) consists of hundreds of continuous narrow bands with high spectral correlation, which would lead to the so-called Hughes phenomenon and the high computational cost in processing. Band selection has been proven effective in avoiding such problems by removing the redundant bands. However, many of existing band selection methods separately estimate the significance for every single band and cannot fully consider the nonlinear and global interaction between spectral bands. In this paper, by assuming that a complete HSI can be reconstructed from its few informative bands, we propose a general band selection framework, Band Selection Network (termed as BS-Net). The framework consists of a band attention module (BAM), which aims to explicitly model the nonlinear inter-dependencies between spectral bands, and a reconstruction network (RecNet), which is used to restore the original HSI cube from the learned informative bands, resulting in a flexible architecture. The resulting framework is end-to-end trainable, making it easier to train from scratch and to combine with existing networks. We implement two BS-Nets respectively using fully connected networks (BS-Net-FC) and convolutional neural networks (BS-Net-Conv), and compare the results with many existing band selection approaches for three real hyperspectral images, demonstrating that the proposed BS-Nets can accurately select informative band subset with less redundancy and achieve significantly better classification performance with an acceptable time cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08269](http://arxiv.org/abs/1904.08269)

##### PDF
[http://arxiv.org/pdf/1904.08269](http://arxiv.org/pdf/1904.08269)

