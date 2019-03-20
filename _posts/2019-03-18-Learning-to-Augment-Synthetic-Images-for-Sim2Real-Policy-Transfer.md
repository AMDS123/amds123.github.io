---
layout: post
title: "Learning to Augment Synthetic Images for Sim2Real Policy Transfer"
date: 2019-03-18 22:01:57
categories: arXiv_CV
tags: arXiv_CV Image_Caption
author: Alexander Pashevich, Robin A. M. Strudel, Igor Kalevatykh, Ivan Laptev, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
Vision and learning have made significant progress that could improve robotics policies for complex tasks and environments. Learning deep neural networks for image understanding, however, requires large amounts of domain-specific visual data. While collecting such data from real robots is possible, such an approach limits the scalability as learning policies typically requires thousands of trials. In this work we attempt to learn manipulation policies in simulated environments. Simulators enable scalability and provide access to the underlying world state during training. Policies learned in simulators, however, do not transfer well to real scenes given the domain gap between real and synthetic data. We follow recent work on domain randomization and augment synthetic images with sequences of random transformations. Our main contribution is to optimize the augmentation strategy for sim2real transfer and to enable domain-independent policy learning. We design an efficient search for depth image augmentations using object localization as a proxy task. Given the resulting sequence of random transformations, we use it to augment synthetic depth images during policy learning. Our augmentation strategy is policy-independent and enables policy learning with no real images. We demonstrate our approach to significantly improve accuracy on three manipulation tasks evaluated on a real robot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07740](http://arxiv.org/abs/1903.07740)

##### PDF
[http://arxiv.org/pdf/1903.07740](http://arxiv.org/pdf/1903.07740)

