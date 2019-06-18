---
layout: post
title: "Improving temporal action proposal generation by using high performance computing"
date: 2019-06-15 08:35:34
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Tian Wang, Shiye Lei, Youyou Jiang, Zihang Deng, Xin Su, Hichem Snoussi, Chang Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action proposal generation is an important and challenging problem in computer vision. The biggest challenge for the task is generating proposals with precise temporal boundaries. To address these difficulties, we improved the algorithm based on boundary sensitive network. The popular temporal convolution network today overlooked the original meaning of the single video feature vector. We proposed a new temporal convolution network called Multipath Temporal ConvNet (MTN), which consists of two parts i.e. Multipath DenseNet and SE-ConvNet, can extract more useful information from the video database. Besides, to respond to the large memory occupation and a large number of videos, we abandon traditional parameter server parallel architecture and introduce high performance computing into temporal action proposal generation. To achieve this, we implement ring parallel architecture by Massage Passing Interface (MPI) acting on our method. Compared to parameter server architecture, our parallel architecture has higher efficiency on temporal action detection task with multiple GPUs, which is significant to dealing with large-scale video database. We conduct experiments on ActivityNet-1.3 and THUMOS14, where our method outperforms other state-of-art temporal action detection methods with high recall and high temporal precision.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06496](http://arxiv.org/abs/1906.06496)

##### PDF
[http://arxiv.org/pdf/1906.06496](http://arxiv.org/pdf/1906.06496)

