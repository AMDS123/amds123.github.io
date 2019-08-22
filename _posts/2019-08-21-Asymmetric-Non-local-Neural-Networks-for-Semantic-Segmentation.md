---
layout: post
title: "Asymmetric Non-local Neural Networks for Semantic Segmentation"
date: 2019-08-21 02:26:44
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Zhen Zhu, Mengdu Xu, Song Bai, Tengteng Huang, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
The non-local module works as a particularly useful technique for semantic segmentation while criticized for its prohibitive computation and GPU memory occupation. In this paper, we present Asymmetric Non-local Neural Network to semantic segmentation, which has two prominent components: Asymmetric Pyramid Non-local Block (APNB) and Asymmetric Fusion Non-local Block (AFNB). APNB leverages a pyramid sampling module into the non-local block to largely reduce the computation and memory consumption without sacrificing the performance. AFNB is adapted from APNB to fuse the features of different levels under a sufficient consideration of long range dependencies and thus considerably improves the performance. Extensive experiments on semantic segmentation benchmarks demonstrate the effectiveness and efficiency of our work. In particular, we report the state-of-the-art performance of 81.3 mIoU on the Cityscapes test set. For a 256x128 input, APNB is around 6 times faster than a non-local block on GPU while 28 times smaller in GPU running memory occupation. Code is available at: https://github.com/MendelXu/ANN.git.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07678](http://arxiv.org/abs/1908.07678)

##### PDF
[http://arxiv.org/pdf/1908.07678](http://arxiv.org/pdf/1908.07678)

