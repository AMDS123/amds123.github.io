---
layout: post
title: "ADA: A Game-Theoretic Perspective on Data Augmentation for Object Detection"
date: 2017-12-12 15:20:22
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Sima Behpour, Kris M. Kitani, Brian D. Ziebart
mathjax: true
---

* content
{:toc}

##### Abstract
The use of random perturbations of ground truth data, such as random translation or scaling of bounding boxes, is a common heuristic used for data augmentation that has been shown to prevent overfitting and improve generalization. Since the design of data augmentation is largely guided by reported best practices, it is difficult to understand if those design choices are optimal. To provide a more principled perspective, we develop a game-theoretic interpretation of data augmentation in the context of object detection. We aim to find an optimal adversarial perturbations of the ground truth data (i.e., the worst case perturbations) that forces the object bounding box predictor to learn from the hardest distribution of perturbed examples for better test-time performance. We establish that the game theoretic solution, the Nash equilibrium, provides both an optimal predictor and optimal data augmentation distribution. We show that our adversarial method of training a predictor can significantly improve test time performance for the task of object detection. On the ImageNet object detection task, our adversarial approach improves performance by over 16\% compared to the best performing data augmentation method

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.07735](https://arxiv.org/abs/1710.07735)

##### PDF
[https://arxiv.org/pdf/1710.07735](https://arxiv.org/pdf/1710.07735)

