---
layout: post
title: "Meta Filter Pruning to Accelerate Deep Convolutional Neural Networks"
date: 2019-04-08 11:24:21
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Prediction Relation
author: Yang He, Ping Liu, Linchao Zhu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods usually utilize pre-defined criterions, such as p-norm, to prune unimportant filters. There are two major limitations in these methods. First, the relations of the filters are largely ignored. The filters usually work jointly to make an accurate prediction in a collaborative way. Similar filters will have equivalent effects on the network prediction, and the redundant filters can be further pruned. Second, the pruning criterion remains unchanged during training. As the network updated at each iteration, the filter distribution also changes continuously. The pruning criterions should also be adaptively switched. In this paper, we propose Meta Filter Pruning (MFP) to solve the above problems. First, as a complement to the existing p-norm criterion, we introduce a new pruning criterion considering the filter relation via filter distance. Additionally, we build a meta pruning framework for filter pruning, so that our method could adaptively select the most appropriate pruning criterion as the filter distribution changes. Experiments validate our approach on two image classification benchmarks. Notably, on ILSVRC-2012, our MFP reduces more than 50% FLOPs on ResNet-50 with only 0.44% top-5 accuracy loss.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03961](http://arxiv.org/abs/1904.03961)

##### PDF
[http://arxiv.org/pdf/1904.03961](http://arxiv.org/pdf/1904.03961)

