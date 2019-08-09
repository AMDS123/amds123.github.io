---
layout: post
title: "Learn to Scale: Generating Multipolar Normalized Density Maps for Crowd Counting"
date: 2019-08-08 15:56:05
categories: arXiv_CV
tags: arXiv_CV
author: Chenfeng Xu, Kai Qiu, Jianlong Fu, Song Bai, Yongchao Xu, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Dense crowd counting aims to predict thousands of human instances from an image, by calculating integrals of a density map over image pixels. Existing approaches mainly suffer from the extreme density variances. Such density pattern shift poses challenges even for multi-scale model ensembling. In this paper, we propose a simple yet effective approach to tackle this problem. First, a patch-level density map is extracted by a density estimation model and further grouped into several density levels which are determined over full datasets. Second, each patch density map is automatically normalized by an online center learning strategy with a multipolar center loss. Such a design can significantly condense the density distribution into several clusters, and enable that the density variance can be learned by a single model. Extensive experiments demonstrate the superiority of the proposed method. Our work outperforms the state-of-the-art by 4.2%, 14.3%, 27.1% and 20.1% in MAE, on ShanghaiTech Part A, ShanghaiTech Part B, UCF_CC_50 and UCF-QNRF datasets, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12428](http://arxiv.org/abs/1907.12428)

##### PDF
[http://arxiv.org/pdf/1907.12428](http://arxiv.org/pdf/1907.12428)

