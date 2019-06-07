---
layout: post
title: "Improving Robustness Without Sacrificing Accuracy with Patch Gaussian Augmentation"
date: 2019-06-06 17:54:24
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Detection
author: Raphael Gontijo Lopes, Dong Yin, Ben Poole, Justin Gilmer, Ekin D. Cubuk
mathjax: true
---

* content
{:toc}

##### Abstract
Deploying machine learning systems in the real world requires both high accuracy on clean data and robustness to naturally occurring corruptions. While architectural advances have led to improved accuracy, building robust models remains challenging. Prior work has argued that there is an inherent trade-off between robustness and accuracy, which is exemplified by standard data augment techniques such as Cutout, which improves clean accuracy but not robustness, and additive Gaussian noise, which improves robustness but hurts accuracy. To overcome this trade-off, we introduce Patch Gaussian, a simple augmentation scheme that adds noise to randomly selected patches in an input image. Models trained with Patch Gaussian achieve state of the art on the CIFAR-10 and ImageNetCommon Corruptions benchmarks while also improving accuracy on clean data. We find that this augmentation leads to reduced sensitivity to high frequency noise(similar to Gaussian) while retaining the ability to take advantage of relevant high frequency information in the image (similar to Cutout). Finally, we show that Patch Gaussian can be used in conjunction with other regularization methods and data augmentation policies such as AutoAugment, and improves performance on the COCO object detection benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02611](http://arxiv.org/abs/1906.02611)

##### PDF
[http://arxiv.org/pdf/1906.02611](http://arxiv.org/pdf/1906.02611)

