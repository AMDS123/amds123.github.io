---
layout: post
title: "See far with TPNET: a Tile Processor and a CNN Symbiosis"
date: 2018-11-20 00:26:42
categories: arXiv_CV
tags: arXiv_CV Prediction Relation
author: Andrey Filippov, Oleg Dzhimiev
mathjax: true
---

* content
{:toc}

##### Abstract
Throughout the evolution of the neural networks more specialized cells were added to the set of basic building blocks. These cells aim to improve training convergence, increase the overall performance, and reduce the number of required labels, all while preserving the expressive power of the universal network. Inspired by the partitioning of the human visual perception system between the eyes and the cerebral cortex, we present TPNET, which offloads universal and application-specific CNN from the bulk processing of the high resolution pixel data and performs the translation-variant image correction while delegating all non-linear decision making to the network. 
 In this work, we explore application of TPNET to 3D perception with a narrow-baseline (0.0001-0.0025) quad stereo camera and prove that a trained network provides a disparity prediction from the 2D phase correlation output by the Tile Processor (TP) that is twice as accurate as the prediction from a carefully hand-crafted algorithm. The TP in turn reduces the dimensions of the input features of the network and provides instrument-invariant and translation-invariant data, making real-time high resolution stereo 3D perception feasible and easing the requirement to have a complete end-to-end network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08032](http://arxiv.org/abs/1811.08032)

##### PDF
[http://arxiv.org/pdf/1811.08032](http://arxiv.org/pdf/1811.08032)

