---
layout: post
title: "Visual Object Tracking: The Initialisation Problem"
date: 2018-05-03 07:43:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking
author: George De Ath, Richard Everson
mathjax: true
---

* content
{:toc}

##### Abstract
Model initialisation is an important component of object tracking. Tracking algorithms are generally provided with the first frame of a sequence and a bounding box (BB) indicating the location of the object. This BB may contain a large number of background pixels in addition to the object and can lead to parts-based tracking algorithms initialising their object models in background regions of the BB. In this paper, we tackle this as a missing labels problem, marking pixels sufficiently away from the BB as belonging to the background and learning the labels of the unknown pixels. Three techniques, One-Class SVM (OC-SVM), Sampled-Based Background Model (SBBM) (a novel background model based on pixel samples), and Learning Based Digital Matting (LBDM), are adapted to the problem. These are evaluated with leave-one-video-out cross-validation on the VOT2016 tracking benchmark. Our evaluation shows both OC-SVMs and SBBM are capable of providing a good level of segmentation accuracy but are too parameter-dependent to be used in real-world scenarios. We show that LBDM achieves significantly increased performance with parameters selected by cross validation and we show that it is robust to parameter variation.

##### Abstract (translated by Google)
模型初始化是目标跟踪的重要组成部分。跟踪算法通常与序列的第一帧和指示对象位置的边界框（BB）一起提供。除了对象之外，这个BB可能包含大量的背景像素，并且可能导致基于部件的跟踪算法在BB的背景区域中初始化它们的对象模型。在本文中，我们将此视为缺失标签问题，将像素标记为远离BB，因为它属于背景并学习未知像素的标签。采用三种技术，一类SVM（OC-SVM），基于采样的背景模型（SBBM）（基于像素样本的新型背景模型）和基于学习的数字Matting（LBDM）。在VOT2016跟踪基准测试中，对这些评估结果进行了leave-one-video-out交叉验证。我们的评估显示，OC-SVM和SBBM都能够提供良好的分割准确性，但是太依赖于参数，不适用于真实世界的场景。我们展示了LBDM通过交叉验证选择的参数实现了显着提高的性能，并且我们证明它对参数变化具有鲁棒性。

##### URL
[http://arxiv.org/abs/1805.01146](http://arxiv.org/abs/1805.01146)

##### PDF
[http://arxiv.org/pdf/1805.01146](http://arxiv.org/pdf/1805.01146)

