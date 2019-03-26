---
layout: post
title: "Scale-Adaptive Neural Dense Features: Learning via Hierarchical Context Aggregation"
date: 2019-03-25 16:12:20
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Deep_Learning SLAM Relation
author: Jaime Spencer, Richard Bowden, Simon Hadfield
mathjax: true
---

* content
{:toc}

##### Abstract
How do computers and intelligent agents view the world around them? Feature extraction and representation constitutes one the basic building blocks towards answering this question. Traditionally, this has been done with carefully engineered hand-crafted techniques such as HOG, SIFT or ORB. However, there is no ``one size fits all'' approach that satisfies all requirements. In recent years, the rising popularity of deep learning has resulted in a myriad of end-to-end solutions to many computer vision problems. These approaches, while successful, tend to lack scalability and can't easily exploit information learned by other systems. Instead, we propose SAND features, a dedicated deep learning solution to feature extraction capable of providing hierarchical context information. This is achieved by employing sparse relative labels indicating relationships of similarity/dissimilarity between image locations. The nature of these labels results in an almost infinite set of dissimilar examples to choose from. We demonstrate how the selection of negative examples during training can be used to modify the feature space and vary it's properties. To demonstrate the generality of this approach, we apply the proposed features to a multitude of tasks, each requiring different properties. This includes disparity estimation, semantic segmentation, self-localisation and SLAM. In all cases, we show how incorporating SAND features results in better or comparable results to the baseline, whilst requiring little to no additional training. Code can be found at: https://github.com/jspenmar/SAND_features

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10427](http://arxiv.org/abs/1903.10427)

##### PDF
[http://arxiv.org/pdf/1903.10427](http://arxiv.org/pdf/1903.10427)

