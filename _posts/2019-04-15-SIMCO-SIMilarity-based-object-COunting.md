---
layout: post
title: "SIMCO: SIMilarity-based object COunting"
date: 2019-04-15 14:52:31
categories: arXiv_CV
tags: arXiv_CV Image_Caption Embedding
author: Marco Godi, Christian Joppi, Andrea Giachetti, Marco Cristani
mathjax: true
---

* content
{:toc}

##### Abstract
We present SIMCO, the first agnostic multi-class object counting approach. SIMCO starts by detecting foreground objects through a novel Mask RCNN-based architecture trained beforehand (just once) on a brand-new synthetic 2D shape dataset, InShape; the idea is to highlight every object resembling a primitive 2D shape (circle, square, rectangle, etc.). Each object detected is described by a low-dimensional embedding, obtained from a novel similarity-based head branch; this latter implements a triplet loss, encouraging similar objects (same 2D shape + color and scale) to map close. Subsequently, SIMCO uses this embedding for clustering, so that different types of objects can emerge and be counted, making SIMCO the very first multi-class unsupervised counter. Experiments show that SIMCO provides state-of-the-art scores on counting benchmarks and that it can also help in many challenging image understanding tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07092](http://arxiv.org/abs/1904.07092)

##### PDF
[http://arxiv.org/pdf/1904.07092](http://arxiv.org/pdf/1904.07092)

