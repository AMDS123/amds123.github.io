---
layout: post
title: "A Main/Subsidiary Network Framework for Simplifying Binary Neural Network"
date: 2018-12-11 03:55:00
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Prediction
author: Yinghao Xu, Xin Dong, Yudian Li, Hao Su
mathjax: true
---

* content
{:toc}

##### Abstract
To reduce memory footprint and run-time latency, techniques such as neural network pruning and binarization have been explored separately. However, it is unclear how to combine the best of the two worlds to get extremely small and efficient models. In this paper, we, for the first time, define the filter-level pruning problem for binary neural networks, which cannot be solved by simply migrating existing structural pruning methods for full-precision models. A novel learning-based approach is proposed to prune filters in our main/subsidiary network framework, where the main network is responsible for learning representative features to optimize the prediction performance, and the subsidiary component works as a filter selector on the main network. To avoid gradient mismatch when training the subsidiary component, we propose a layer-wise and bottom-up scheme. We also provide the theoretical and experimental comparison between our learning-based and greedy rule-based methods. Finally, we empirically demonstrate the effectiveness of our approach applied on several binary models, including binarized NIN, VGG-11, and ResNet-18, on various image classification datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04210](http://arxiv.org/abs/1812.04210)

##### PDF
[http://arxiv.org/pdf/1812.04210](http://arxiv.org/pdf/1812.04210)

