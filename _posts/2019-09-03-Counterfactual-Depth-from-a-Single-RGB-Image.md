---
layout: post
title: "Counterfactual Depth from a Single RGB Image"
date: 2019-09-03 01:50:17
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Theerasit Issaranon, Chuhang Zou, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a method that predicts, from a single RGB image, a depth map that describes the scene when a masked object is removed - we call this "counterfactual depth" that models hidden scene geometry together with the observations. Our method works for the same reason that scene completion works: the spatial structure of objects is simple. But we offer a much higher resolution representation of space than current scene completion methods, as we operate at pixel-level precision and do not rely on a voxel representation. Furthermore, we do not require RGBD inputs. Our method uses a standard encoder-decoder architecture, and with a decoder modified to accept an object mask. We describe a small evaluation dataset that we have collected, which allows inference about what factors affect reconstruction most strongly. Using this dataset, we show that our depth predictions for masked objects are better than other baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00915](http://arxiv.org/abs/1909.00915)

##### PDF
[http://arxiv.org/pdf/1909.00915](http://arxiv.org/pdf/1909.00915)

