---
layout: post
title: "ROSA: Robust Salient Object Detection against Adversarial Attacks"
date: 2019-05-09 03:56:32
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Object_Detection Knowledge CNN Detection
author: Haofeng Li, Guanbin Li, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently salient object detection has witnessed remarkable improvement owing to the deep convolutional neural networks which can harvest powerful features for images. In particular, state-of-the-art salient object detection methods enjoy high accuracy and efficiency from fully convolutional network (FCN) based frameworks which are trained from end to end and predict pixel-wise labels. However, such framework suffers from adversarial attacks which confuse neural networks via adding quasi-imperceptible noises to input images without changing the ground truth annotated by human subjects. To our knowledge, this paper is the first one that mounts successful adversarial attacks on salient object detection models and verifies that adversarial samples are effective on a wide range of existing methods. Furthermore, this paper proposes a novel end-to-end trainable framework to enhance the robustness for arbitrary FCN-based salient object detection models against adversarial attacks. The proposed framework adopts a novel idea that first introduces some new generic noise to destroy adversarial perturbations, and then learns to predict saliency maps for input images with the introduced noise. Specifically, our proposed method consists of a segment-wise shielding component, which preserves boundaries and destroys delicate adversarial noise patterns and a context-aware restoration component, which refines saliency maps through global contrast modeling. Experimental results suggest that our proposed framework improves the performance significantly for state-of-the-art models on a series of datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03434](http://arxiv.org/abs/1905.03434)

##### PDF
[http://arxiv.org/pdf/1905.03434](http://arxiv.org/pdf/1905.03434)

