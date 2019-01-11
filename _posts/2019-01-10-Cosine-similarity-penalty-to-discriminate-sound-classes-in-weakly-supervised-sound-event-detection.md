---
layout: post
title: "Cosine-similarity penalty to discriminate sound classes in weakly-supervised sound event detection"
date: 2019-01-10 13:21:06
categories: arXiv_SD
tags: arXiv_SD Attention CNN Classification Prediction Detection
author: Thomas Pellegrini, Léo Cances
mathjax: true
---

* content
{:toc}

##### Abstract
The design of new methods and models when only weakly-labeled data are available is of paramount importance in order to reduce the costs of manual annotation and the considerable human effort associated with it. In this work, we address Sound Event Detection in the case where a weakly annotated dataset is available for training. The weak annotations provide tags of audio events but do not provide temporal boundaries. The objective is twofold: 1) audio tagging, i.e. multi-label classification at recording level, 2) sound event detection, i.e. localization of the event boundaries within the recordings. This work focuses mainly on the second objective. We explore an approach inspired by Multiple Instance Learning, in which we train a convolutional recurrent neural network to give predictions at frame-level, using a custom loss function based on the weak labels and the statistics of the frame-based predictions. Since some sound classes cannot be distinguished with this approach, we improve the method by penalizing similarity between the predictions of the positive classes during training. On the test set used in the DCASE 2018 challenge, consisting of 288 recordings and 10 sound classes, the addition of a penalty resulted in a localization F-score of 33.42%, and brought more than 25% relative improvement compared to not using the penalty. The approach also outperformed a false strong labeling baseline and an attention-based model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.03146](https://arxiv.org/abs/1901.03146)

##### PDF
[https://arxiv.org/pdf/1901.03146](https://arxiv.org/pdf/1901.03146)

