---
layout: post
title: "Decoupled Classification Refinement: Hard False Positive Suppression for Object Detection"
date: 2018-10-05 19:34:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Classification Detection
author: Bowen Cheng, Yunchao Wei, Honghui Shi, Rogerio Feris, Jinjun Xiong, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we analyze failure cases of state-of-the-art detectors and observe that most hard false positives result from classification instead of localization and they have a large negative impact on the performance of object detectors. We conjecture there are three factors: (1) Shared feature representation is not optimal due to the mismatched goals of feature learning for classification and localization; (2) multi-task learning helps, yet optimization of the multi-task loss may result in sub-optimal for individual tasks; (3) large receptive field for different scales leads to redundant context information for small objects. We demonstrate the potential of detector classification power by a simple, effective, and widely-applicable Decoupled Classification Refinement (DCR) network. In particular, DCR places a separate classification network in parallel with the localization network (base detector). With ROI Pooling placed on the early stage of the classification network, we enforce an adaptive receptive field in DCR. During training, DCR samples hard false positives from the base detector and trains a strong classifier to refine classification results. During testing, DCR refines all boxes from the base detector. Experiments show competitive results on PASCAL VOC and COCO without any bells and whistles. Our codes are available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04002](https://arxiv.org/abs/1810.04002)

##### PDF
[https://arxiv.org/pdf/1810.04002](https://arxiv.org/pdf/1810.04002)

