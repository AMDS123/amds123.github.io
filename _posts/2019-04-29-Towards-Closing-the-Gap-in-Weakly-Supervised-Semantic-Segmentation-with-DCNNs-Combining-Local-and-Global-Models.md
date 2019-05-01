---
layout: post
title: "Towards Closing the Gap in Weakly Supervised Semantic Segmentation with DCNNs: Combining Local and Global Models"
date: 2019-04-29 22:39:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Semantic_Segmentation
author: Christoph Mayer, Radu Timofte, Gr&#xe9;gory Paul
mathjax: true
---

* content
{:toc}

##### Abstract
Generating training sets for deep convolutional neural networks (DCNNs) is a bottleneck for modern real-world applications. This is a demanding task for applications where annotating training data is costly, such as in semantic segmentation. In the literature, there is still a gap between the performance achieved by a network trained on full and on weak annotations. In this paper, we establish a strategy to measure this gap and to identify the ingredients necessary to reduce it. 
 On scribbles, we establish new state-of-the-art results: we obtain a mIoU of 75.6% without, and 75.7% with CRF post-processing. We reduce the gap by 64.2% whereas the current state-of-the-art reduces it only by 57.5%. Thanks to a systematic study of the different ingredients involved in the weakly supervised scenario and an original experimental strategy, we unravel a counter-intuitive mechanism that is simple and amenable to generalisations to other weakly-supervised scenarios: averaging poor local predicted annotations with the baseline ones and reuse them for training a DCNN yields new state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.01625](http://arxiv.org/abs/1808.01625)

##### PDF
[http://arxiv.org/pdf/1808.01625](http://arxiv.org/pdf/1808.01625)

