---
layout: post
title: "Deflecting Adversarial Attacks with Pixel Deflection"
date: 2018-01-26 18:24:59
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Aaditya Prakash, Nick Moran, Solomon Garber, Antonella DiLillo, James Storer
mathjax: true
---

* content
{:toc}

##### Abstract
CNNs are poised to become integral parts of many critical systems. Despite their robustness to natural variations, image pixel values can be manipulated, via small, carefully crafted, imperceptible perturbations, to cause a model to misclassify images. We present an algorithm to process an image so that classification accuracy is significantly preserved in the presence of such adversarial manipulations. Image classifiers tend to be robust to natural noise, and adversarial attacks tend to be agnostic to object location. These observations motivate our strategy, which leverages model robustness to defend against adversarial perturbations by forcing the image to match natural image statistics. Our algorithm locally corrupts the image by redistributing pixel values via a process we term pixel deflection. A subsequent wavelet-based denoising operation softens this corruption, as well as some of the adversarial changes. We demonstrate experimentally that the combination of these techniques enables the effective recovery of the true class, against a variety of robust attacks. Our results compare favorably with current state-of-the-art defenses, without requiring retraining or modifying the CNN.

##### Abstract (translated by Google)
有线电视新闻网有望成为许多关键系统的组成部分。尽管它们对自然变化的鲁棒性，但是可以通过小的，精心设计的，不可察觉的扰动来操纵图像像素值，从而导致模型将图像错误分类。我们提出了一种算法来处理图像，以便在存在这样的对抗操纵的情况下显着保留分类准确性。图像分类器往往对自然噪声是强大的，敌对攻击往往是不可知的对象的位置。这些观察激发了我们的策略，该策略利用模型稳健性通过迫使图像匹配自然图像统计来防御对抗性扰动。我们的算法局部腐败的图像通过重新分配像素值通过一个过程我们像素偏转。随后的基于小波的去噪操作软化了这种腐败以及一些对抗性变化。我们通过实验证明，这些技术的组合能够有效地恢复真实的类，抵御各种强大的攻击。我们的研究结果与目前最先进的防御技术相媲美，不需要再培训或修改CNN。

##### URL
[http://arxiv.org/abs/1801.08926](http://arxiv.org/abs/1801.08926)

##### PDF
[http://arxiv.org/pdf/1801.08926](http://arxiv.org/pdf/1801.08926)

