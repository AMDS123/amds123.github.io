---
layout: post
title: "Semi-Supervised and Task-Driven Data Augmentation"
date: 2019-02-11 11:21:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Krishna Chaitanya, Neerav Karani, Christian Baumgartner, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised deep learning methods for segmentation require large amounts of labelled training data, without which they are prone to overfitting, not generalizing well to unseen images. In practice, obtaining a large number of annotations from clinical experts is expensive and time-consuming. One way to address scarcity of annotated examples is data augmentation using random spatial and intensity transformations. Recently, it has been proposed to use generative models to synthesize realistic training examples, complementing the random augmentation. So far, these methods have yielded limited gains over the random augmentation. However, there is potential to improve the approach by (i) explicitly modeling deformation fields (non-affine spatial transformation) and intensity transformations and (ii) leveraging unlabelled data during the generative process. With this motivation, we propose a novel task-driven data augmentation method where to synthesize new training examples, a generative network explicitly models and applies deformation fields and additive intensity masks on existing labelled data, modeling shape and intensity variations, respectively. Crucially, the generative model is optimized to be conducive to the task, in this case segmentation, and constrained to match the distribution of images observed from labelled and unlabelled samples. Furthermore, explicit modeling of deformation fields allow synthesizing segmentation masks and images in exact correspondence by simply applying the generated transformation to an input image and the corresponding annotation. Our experiments on cardiac magnetic resonance images (MRI) showed that, for the task of segmentation in small training data scenarios, the proposed method substantially outperforms conventional augmentation techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05396](http://arxiv.org/abs/1902.05396)

##### PDF
[http://arxiv.org/pdf/1902.05396](http://arxiv.org/pdf/1902.05396)

