---
layout: post
title: "Domain Adaptive Faster R-CNN for Object Detection in the Wild"
date: 2018-03-08 18:36:22
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Object_Detection Detection
author: Yuhua Chen, Wen Li, Christos Sakaridis, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection typically assumes that training and test data are drawn from an identical distribution, which, however, does not always hold in practice. Such a distribution mismatch will lead to a significant performance drop. In this work, we aim to improve the cross-domain robustness of object detection. We tackle the domain shift on two levels: 1) the image-level shift, such as image style, illumination, etc, and 2) the instance-level shift, such as object appearance, size, etc. We build our approach based on the recent state-of-the-art Faster R-CNN model, and design two domain adaptation components, on image level and instance level, to reduce the domain discrepancy. The two domain adaptation components are based on H-divergence theory, and are implemented by learning a domain classifier in adversarial training manner. The domain classifiers on different levels are further reinforced with a consistency regularization to learn a domain-invariant region proposal network (RPN) in the Faster R-CNN model. We evaluate our newly proposed approach using multiple datasets including Cityscapes, KITTI, SIM10K, etc. The results demonstrate the effectiveness of our proposed approach for robust object detection in various domain shift scenarios.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.03243](https://arxiv.org/abs/1803.03243)

##### PDF
[https://arxiv.org/pdf/1803.03243](https://arxiv.org/pdf/1803.03243)

