---
layout: post
title: "Automated crater shape retrieval using weakly-supervised deep learning"
date: 2019-06-20 20:04:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Mohamad Ali-Dib, Kristen Menou, Chenchong Zhu, Noah Hammond, Alan P. Jackson
mathjax: true
---

* content
{:toc}

##### Abstract
Crater shape determination is a complex and time consuming task that so far has evaded automation. We train a state of the art computer vision algorithm to identify craters on the moon and retrieve their sizes and shapes. The computational backbone of the model is MaskRCNN, an "instance segmentation" general framework that detects craters in an image while simultaneously producing a mask for each crater that traces its outer rim. Our post-processing pipeline then finds the closest fitting ellipse to these masks, allowing us to retrieve the crater ellipticities. Our model is able to correctly identify 87% of known craters in the holdout set, while predicting thousands of additional craters not present in our training data. Manual validation of a subset of these craters indicates that a majority of them are real, which we take as an indicator of the strength of our model in learning to identify craters, despite incomplete training data. The crater size, ellipticity, and depth distributions predicted by our model are consistent with human-generated results. The model allows us to perform a large scale search for differences in crater diameter and shape distributions between the lunar highlands and maria, and we exclude any such differences with a high statistical significance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08826](http://arxiv.org/abs/1906.08826)

##### PDF
[http://arxiv.org/pdf/1906.08826](http://arxiv.org/pdf/1906.08826)

