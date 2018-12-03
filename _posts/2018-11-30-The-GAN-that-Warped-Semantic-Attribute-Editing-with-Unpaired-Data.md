---
layout: post
title: "The GAN that Warped: Semantic Attribute Editing with Unpaired Data"
date: 2018-11-30 13:26:38
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Garoe Dorta, Sara Vicente, Neill D.F. Campbell, Ivor Simpson
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have recently been used to edit images with great success. However, they are often limited by only being able to work at a restricted range of resolutions. They are also so flexible that semantic face edits can often result in an unwanted loss of identity. This work proposes a model that learns how to perform semantic image edits through the application of smooth warp fields. This warp field can be efficiently predicted at a reasonably low resolution and then resampled and applied at arbitrary resolutions. Previous approaches that attempted to use warping for semantic edits required paired data, that is example images of the same object with different semantic characteristics. In contrast, we employ recent advances in Generative Adversarial Networks that allow our model to be effectively trained with unpaired data. We demonstrate the efficacy of our method for editing face images at very high resolutions (4k images) with an efficient single forward pass of a deep network at a lower resolution. We illustrate how the extent of our edits can be trivially reduced or exaggerated by scaling the predicted warp field, and we also show that our edits are substantially better at maintaining the subject's identity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12784](http://arxiv.org/abs/1811.12784)

##### PDF
[http://arxiv.org/pdf/1811.12784](http://arxiv.org/pdf/1811.12784)

