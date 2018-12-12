---
layout: post
title: "Loss Guided Activation for Action Recognition in Still Images"
date: 2018-12-11 02:43:45
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Deep_Learning Recognition
author: Lu Liu, Robby T. Tan, Shaodi You
mathjax: true
---

* content
{:toc}

##### Abstract
One significant problem of deep-learning based human action recognition is that it can be easily misled by the presence of irrelevant objects or backgrounds. Existing methods commonly address this problem by employing bounding boxes on the target humans as part of the input, in both training and testing stages. This requirement of bounding boxes as part of the input is needed to enable the methods to ignore irrelevant contexts and extract only human features. However, we consider this solution is inefficient, since the bounding boxes might not be available. Hence, instead of using a person bounding box as an input, we introduce a human-mask loss to automatically guide the activations of the feature maps to the target human who is performing the action, and hence suppress the activations of misleading contexts. We propose a multi-task deep learning method that jointly predicts the human action class and human location heatmap. Extensive experiments demonstrate our approach is more robust compared to the baseline methods under the presence of irrelevant misleading contexts. Our method achieves 94.06\% and 40.65\% (in terms of mAP) on Stanford40 and MPII dataset respectively, which are 3.14\% and 12.6\% relative improvements over the best results reported in the literature, and thus set new state-of-the-art results. Additionally, unlike some existing methods, we eliminate the requirement of using a person bounding box as an input during testing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04194](http://arxiv.org/abs/1812.04194)

##### PDF
[http://arxiv.org/pdf/1812.04194](http://arxiv.org/pdf/1812.04194)

