---
layout: post
title: "Data Priming Network for Automatic Check-Out"
date: 2019-04-10 02:12:48
categories: arXiv_CV
tags: arXiv_CV Detection
author: Congcong Li, Dawei Du, Libo Zhang, Tiejian Luo, Yanjun Wu, Qi Tian, Longyin Wen, Siwei Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic Check-Out (ACO) receives increased interests in recent years. An important component of the ACO system is the visual item counting, which recognize the categories and counts of the items chosen by the customers. However, the training of such a system is challenged by the domain adaptation problem, in which the training data are images from isolated items while the testing images are for collections of items. Existing methods solve this problem with data augmentation using synthesized images, but the image synthesis leads to unreal images that affect the training process. In this paper, we propose a new data priming method to solve the domain adaptation problem. Specifically, we first use pre-augmentation data priming, in which we remove distracting background from the training images and select images with realistic view angles by the pose pruning method. In the post-augmentation step, we train a data priming network using detection and counting collaborative learning, and select more reliable images from testing data to train the final visual item tallying network. Experiments on the large scale Retail Product Checkout (RPC) dataset demonstrate the superiority of the proposed method, i.e., we achieve 80.51% checkout accuracy compared with 56.68% of the baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04978](http://arxiv.org/abs/1904.04978)

##### PDF
[http://arxiv.org/pdf/1904.04978](http://arxiv.org/pdf/1904.04978)

