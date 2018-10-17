---
layout: post
title: "Realistic Adversarial Examples in 3D Meshes"
date: 2018-10-11 19:01:10
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection Recognition
author: Dawei Yang, Chaowei Xiao, Bo Li, Jia Deng, Mingyan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Highly expressive models such as deep neural networks (DNNs) have been widely applied to various applications and achieved increasing success. However, recent studies show that such machine learning models appear to be vulnerable against adversarial examples. So far adversarial examples have been heavily explored for 2D images, while few works have conducted to understand vulnerabilities of 3D objects which exist in real world, where 3D objects are projected to 2D domains by photo taking for different learning (recognition) tasks. In this paper, we consider adversarial behaviors in practical scenarios by manipulating the shape and texture of a given 3D mesh representation of an object. Our goal is to project the optimized "adversarial meshes" to 2D with a photorealistic renderer, and still able to mislead different machine learning models. Extensive experiments show that by generating unnoticeable 3D adversarial perturbation on shape or texture for a 3D mesh, the corresponding projected 2D instance can either lead classifiers to misclassify the victim object as an arbitrary malicious target, or hide any target object within the scene from object detectors. We conduct human studies to show that our optimized adversarial 3D perturbation is highly unnoticeable for human vision systems. In addition to the subtle perturbation for a given 3D mesh, we also propose to synthesize a realistic 3D mesh and put in a scene mimicking similar rendering conditions and therefore attack different machine learning models. In-depth analysis of transferability among various 3D renderers and vulnerable regions of meshes are provided to help better understand adversarial behaviors in real-world.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05206](https://arxiv.org/abs/1810.05206)

##### PDF
[https://arxiv.org/pdf/1810.05206](https://arxiv.org/pdf/1810.05206)

