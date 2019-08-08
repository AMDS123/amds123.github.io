---
layout: post
title: "Progressive Transfer Learning for Person Re-identification"
date: 2019-08-07 08:52:26
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN Transfer_Learning
author: Zhengxu Yu, Zhongming Jin, Long Wei, Jishun Guo, Jianqiang Huang, Deng Cai, Xiaofei He, Xian-Sheng Hua
mathjax: true
---

* content
{:toc}

##### Abstract
Model fine-tuning is a widely used transfer learning approach in person Re-identification (ReID) applications, which fine-tuning a pre-trained feature extraction model into the target scenario instead of training a model from scratch. It is challenging due to the significant variations inside the target scenario, e.g., different camera viewpoint, illumination changes, and occlusion. These variations result in a gap between the distribution of each mini-batch and the distribution of the whole dataset when using mini-batch training. In this paper, we study model fine-tuning from the perspective of the aggregation and utilization of the global information of the dataset when using mini-batch training. Specifically, we introduce a novel network structure called Batch-related Convolutional Cell (BConv-Cell), which progressively collects the global information of the dataset into a latent state and uses this latent state to rectify the extracted feature. Based on BConv-Cells, we further proposed the Progressive Transfer Learning (PTL) method to facilitate the model fine-tuning process by joint training the BConv-Cells and the pre-trained ReID model. Empirical experiments show that our proposal can improve the performance of the ReID model greatly on MSMT17, Market-1501, CUHK03 and DukeMTMC-reID datasets. The code will be released later on at \url{https://github.com/ZJULearning/PTL}

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02492](http://arxiv.org/abs/1908.02492)

##### PDF
[http://arxiv.org/pdf/1908.02492](http://arxiv.org/pdf/1908.02492)

