---
layout: post
title: "MONET: Multiview Semi-supervised Keypoint Detection via Epipolar Divergence"
date: 2019-08-17 00:14:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yuan Yao, Yasamin Jafarian, Hyun Soo Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents MONET -- an end-to-end semi-supervised learning framework for a keypoint detector using multiview image streams. In particular, we consider general subjects such as non-human species where attaining a large scale annotated dataset is challenging. While multiview geometry can be used to self-supervise the unlabeled data, integrating the geometry into learning a keypoint detector is challenging due to representation mismatch. We address this mismatch by formulating a new differentiable representation of the epipolar constraint called epipolar divergence---a generalized distance from the epipolar lines to the corresponding keypoint distribution. Epipolar divergence characterizes when two view keypoint distributions produce zero reprojection error. We design a twin network that minimizes the epipolar divergence through stereo rectification that can significantly alleviate computational complexity and sampling aliasing in training. We demonstrate that our framework can localize customized keypoints of diverse species, e.g., humans, dogs, and monkeys.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.00104](http://arxiv.org/abs/1806.00104)

##### PDF
[http://arxiv.org/pdf/1806.00104](http://arxiv.org/pdf/1806.00104)

