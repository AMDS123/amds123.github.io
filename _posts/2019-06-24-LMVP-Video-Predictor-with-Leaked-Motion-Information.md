---
layout: post
title: "LMVP: Video Predictor with Leaked Motion Information"
date: 2019-06-24 17:36:27
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Dong Wang, Yitong Li, Wei Cao, Liqun Chen, Qi Wei, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Leaked Motion Video Predictor (LMVP) to predict future frames by capturing the spatial and temporal dependencies from given inputs. The motion is modeled by a newly proposed component, motion guider, which plays the role of both learner and teacher. Specifically, it {\em learns} the temporal features from real data and {\em guides} the generator to predict future frames. The spatial consistency in video is modeled by an adaptive filtering network. To further ensure the spatio-temporal consistency of the prediction, a discriminator is also adopted to distinguish the real and generated frames. Further, the discriminator leaks information to the motion guider and the generator to help the learning of motion. The proposed LMVP can effectively learn the static and temporal features in videos without the need for human labeling. Experiments on synthetic and real data demonstrate that LMVP can yield state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10101](http://arxiv.org/abs/1906.10101)

##### PDF
[http://arxiv.org/pdf/1906.10101](http://arxiv.org/pdf/1906.10101)

