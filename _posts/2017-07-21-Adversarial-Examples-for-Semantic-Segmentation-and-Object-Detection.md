---
layout: post
title: "Adversarial Examples for Semantic Segmentation and Object Detection"
date: 2017-07-21 17:27:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation Image_Classification Semantic_Segmentation Classification Detection Recognition
author: Cihang Xie, Jianyu Wang, Zhishuai Zhang, Yuyin Zhou, Lingxi Xie, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
It has been well demonstrated that adversarial examples, i.e., natural images with visually imperceptible perturbations added, generally exist for deep networks to fail on image classification. In this paper, we extend adversarial examples to semantic segmentation and object detection which are much more difficult. Our observation is that both segmentation and detection are based on classifying multiple targets on an image (e.g., the basic target is a pixel or a receptive field in segmentation, and an object proposal in detection), which inspires us to optimize a loss function over a set of pixels/proposals for generating adversarial perturbations. Based on this idea, we propose a novel algorithm named Dense Adversary Generation (DAG), which generates a large family of adversarial examples, and applies to a wide range of state-of-the-art deep networks for segmentation and detection. We also find that the adversarial perturbations can be transferred across networks with different training data, based on different architectures, and even for different recognition tasks. In particular, the transferability across networks with the same architecture is more significant than in other cases. Besides, summing up heterogeneous perturbations often leads to better transfer performance, which provides an effective method of black-box adversarial attack.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.08603](https://arxiv.org/abs/1703.08603)

##### PDF
[https://arxiv.org/pdf/1703.08603](https://arxiv.org/pdf/1703.08603)

