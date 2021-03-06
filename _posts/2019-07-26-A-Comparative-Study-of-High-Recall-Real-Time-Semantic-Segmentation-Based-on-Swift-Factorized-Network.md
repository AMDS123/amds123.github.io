---
layout: post
title: "A Comparative Study of High-Recall Real-Time Semantic Segmentation Based on Swift Factorized Network"
date: 2019-07-26 06:36:18
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Detection
author: Kaite Xiang, Kaiwei Wang, Kailun Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic Segmentation (SS) is the task to assign a semantic label to each pixel of the observed images, which is of crucial significance for autonomous vehicles, navigation assistance systems for the visually impaired, and augmented reality devices. However, there is still a long way for SS to be put into practice as there are two essential challenges that need to be addressed: efficiency and evaluation criterions for practical application. For specific application scenarios, different criterions need to be adopted. Recall rate is an important criterion for many tasks like autonomous vehicles. For autonomous vehicles, we need to focus on the detection of the traffic objects like cars, buses, and pedestrians, which should be detected with high recall rates. In other words, it is preferable to detect it wrongly than miss it, because the other traffic objects will be dangerous if the algorithm miss them and segment them as safe roadways. In this paper, our main goal is to explore possible methods to attain high recall rate. Firstly, we propose a real-time SS network named Swift Factorized Network (SFN). The proposed network is adapted from SwiftNet, whose structure is a typical U-shape structure with lateral connections. Inspired by ERFNet and Global convolution Networks (GCNet), we propose two different blocks to enlarge valid receptive field. They do not take up too much calculation resources, but significantly enhance the performance compared with the baseline network. Secondly, we explore three ways to achieve higher recall rate, i.e. loss function, classifier and decision rules. We perform a comprehensive set of experiments on state-of-the-art datasets including CamVid and Cityscapes. We demonstrate that our SS convolutional neural networks reach excellent performance. Furthermore, we make a detailed analysis and comparison of the three proposed methods on the promotion of recall rate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11394](http://arxiv.org/abs/1907.11394)

##### PDF
[http://arxiv.org/pdf/1907.11394](http://arxiv.org/pdf/1907.11394)

