---
layout: post
title: "A Non-linear Differential CNN-Rendering Module for 3D Data Enhancement"
date: 2019-04-09 18:04:47
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Yonatan Svirsky, Andrei Sharf
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce a differential rendering module which allows neural networks to efficiently process cluttered data. The module is composed of continuous piecewise differentiable functions defined as a sensor array of cells embedded in 3D space. Our module is learnable and can be easily integrated into neural networks allowing to optimize data rendering towards specific learning tasks using gradient based methods in an end-to-end fashion. Essentially, the module's sensor cells are allowed to transform independently and locally focus and sense different parts of the 3D data. Thus, through their optimization process, cells learn to focus on important parts of the data, bypassing occlusions, clutter and noise. Since sensor cells originally lie on a grid, this equals to a highly non-linear rendering of the scene into a 2D image. Our module performs especially well in presence of clutter and occlusions. Similarly, it deals well with non-linear deformations and improves classification accuracy through proper rendering of the data. In our experiments, we apply our module to demonstrate efficient localization and classification tasks in cluttered data both 2D and 3D.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04850](http://arxiv.org/abs/1904.04850)

##### PDF
[http://arxiv.org/pdf/1904.04850](http://arxiv.org/pdf/1904.04850)

