---
layout: post
title: "Class-Aware Adversarial Lung Nodule Synthesis in CT Images"
date: 2018-12-28 19:33:38
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Deep_Learning
author: Jie Yang, Siqi Liu, Sasa Grbic, Arnaud Arindra Adiyoso Setio, Zhoubing Xu, Eli Gibson, Guillaume Chabin, Bogdan Georgescu, Andrew F. Laine, Dorin Comaniciu
mathjax: true
---

* content
{:toc}

##### Abstract
Though large-scale datasets are essential for training deep learning systems, it is expensive to scale up the collection of medical imaging datasets. Synthesizing the objects of interests, such as lung nodules, in medical images based on the distribution of annotated datasets can be helpful for improving the supervised learning tasks, especially when the datasets are limited by size and class balance. In this paper, we propose the class-aware adversarial synthesis framework to synthesize lung nodules in CT images. The framework is built with a coarse-to-fine patch in-painter (generator) and two class-aware discriminators. By conditioning on the random latent variables and the target nodule labels, the trained networks are able to generate diverse nodules given the same context. By evaluating on the public LIDC-IDRI dataset, we demonstrate an example application of the proposed framework for improving the accuracy of the lung nodule malignancy estimation as a binary classification problem, which is important in the lung screening scenario. We show that combining the real image patches and the synthetic lung nodules in the training set can improve the mean AUC classification score across different network architectures by 2%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11204](http://arxiv.org/abs/1812.11204)

##### PDF
[http://arxiv.org/pdf/1812.11204](http://arxiv.org/pdf/1812.11204)

