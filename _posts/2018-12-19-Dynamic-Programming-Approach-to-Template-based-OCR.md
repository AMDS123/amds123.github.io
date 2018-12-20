---
layout: post
title: "Dynamic Programming Approach to Template-based OCR"
date: 2018-12-19 13:22:00
categories: arXiv_CV
tags: arXiv_CV OCR Segmentation Recognition
author: M.A. Povolotskiy, D.V. Tropin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a dynamic programming solution to the template-based recognition task in OCR case. We formulate a problem of optimal position search for complex objects consisting of parts forming a sequence. We limit the distance between every two adjacent elements with predefined upper and lower thresholds. We choose the sum of penalties for each part in given position as a function to be minimized. We show that such a choice of restrictions allows a faster algorithm to be used than the one for the general form of deformation penalties. We named this algorithm Dynamic Squeezeboxes Packing (DSP) and applied it to solve the two OCR problems: text fields extraction from an image of document Visual Inspection Zone (VIZ) and license plate segmentation. The quality and the performance of resulting solutions were experimentally proved to meet the requirements of the state-of-the-art industrial recognition systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07933](http://arxiv.org/abs/1812.07933)

##### PDF
[http://arxiv.org/pdf/1812.07933](http://arxiv.org/pdf/1812.07933)

