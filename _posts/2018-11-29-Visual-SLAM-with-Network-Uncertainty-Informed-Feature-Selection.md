---
layout: post
title: "Visual SLAM with Network Uncertainty Informed Feature Selection"
date: 2018-11-29 03:53:17
categories: arXiv_CV
tags: arXiv_CV Sparse Classification SLAM
author: Pranav Ganti, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
In order to facilitate long-term localization using a visual simultaneous localization and mapping (SLAM) algorithm, careful feature selection is required such that reference points persist over long durations and the runtime and storage complexity of the algorithm remain consistent. We present SIVO (Semantically Informed Visual Odometry and Mapping), a novel information-theoretic feature selection method for visual SLAM which incorporates machine learning and neural network uncertainty into the feature selection pipeline. Our algorithm selects points which provide the highest reduction in Shannon entropy between the entropy of the current state, and the joint entropy of the state given the addition of the new feature with the classification entropy of the feature from a Bayesian neural network. This feature selection strategy generates a sparse map suitable for long-term localization, as each selected feature significantly reduces the uncertainty of the vehicle state and has been detected to be a static object (building, traffic sign, etc.) repeatedly with a high confidence. The KITTI odometry dataset is used to evaluate our method, and we also compare our results against ORB_SLAM2. Overall, SIVO performs comparably to ORB_SLAM2 (average of 0.17% translation error difference, 6.2 x 10^(-5) deg/m rotation error difference) while reducing the map size by 69%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11946](http://arxiv.org/abs/1811.11946)

##### PDF
[http://arxiv.org/pdf/1811.11946](http://arxiv.org/pdf/1811.11946)

