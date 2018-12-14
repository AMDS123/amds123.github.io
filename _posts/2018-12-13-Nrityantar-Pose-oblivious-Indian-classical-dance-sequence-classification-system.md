---
layout: post
title: "Nrityantar: Pose oblivious Indian classical dance sequence classification system"
date: 2018-12-13 02:16:38
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Action_Recognition Classification Relation Recognition
author: Vinay Kaushik, Prerana Mukherjee, Brejesh Lall
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we attempt to advance the research work done in human action recognition to a rather specialized application namely Indian Classical Dance (ICD) classification. The variation in such dance forms in terms of hand and body postures, facial expressions or emotions and head orientation makes pose estimation an extremely challenging task. To circumvent this problem, we construct a pose-oblivious shape signature which is fed to a sequence learning framework. The pose signature representation is done in two-fold process. First, we represent person-pose in first frame of a dance video using symmetric Spatial Transformer Networks (STN) to extract good person object proposals and CNN-based parallel single person pose estimator (SPPE). Next, the pose basis are converted to pose flows by assigning a similarity score between successive poses followed by non-maximal suppression. Instead of feeding a simple chain of joints in the sequence learner which generally hinders the network performance we constitute a feature vector of the normalized distance vectors, flow, angles between anchor joints which captures the adjacency configuration in the skeletal pattern. Thus, the kinematic relationship amongst the body joints across the frames using pose estimation helps in better establishing the spatio-temporal dependencies. We present an exhaustive empirical evaluation of state-of-the-art deep network based methods for dance classification on ICD dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05231](http://arxiv.org/abs/1812.05231)

##### PDF
[http://arxiv.org/pdf/1812.05231](http://arxiv.org/pdf/1812.05231)

