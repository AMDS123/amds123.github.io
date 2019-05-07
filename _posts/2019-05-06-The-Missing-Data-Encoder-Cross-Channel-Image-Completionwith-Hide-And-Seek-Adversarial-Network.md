---
layout: post
title: "The Missing Data Encoder: Cross-Channel Image Completionwith Hide-And-Seek Adversarial Network"
date: 2019-05-06 07:51:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Represenation_Learning Quantitative
author: Arnaud Dapogny, Matthieu Cord, Patrick Perez
mathjax: true
---

* content
{:toc}

##### Abstract
Image completion is the problem of generating whole images from fragments only. It encompasses inpainting (generating a patch given its surrounding), reverse inpainting/extrapolation (generating the periphery given the central patch) as well as colorization (generating one or several channels given other ones). In this paper, we employ a deep network to perform image completion, with adversarial training as well as perceptual and completion losses, and call it the ``missing data encoder'' (MDE). We consider several configurations based on how the seed fragments are chosen. We show that training MDE for ``random extrapolation and colorization'' (MDE-REC), i.e. using random channel-independent fragments, allows a better capture of the image semantics and geometry. MDE training makes use of a novel ``hide-and-seek'' adversarial loss, where the discriminator seeks the original non-masked regions, while the generator tries to hide them. We validate our models both qualitatively and quantitatively on several datasets, showing their interest for image completion, unsupervised representation learning as well as face occlusion handling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01861](http://arxiv.org/abs/1905.01861)

##### PDF
[http://arxiv.org/pdf/1905.01861](http://arxiv.org/pdf/1905.01861)

