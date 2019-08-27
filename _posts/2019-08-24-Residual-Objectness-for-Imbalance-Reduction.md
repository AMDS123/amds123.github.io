---
layout: post
title: "Residual Objectness for Imbalance Reduction"
date: 2019-08-24 02:24:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Optimization Detection
author: Joya Chen, Dong Liu, Bin Luo, Xuezheng Peng, Tong Xu, Enhong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
For a long time, object detectors have suffered from extreme imbalance between foregrounds and backgrounds. While several sampling/reweighting schemes have been explored to alleviate the imbalance, they are usually heuristic and demand laborious hyper-parameters tuning, which is hard to achieve the optimality. In this paper, we first reveal that such the imbalance could be addressed in a learning-based manner. Guided by this illuminating observation, we propose a novel Residual Objectness (ResObj) mechanism that addresses the imbalance by end-to-end optimization, while no further hand-crafted sampling/reweighting is required. Specifically, by applying multiple cascaded objectness-related modules with residual connections, we formulate an elegant consecutive refinement procedure for distinguishing the foregrounds from backgrounds, thereby progressively addressing the imbalance. Extensive experiments present the effectiveness of our method, as well as its compatibility and adaptivity for both region-based and one-stage detectors, namely, the RetinaNet-ResObj, YOLOv3-ResObj and FasterRCNN-ResObj achieve relative 3.6%, 3.9%, 3.2% Average Precision (AP) improvements compared with their vanilla models on COCO, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09075](http://arxiv.org/abs/1908.09075)

##### PDF
[http://arxiv.org/pdf/1908.09075](http://arxiv.org/pdf/1908.09075)

