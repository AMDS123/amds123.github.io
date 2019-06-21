---
layout: post
title: "Mask-aware networks for crowd counting"
date: 2019-06-20 02:20:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Shengqin Jiang, Xiaobo Lu, Yinjie Lei, Lingqiao Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd counting problem aims to count the number of objects within an image or a frame in the videos and is usually solved by estimating the density map generated from the object location annotations. The values in the density map, by nature, take two possible states: zero indicating no object around, a non-zero value indicating the existence of objects and the value denoting the local object density. In contrast to traditional methods which do not differentiate the density prediction of these two states, we propose to use a dedicated network branch to predict the object/non-object mask and then combine its prediction with the input image to produce the density map. Our rationale is that the mask prediction could be better modeled as a binary segmentation problem and the difficulty of estimating the density could be reduced if the mask is known. A key to the proposed scheme is the strategy of incorporating the mask prediction into the density map estimator. To this end, we study five possible solutions, and via analysis and experimental validation we identify the most effective one. Through extensive experiments on five public datasets, we demonstrate the superior performance of the proposed approach over the baselines and show that our network could achieve the state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.00039](http://arxiv.org/abs/1901.00039)

##### PDF
[http://arxiv.org/pdf/1901.00039](http://arxiv.org/pdf/1901.00039)

