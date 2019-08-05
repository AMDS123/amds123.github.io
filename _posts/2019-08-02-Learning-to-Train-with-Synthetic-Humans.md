---
layout: post
title: "Learning to Train with Synthetic Humans"
date: 2019-08-02 17:49:30
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation
author: David T. Hoffmann, Dimitrios Tzionas, Micheal J. Black, Siyu Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks need big annotated datasets for training. However, manual annotation can be too expensive or even unfeasible for certain tasks, like multi-person 2D pose estimation with severe occlusions. A remedy for this is synthetic data with perfect ground truth. Here we explore two variations of synthetic data for this challenging problem; a dataset with purely synthetic humans and a real dataset augmented with synthetic humans. We then study which approach better generalizes to real data, as well as the influence of virtual humans in the training loss. Using the augmented dataset, without considering synthetic humans in the loss, leads to the best results. We observe that not all synthetic samples are equally informative for training, while the informative samples are different for each training stage. To exploit this observation, we employ an adversarial student-teacher framework; the teacher improves the student by providing the hardest samples for its current state as a challenge. Experiments show that the student-teacher framework outperforms normal training on the purely synthetic dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00967](http://arxiv.org/abs/1908.00967)

##### PDF
[http://arxiv.org/pdf/1908.00967](http://arxiv.org/pdf/1908.00967)

