---
layout: post
title: "Graph Convolutional Label Noise Cleaner: Train a Plug-and-play Action Classifier for Anomaly Detection"
date: 2019-03-18 05:07:09
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised CNN Prediction Detection
author: Jia-Xing Zhong, Nannan Li, Weijie Kong, Shan Liu, Thomas H. Li, Ge Li
mathjax: true
---

* content
{:toc}

##### Abstract
Video anomaly detection under weak labels is formulated as a typical multiple-instance learning problem in previous works. In this paper, we provide a new perspective, i.e., a supervised learning task under noisy labels. In such a viewpoint, as long as cleaning away label noise, we can directly apply fully supervised action classifiers to weakly supervised anomaly detection, and take maximum advantage of these well-developed classifiers. For this purpose, we devise a graph convolutional network to correct noisy labels. Based upon feature similarity and temporal consistency, our network propagates supervisory signals from high-confidence snippets to low-confidence ones. In this manner, the network is capable of providing cleaned supervision for action classifiers. During the test phase, we only need to obtain snippet-wise predictions from the action classifier without any extra post-processing. Extensive experiments on 3 datasets at different scales with 2 types of action classifiers demonstrate the efficacy of our method. Remarkably, we obtain the frame-level AUC score of 82.12% on UCF-Crime.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07256](http://arxiv.org/abs/1903.07256)

##### PDF
[http://arxiv.org/pdf/1903.07256](http://arxiv.org/pdf/1903.07256)

