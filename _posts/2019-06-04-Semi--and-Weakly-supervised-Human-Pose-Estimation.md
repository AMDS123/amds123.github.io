---
layout: post
title: "Semi- and Weakly-supervised Human Pose Estimation"
date: 2019-06-04 13:12:28
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection
author: Norimichi Ukita, Yusuke Uematsu
mathjax: true
---

* content
{:toc}

##### Abstract
For human pose estimation in still images, this paper proposes three semi- and weakly-supervised learning schemes. While recent advances of convolutional neural networks improve human pose estimation using supervised training data, our focus is to explore the semi- and weakly-supervised schemes. Our proposed schemes initially learn conventional model(s) for pose estimation from a small amount of standard training images with human pose annotations. For the first semi-supervised learning scheme, this conventional pose model detects candidate poses in training images with no human annotation. From these candidate poses, only true-positives are selected by a classifier using a pose feature representing the configuration of all body parts. The accuracies of these candidate pose estimation and true-positive pose selection are improved by action labels provided to these images in our second and third learning schemes, which are semi- and weakly-supervised learning. While the first and second learning schemes select only poses that are similar to those in the supervised training data, the third scheme selects more true-positive poses that are significantly different from any supervised poses. This pose selection is achieved by pose clustering using outlier pose detection with Dirichlet process mixtures and the Bayes factor. The proposed schemes are validated with large-scale human pose datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01399](http://arxiv.org/abs/1906.01399)

##### PDF
[http://arxiv.org/pdf/1906.01399](http://arxiv.org/pdf/1906.01399)

