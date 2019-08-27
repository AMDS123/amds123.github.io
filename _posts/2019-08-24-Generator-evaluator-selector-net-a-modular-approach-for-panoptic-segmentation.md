---
layout: post
title: "Generator evaluator-selector net: a modular approach for panoptic segmentation"
date: 2019-08-24 09:01:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Sagi Eppel, Aspuru-Guzik
mathjax: true
---

* content
{:toc}

##### Abstract
In machine learning and other fields, suggesting a good solution to a problem is usually a harder task than evaluating the quality of such a solution. This asymmetry is the basis for a large number of selection oriented methods that use a generator system to guess a set of solutions and an evaluator system to rank and select the best solutions. This work examines the use of this approach to the problem of image segmentation. The generator/evaluator approach for this case consists of two independent convolutional neural nets: a generator net that suggests variety segments corresponding to objects and distinct regions in the image and an evaluator net that chooses the best segments to be merged into the segmentation map. The result is a trial and error evolutionary approach in which a generator that guesses segments with low average accuracy, but with wide variability, can still produce good results when coupled with an accurate evaluator. Generating and evaluating each segment separately is essential in this case since it demands exponentially fewer guesses compared to a system that guesses and evaluates the full segmentation map in each try. Another form of modularity used in this system is separating the segmentation and classification into independent neural nets. This allows the segmentation to be class agnostic and hence capable of segmenting unfamiliar categories that were not part of the training set. The method was examined on the COCO Panoptic segmentation benchmark and gave competitive results to the standard semantic segmentation and instance segmentation methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09108](http://arxiv.org/abs/1908.09108)

##### PDF
[http://arxiv.org/pdf/1908.09108](http://arxiv.org/pdf/1908.09108)

