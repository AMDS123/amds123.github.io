---
layout: post
title: "Improving the Harmony of the Composite Image by Spatial-Separated Attention Module"
date: 2019-07-15 10:06:42
categories: arXiv_CV
tags: arXiv_CV Attention
author: Cun Xiaodong, Pun Chi-Man
mathjax: true
---

* content
{:toc}

##### Abstract
Image composition is one of the most important applications in image processing. However, the inharmonious appearance between the spliced region and background degrade the quality of the image. Thus, we address the problem of Image Harmonization: Given a spliced image and the mask of the spliced region, we try to harmonize the "style'' of the pasted region with the background (non-spliced region). Previous approaches have been focusing on learning directly by the neural network. In this work, we start from an empirical observation: the differences can only be found in the spliced region between the spliced image and the harmonized result while they share the same semantic information and the appearance in the non-spliced region. Thus, in order to learn the feature map in the masked region and the others individually, we propose a novel attention module named Spatial-Separated Attention Module (S2AM). Furthermore, we design a novel image harmonization framework by inserting the S2AM in the coarser low-level features of the Unet structure in two different ways. Besides image harmonization, we make a big step for harmonizing the composite image without the specific mask under previous observation. The experiments show that the proposed S2AM performs better than other state-of-the-art attention modules in our task. Moreover, we demonstrate the advantages of our model against other state-of-the-art image harmonization methods via criteria from multiple points of view. Code is available at https://github.com/vinthony/s2am

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06406](http://arxiv.org/abs/1907.06406)

##### PDF
[http://arxiv.org/pdf/1907.06406](http://arxiv.org/pdf/1907.06406)

