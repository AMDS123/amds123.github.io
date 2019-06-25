---
layout: post
title: "Dense Scale Network for Crowd Counting"
date: 2019-06-24 03:33:35
categories: arXiv_CV
tags: arXiv_CV
author: Feng Dai, Hao Liu, Yike Ma, Juan Cao, Qiang Zhao, Yongdong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd counting has been widely studied by computer vision community in recent years. Due to the large scale variation, it remains to be a challenging task. Previous methods adopt either multi-column CNN or single-column CNN with multiple branches to deal with this problem. However, restricted by the number of columns or branches, these methods can only capture a few different scales and have limited capability. In this paper, we propose a simple but effective network called DSNet for crowd counting, which can be easily trained in an end-to-end fashion. The key component of our network is the dense dilated convolution block, in which each dilation layer is densely connected with the others to preserve information from continuously varied scales. The dilation rates in dilation layers are carefully selected to prevent the block from gridding artifacts. To further enlarge the range of scales covered by the network, we cascade three blocks and link them with dense residual connections. We also introduce a novel multi-scale density level consistency loss for performance improvement. To evaluate our method, we compare it with state-of-the-art algorithms on four crowd counting datasets (ShanghaiTech, UCF-QNRF, UCF_CC_50 and UCSD). Experimental results demonstrate that DSNet can achieve the best performance and make significant improvements on all the four datasets (30% on the UCF-QNRF and UCF_CC_50, and 20% on the others).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09707](http://arxiv.org/abs/1906.09707)

##### PDF
[http://arxiv.org/pdf/1906.09707](http://arxiv.org/pdf/1906.09707)

