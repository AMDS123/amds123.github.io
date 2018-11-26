---
layout: post
title: "MURAUER: Mapping Unlabeled Real Data for Label AUstERity"
date: 2018-11-23 14:40:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation
author: Georg Poier, Michael Opitz, David Schinagl, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
Data labeling for learning 3D hand pose estimation models is a huge effort. Readily available, accurately labeled synthetic data has the potential to reduce the effort. However, to successfully exploit synthetic data, current state-of-the-art methods still require a large amount of labeled real data. In this work, we remove this requirement by learning to map from the features of real data to the features of synthetic data mainly using a large amount of synthetic and unlabeled real data. We exploit unlabeled data using two auxiliary objectives, which enforce that (i) the mapped representation is pose specific and (ii) at the same time, the distributions of real and synthetic data are aligned. While pose specifity is enforced by a self-supervisory signal requiring that the representation is predictive for the appearance from different views, distributions are aligned by an adversarial term. In this way, we can significantly improve the results of the baseline system, which does not use unlabeled data and outperform many recent approaches already with about 1% of the labeled real data. This presents a step towards faster deployment of learning based hand pose estimation, making it accessible for a larger range of applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09497](http://arxiv.org/abs/1811.09497)

##### PDF
[http://arxiv.org/pdf/1811.09497](http://arxiv.org/pdf/1811.09497)

