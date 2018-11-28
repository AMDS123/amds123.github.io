---
layout: post
title: "Class-Distinct and Class-Mutual Image Generation with GANs"
date: 2018-11-27 18:56:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Takuhiro Kaneko, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a new problem called class-distinct and class-mutual (DM) image generation. Typically in class-conditional image generation, it is assumed that there are no intersections between classes, and a generative model is optimized to fit discrete class labels. However, in real-world scenarios, it is often required to handle data in which class boundaries are ambiguous or unclear. For example, data crawled from the web tend to contain mislabeled data resulting from confusion. Given such data, our goal is to construct a generative model that can be controlled for class specificity, which we employ to selectively generate class-distinct and class-mutual images in a controllable manner. To achieve this, we propose novel families of generative adversarial networks (GANs) called class-mixture GAN (CMGAN) and class-posterior GAN (CPGAN). In these new networks, we redesign the generator prior and the objective function in auxiliary classifier GAN (AC-GAN), then extend these to class-mixture and arbitrary class-overlapping settings. In addition to an analysis from an information theory perspective, we empirically demonstrate the effectiveness of our proposed models for various class-overlapping settings (including synthetic to real-world settings) and tasks (i.e., image generation and image-to-image translation).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11163](http://arxiv.org/abs/1811.11163)

##### PDF
[http://arxiv.org/pdf/1811.11163](http://arxiv.org/pdf/1811.11163)

