---
layout: post
title: "Learning Implicit Fields for Generative Shape Modeling"
date: 2019-06-03 22:25:57
categories: arXiv_CV
tags: arXiv_CV GAN Face Represenation_Learning
author: Zhiqin Chen, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We advocate the use of implicit fields for learning generative models of shapes and introduce an implicit field decoder, called IM-NET, for shape generation, aimed at improving the visual quality of the generated shapes. An implicit field assigns a value to each point in 3D space, so that a shape can be extracted as an iso-surface. IM-NET is trained to perform this assignment by means of a binary classifier. Specifically, it takes a point coordinate, along with a feature vector encoding a shape, and outputs a value which indicates whether the point is outside the shape or not. By replacing conventional decoders by our implicit decoder for representation learning (via IM-AE) and shape generation (via IM-GAN), we demonstrate superior results for tasks such as generative shape modeling, interpolation, and single-view 3D reconstruction, particularly in terms of visual quality. Code and supplementary material are available at https://github.com/czq142857/implicit-decoder.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02822](http://arxiv.org/abs/1812.02822)

##### PDF
[http://arxiv.org/pdf/1812.02822](http://arxiv.org/pdf/1812.02822)

