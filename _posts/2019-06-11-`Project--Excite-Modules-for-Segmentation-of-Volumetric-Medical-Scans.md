---
layout: post
title: "`Project & Excite' Modules for Segmentation of Volumetric Medical Scans"
date: 2019-06-11 15:21:33
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Anne-Marie Rickmann, Abhijit Guha Roy, Ignacio Sarasua, Nassir Navab, Christian Wachinger
mathjax: true
---

* content
{:toc}

##### Abstract
Fully Convolutional Neural Networks (F-CNNs) achieve state-of-the-art performance for image segmentation in medical imaging. Recently, squeeze and excitation (SE) modules and variations thereof have been introduced to recalibrate feature maps channel- and spatial-wise, which can boost performance while only minimally increasing model complexity. So far, the development of SE has focused on 2D images. In this paper, we propose `Project &amp; Excite' (PE) modules that base upon the ideas of SE and extend them to operating on 3D volumetric images. `Project &amp; Excite' does not perform global average pooling, but squeezes feature maps along different slices of a tensor separately to retain more spatial information that is subsequently used in the excitation step. We demonstrate that PE modules can be easily integrated in 3D U-Net, boosting performance by 5% Dice points, while only increasing the model complexity by 2%. We evaluate the PE module on two challenging tasks, whole-brain segmentation of MRI scans and whole-body segmentation of CT scans. Code: https://github.com/ai-med/squeeze_and_excitation

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04649](http://arxiv.org/abs/1906.04649)

##### PDF
[http://arxiv.org/pdf/1906.04649](http://arxiv.org/pdf/1906.04649)

