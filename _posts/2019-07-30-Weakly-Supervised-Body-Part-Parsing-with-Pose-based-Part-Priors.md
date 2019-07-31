---
layout: post
title: "Weakly Supervised Body Part Parsing with Pose based Part Priors"
date: 2019-07-30 16:21:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Face Semantic_Segmentation Prediction
author: Zhengyuan Yang, Yuncheng Li, Linjie Yang, Ning Zhang, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Human body part parsing refers to the task of predicting the semantic segmentation mask for each body part. Fully supervised body part parsing methods achieve good performances, but require an enormous amount of effort to annotate part masks for training. In contrast to high annotation costs required for a limited number of part mask annotations, a large number of weak labels such as poses and full body masks already exist and contain relevant information. Motivated by the possibility of using existing weak labels, we propose the first weakly supervised body part parsing framework. The basic idea is to train a parsing network with pose generated part priors that has blank uncertain regions on estimated boundaries, and use an iterative refinement module to generate new supervision and predictions on these regions. When sufficient extra weak supervisions are available, our weakly-supervised results (62.0% mIoU) on Pascal-Person-Part are comparable to the fully supervised state-of-the-art results (63.6% mIoU). Furthermore, in the extended semi-supervised setting, the proposed framework outperforms the state-of-art methods. In addition, we show that the proposed framework can be extended to other keypoint-supervised part parsing tasks such as face parsing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13051](http://arxiv.org/abs/1907.13051)

##### PDF
[http://arxiv.org/pdf/1907.13051](http://arxiv.org/pdf/1907.13051)

