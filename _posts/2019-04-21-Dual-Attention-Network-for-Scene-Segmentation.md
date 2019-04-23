---
layout: post
title: "Dual Attention Network for Scene Segmentation"
date: 2019-04-21 08:10:54
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Jun Fu, Jing Liu, Haijie Tian, Yong Li, Yongjun Bao, Zhiwei Fang, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the scene segmentation task by capturing rich contextual dependencies based on the selfattention mechanism. Unlike previous works that capture contexts by multi-scale features fusion, we propose a Dual Attention Networks (DANet) to adaptively integrate local features with their global dependencies. Specifically, we append two types of attention modules on top of traditional dilated FCN, which model the semantic interdependencies in spatial and channel dimensions respectively. The position attention module selectively aggregates the features at each position by a weighted sum of the features at all positions. Similar features would be related to each other regardless of their distances. Meanwhile, the channel attention module selectively emphasizes interdependent channel maps by integrating associated features among all channel maps. We sum the outputs of the two attention modules to further improve feature representation which contributes to more precise segmentation results. We achieve new state-of-the-art segmentation performance on three challenging scene segmentation datasets, i.e., Cityscapes, PASCAL Context and COCO Stuff dataset. In particular, a Mean IoU score of 81.5% on Cityscapes test set is achieved without using coarse data. We make the code and trained model publicly available at https://github.com/junfu1115/DANet

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.02983](http://arxiv.org/abs/1809.02983)

##### PDF
[http://arxiv.org/pdf/1809.02983](http://arxiv.org/pdf/1809.02983)

