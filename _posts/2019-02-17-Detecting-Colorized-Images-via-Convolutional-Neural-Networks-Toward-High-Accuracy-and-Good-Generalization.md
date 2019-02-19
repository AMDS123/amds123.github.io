---
layout: post
title: "Detecting Colorized Images via Convolutional Neural Networks: Toward High Accuracy and Good Generalization"
date: 2019-02-17 08:40:48
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Detection
author: Weize Quan, Dong-Ming Yan, Kai Wang, Xiaopeng Zhang, Denis Pellerin
mathjax: true
---

* content
{:toc}

##### Abstract
Image colorization achieves more and more realistic results with the increasing computation power of recent deep learning techniques. It becomes more difficult to identify the fake colorized images by human eyes. In this work, we propose a novel forensic method to distinguish between natural images (NIs) and colorized images (CIs) based on convolutional neural network (CNN). Our method is able to achieve high classification accuracy and cope with the challenging scenario of blind detection, i.e., no training sample is available from "unknown" colorization algorithm that we may encounter during the testing phase. This blind detection performance can be regarded as a generalization performance. First, we design and implement a base network, which can attain better performance in terms of classification accuracy and generalization (in most cases) compared with state-of-the-art methods. Furthermore, we design a new branch, which analyzes smaller regions of extracted features, and insert it into the above base network. Consequently, our network can not only improve the classification accuracy, but also enhance the generalization in the vast majority of cases. To further improve the performance of blind detection, we propose to automatically construct negative samples through linear interpolation of paired natural and colorized images. Then, we progressively insert these negative samples into the original training dataset and continue to train the network. Experimental results demonstrate that our method can achieve stable and high generalization performance when tested against different state-of-the-art colorization algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06222](http://arxiv.org/abs/1902.06222)

##### PDF
[http://arxiv.org/pdf/1902.06222](http://arxiv.org/pdf/1902.06222)

