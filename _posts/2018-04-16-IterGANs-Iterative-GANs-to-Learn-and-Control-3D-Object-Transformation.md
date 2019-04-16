---
layout: post
title: "IterGANs: Iterative GANs to Learn and Control 3D Object Transformation"
date: 2018-04-16 13:08:58
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Ysbrand Galama, Thomas Mensink
mathjax: true
---

* content
{:toc}

##### Abstract
We are interested in learning visual representations which allow for 3D manipulations of visual objects based on a single 2D image. We cast this into an image-to-image transformation task, and propose Iterative Generative Adversarial Networks (IterGANs) which iteratively transform an input image into an output image. Our models learn a visual representation that can be used for objects seen in training, but also for never seen objects. Since object manipulation requires a full understanding of the geometry and appearance of the object, our IterGANs learn an implicit 3D model and a full appearance model of the object, which are both inferred from a single (test) image. Two advantages of IterGANs are that the intermediate generated images can be used for an additional supervision signal, even in an unsupervised fashion, and that the number of iterations can be used as a control signal to steer the transformation. Experiments on rotated objects and scenes show how IterGANs help with the generation process.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.05651](https://arxiv.org/abs/1804.05651)

##### PDF
[https://arxiv.org/pdf/1804.05651](https://arxiv.org/pdf/1804.05651)

