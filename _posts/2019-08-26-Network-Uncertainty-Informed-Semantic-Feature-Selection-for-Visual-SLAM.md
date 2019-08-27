---
layout: post
title: "Network Uncertainty Informed Semantic Feature Selection for Visual SLAM"
date: 2019-08-26 15:00:41
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Classification SLAM
author: Pranav Ganti, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
In order to facilitate long-term localization using a visual simultaneous localization and mapping (SLAM) algorithm, careful feature selection can help ensure that reference points persist over long durations and the runtime and storage complexity of the algorithm remain consistent. We present SIVO (Semantically Informed Visual Odometry and Mapping), a novel information-theoretic feature selection method for visual SLAM which incorporates semantic segmentation and neural network uncertainty into the feature selection pipeline. Our algorithm selects points which provide the highest reduction in Shannon entropy between the entropy of the current state and the joint entropy of the state, given the addition of the new feature with the classification entropy of the feature from a Bayesian neural network. Each selected feature significantly reduces the uncertainty of the vehicle state and has been detected to be a static object (building, traffic sign, etc.) repeatedly with a high confidence. This selection strategy generates a sparse map which can facilitate long-term localization. The KITTI odometry dataset is used to evaluate our method, and we also compare our results against ORB_SLAM2. Overall, SIVO performs comparably to the baseline method while reducing the map size by almost 70%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11946](http://arxiv.org/abs/1811.11946)

##### PDF
[http://arxiv.org/pdf/1811.11946](http://arxiv.org/pdf/1811.11946)

