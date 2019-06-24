---
layout: post
title: "Neural Sign Language Translation based on Human Keypoint Estimation"
date: 2019-06-21 06:27:34
categories: arXiv_CV
tags: arXiv_CV Attention Face
author: Sang-Ki Ko, Chang Jo Kim, Hyedong Jung, Choongsang Cho
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a sign language translation system based on human keypoint estimation. It is well-known that many problems in the field of computer vision require a massive amount of dataset to train deep neural network models. The situation is even worse when it comes to the sign language translation problem as it is far more difficult to collect high-quality training data. In this paper, we introduce the KETI (short for Korea Electronics Technology Institute) sign language dataset which consists of 14,672 videos of high resolution and quality. Considering the fact that each country has a different and unique sign language, the KETI sign language dataset can be the starting line for further research on the Korean sign language translation. Using the KETI sign language dataset, we develop a neural network model for translating sign videos into natural language sentences by utilizing the human keypoints extracted from a face, hands, and body parts. The obtained human keypoint vector is normalized by the mean and standard deviation of the keypoints and used as input to our translation model based on the sequence-to-sequence architecture. As a result, we show that our approach is robust even when the size of the training data is not sufficient. Our translation model achieves 93.28% (55.28%, respectively) translation accuracy on the validation set (test set, respectively) for 105 sentences that can be used in emergency situations. We compare several types of our neural sign translation models based on different attention mechanisms in terms of classical metrics for measuring the translation performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11436](http://arxiv.org/abs/1811.11436)

##### PDF
[http://arxiv.org/pdf/1811.11436](http://arxiv.org/pdf/1811.11436)

