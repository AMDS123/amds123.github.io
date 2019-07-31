---
layout: post
title: "Extended 2D Consensus Hippocampus Segmentation"
date: 2019-07-29 20:21:52
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Diedre Carmo, Bruna Silva, Clarissa Yasuda, Let&#xed;cia Rittner, Roberto Lotufo
mathjax: true
---

* content
{:toc}

##### Abstract
Hippocampus segmentation plays a key role in diagnosing various brain disorders such as Alzheimer's disease, epilepsy, multiple sclerosis, cancer, depression and others. Nowadays, segmentation is still mainly performed manually by specialists. Segmentation done by experts is considered to be a gold-standard when evaluating automated methods, buts it is a time consuming and arduos task, requiring specialized personnel. In recent years, efforts have been made to achieve reliable automated segmentation. For years the best performing authomatic methods were multi atlas based with around 80-85% Dice coefficient and very time consuming, but machine learning methods are recently rising with promising time and accuracy performance. A method for volumetric hippocampus segmentation is presented, based on the consensus of tri-planar U-Net inspired fully convolutional networks (FCNNs), with some modifications, including residual connections, VGG weight transfers, batch normalization and a patch extraction technique employing data from neighbor patches. A study on the impact of our modifications to the classical U-Net architecture was performed. Our method achieves cutting edge performance in our dataset, with around 96% volumetric Dice accuracy in our test data. In a public validation dataset, HARP, we achieve 87.48% DICE. GPU execution time is in the order of seconds per volume, and source code is publicly available. Also, masks are shown to be similar to other recent state-of-the-art hippocampus segmentation methods in a third dataset, without manual annotations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04487](http://arxiv.org/abs/1902.04487)

##### PDF
[http://arxiv.org/pdf/1902.04487](http://arxiv.org/pdf/1902.04487)

