---
layout: post
title: "Joint Vertebrae Identification and Localization in Spinal CT Images by Combining Short- and Long-Range Contextual Information"
date: 2018-12-09 15:25:43
categories: arXiv_CV
tags: arXiv_CV GAN CNN RNN
author: Haofu Liao, Addisu Mesfin, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic vertebrae identification and localization from arbitrary CT images is challenging. Vertebrae usually share similar morphological appearance. Because of pathology and the arbitrary field-of-view of CT scans, one can hardly rely on the existence of some anchor vertebrae or parametric methods to model the appearance and shape. To solve the problem, we argue that one should make use of the short-range contextual information, such as the presence of some nearby organs (if any), to roughly estimate the target vertebrae; due to the unique anatomic structure of the spine column, vertebrae have fixed sequential order which provides the important long-range contextual information to further calibrate the results. 
 We propose a robust and efficient vertebrae identification and localization system that can inherently learn to incorporate both the short-range and long-range contextual information in a supervised manner. To this end, we develop a multi-task 3D fully convolutional neural network (3D FCN) to effectively extract the short-range contextual information around the target vertebrae. For the long-range contextual information, we propose a multi-task bidirectional recurrent neural network (Bi-RNN) to encode the spatial and contextual information among the vertebrae of the visible spine column. We demonstrate the effectiveness of the proposed approach on a challenging dataset and the experimental results show that our approach outperforms the state-of-the-art methods by a significant margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03500](http://arxiv.org/abs/1812.03500)

##### PDF
[http://arxiv.org/pdf/1812.03500](http://arxiv.org/pdf/1812.03500)

