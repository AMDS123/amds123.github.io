---
layout: post
title: "Real time backbone for semantic segmentation"
date: 2019-03-16 13:51:15
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Deep_Learning
author: Zhengeng Yang, Hongshan Yu, Qiang Fu, Wei Sun, Wenyan Jia, Mingui Sun, Zhi-Hong Mao
mathjax: true
---

* content
{:toc}

##### Abstract
The rapid development of autonomous driving in recent years presents lots of challenges for scene understanding. As an essential step towards scene understanding, semantic segmentation thus received lots of attention in past few years. Although deep learning based state-of-the-arts have achieved great success in improving the segmentation accuracy, most of them suffer from an inefficiency problem and can hardly applied to practical applications. In this paper, we systematically analyze the computation cost of Convolutional Neural Network(CNN) and found that the inefficiency of CNN is mainly caused by its wide structure rather than the deep structure. In addition, the success of pruning based model compression methods proved that there are many redundant channels in CNN. Thus, we designed a very narrow while deep backbone network to improve the efficiency of semantic segmentation. By casting our network to FCN32 segmentation architecture, the basic structure of most segmentation methods, we achieved 60.6\% mIoU on Cityscape val dataset with 54 frame per seconds(FPS) on $1024\times2048$ inputs, which already outperforms one of the earliest real time deep learning based segmentation methods: ENet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06922](http://arxiv.org/abs/1903.06922)

##### PDF
[http://arxiv.org/pdf/1903.06922](http://arxiv.org/pdf/1903.06922)

