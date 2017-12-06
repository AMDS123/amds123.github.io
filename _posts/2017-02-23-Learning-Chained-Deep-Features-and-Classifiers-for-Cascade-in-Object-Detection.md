---
layout: post
title: "Learning Chained Deep Features and Classifiers for Cascade in Object Detection"
date: 2017-02-23 00:40:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Wanli Ouyang, Ku Wang, Xin Zhu, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Cascade is a widely used approach that rejects obvious negative samples at early stages for learning better classifier and faster inference. This paper presents chained cascade network (CC-Net). In this CC-Net, the cascaded classifier at a stage is aided by the classification scores in previous stages. Feature chaining is further proposed so that the feature learning for the current cascade stage uses the features in previous stages as the prior information. The chained ConvNet features and classifiers of multiple stages are jointly learned in an end-to-end network. In this way, features and classifiers at latter stages handle more difficult samples with the help of features and classifiers in previous stages. It yields consistent boost in detection performance on benchmarks like PASCAL VOC 2007 and ImageNet. Combined with better region proposal, CC-Net leads to state-of-the-art result of 81.1% mAP on PASCAL VOC 2007.

##### Abstract (translated by Google)
级联是一种广泛使用的方法，可以在早期阶段拒绝明显的负面样本，以便学习更好的分类器和更快的推理。本文提出了链式级联网络（CC-Net）。在这个CC-Net中，一个阶段的级联分类器在前一阶段的分类分数的辅助下。进一步提出了特征链，使得当前级联阶段的特征学习以前一阶段的特征为先验信息。链接的ConvNet特征和多个阶段的分类器是在一个端到端的网络中共同学习的。通过这种方式，后期阶段的特征和分类器可以处理更难的样本。它在基准测试（如PASCAL VOC 2007和ImageNet）上的检测性能持续提升。结合更好的地区建议，CC-Net在PASCAL VOC 2007上获得了81.1％的mAP的最新成果。

##### URL
[https://arxiv.org/abs/1702.07054](https://arxiv.org/abs/1702.07054)

