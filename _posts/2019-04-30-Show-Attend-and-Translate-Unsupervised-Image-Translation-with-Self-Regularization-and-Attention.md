---
layout: post
title: "Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention"
date: 2019-04-30 19:10:49
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Adversarial Segmentation Attention Detection
author: Chao Yang, Taehwan Kim, Ruizhe Wang, Hao Peng, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
Image translation between two domains is a class of problems aiming to learn mapping from an input image in the source domain to an output image in the target domain. It has been applied to numerous domains, such as data augmentation, domain adaptation, and unsupervised training. When paired training data is not accessible, image translation becomes an ill-posed problem. We constrain the problem with the assumption that the translated image needs to be perceptually similar to the original image and also appears to be drawn from the new domain, and propose a simple yet effective image translation model consisting of a single generator trained with a self-regularization term and an adversarial term. We further notice that existing image translation techniques are agnostic to the subjects of interest and often introduce unwanted changes or artifacts to the input. Thus we propose to add an attention module to predict an attention map to guide the image translation process. The module learns to attend to key parts of the image while keeping everything else unaltered, essentially avoiding undesired artifacts or changes. The predicted attention map also opens door to applications such as unsupervised segmentation and saliency detection. Extensive experiments and evaluations show that our model while being simpler, achieves significantly better performance than existing image translation methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.06195](http://arxiv.org/abs/1806.06195)

##### PDF
[http://arxiv.org/pdf/1806.06195](http://arxiv.org/pdf/1806.06195)

