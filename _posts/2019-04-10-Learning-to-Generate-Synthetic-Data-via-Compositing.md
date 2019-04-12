---
layout: post
title: "Learning to Generate Synthetic Data via Compositing"
date: 2019-04-10 23:22:09
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Classification Detection
author: Shashank Tripathi, Siddhartha Chandra, Amit Agrawal, Ambrish Tyagi, James M. Rehg, Visesh Chari
mathjax: true
---

* content
{:toc}

##### Abstract
We present a task-aware approach to synthetic data generation. Our framework employs a trainable synthesizer network that is optimized to produce meaningful training samples by assessing the strengths and weaknesses of a `target' network. The synthesizer and target networks are trained in an adversarial manner wherein each network is updated with a goal to outdo the other. Additionally, we ensure the synthesizer generates realistic data by pairing it with a discriminator trained on real-world images. Further, to make the target classifier invariant to blending artefacts, we introduce these artefacts to background regions of the training images so the target does not over-fit to them. 
 We demonstrate the efficacy of our approach by applying it to different target networks including a classification network on AffNIST, and two object detection networks (SSD, Faster-RCNN) on different datasets. On the AffNIST benchmark, our approach is able to surpass the baseline results with just half the training examples. On the VOC person detection benchmark, we show improvements of up to 2.7% as a result of our data augmentation. Similarly on the GMU detection benchmark, we report a performance boost of 3.5% in mAP over the baseline method, outperforming the previous state of the art approaches by up to 7.5% on specific categories.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05475](http://arxiv.org/abs/1904.05475)

##### PDF
[http://arxiv.org/pdf/1904.05475](http://arxiv.org/pdf/1904.05475)

