---
layout: post
title: "Task-generalizable Adversarial Attack based on Perceptual Metric"
date: 2019-03-25 07:54:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation Classification Detection Recognition
author: Muzammal Naseer, Salman H. Khan, Shafin Rahman, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) can be easily fooled by adding human imperceptible perturbations to the images. These perturbed images are known as `adversarial examples' and pose a serious threat to security and safety critical systems. A litmus test for the strength of adversarial examples is their transferability across different DNN models in a black box setting (i.e. when the target model's architecture and parameters are not known to attacker). Current attack algorithms that seek to enhance adversarial transferability work on the decision level i.e. generate perturbations that alter the network decisions. This leads to two key limitations: (a) An attack is dependent on the task-specific loss function (e.g. softmax cross-entropy for object recognition) and therefore does not generalize beyond its original task. (b) The adversarial examples are specific to the network architecture and demonstrate poor transferability to other network architectures. We propose a novel approach to create adversarial examples that can broadly fool different networks on multiple tasks. Our approach is based on the following intuition: "Perpetual metrics based on neural network features are highly generalizable and show excellent performance in measuring and stabilizing input distortions. Therefore an ideal attack that creates maximum distortions in the network feature space should realize highly transferable examples". We report extensive experiments to show how adversarial examples generalize across multiple networks for classification, object detection and segmentation tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09020](http://arxiv.org/abs/1811.09020)

##### PDF
[http://arxiv.org/pdf/1811.09020](http://arxiv.org/pdf/1811.09020)

