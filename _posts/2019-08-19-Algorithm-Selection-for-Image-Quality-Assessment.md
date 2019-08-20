---
layout: post
title: "Algorithm Selection for Image Quality Assessment"
date: 2019-08-19 16:15:22
categories: arXiv_CV
tags: arXiv_CV QA
author: Markus Wagner, Hanhe Lin, Shujun Li, Dietmar Saupe
mathjax: true
---

* content
{:toc}

##### Abstract
Subjective perceptual image quality can be assessed in lab studies by human observers. Objective image quality assessment (IQA) refers to algorithms for estimation of the mean subjective quality ratings. Many such methods have been proposed, both for blind IQA in which no original reference image is available as well as for the full-reference case. We compared 8 state-of-the-art algorithms for blind IQA and showed that an oracle, able to predict the best performing method for any given input image, yields a hybrid method that could outperform even the best single existing method by a large margin. In this contribution we address the research question whether established methods to learn such an oracle can improve blind IQA. We applied AutoFolio, a state-of-the-art system that trains an algorithm selector to choose a well-performing algorithm for a given instance. We also trained deep neural networks to predict the best method. Our results did not give a positive answer, algorithm selection did not yield a significant improvement over the single best method. Looking into the results in depth, we observed that the noise in images may have played a role in why our trained classifiers could not predict the oracle. This motivates the consideration of noisiness in IQA methods, a property that has so far not been observed and that opens up several interesting new research questions and applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06911](http://arxiv.org/abs/1908.06911)

##### PDF
[http://arxiv.org/pdf/1908.06911](http://arxiv.org/pdf/1908.06911)

