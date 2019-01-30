---
layout: post
title: "Visual Rhythm Prediction with Feature-Aligning Network"
date: 2019-01-29 08:29:08
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Yutong Xie, Haiyang Wang, Yan Hao, Zihao Xu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a data-driven visual rhythm prediction method, which overcomes the previous works' deficiency that predictions are made primarily by human-crafted hard rules. In our approach, we first extract features including original frames and their residuals, optical flow, scene change, and body pose. These visual features will be next taken into an end-to-end neural network as inputs. Here we observe that there are some slight misaligning between features over the timeline and assume that this is due to the distinctions between how different features are computed. To solve this problem, the extracted features are aligned by an elaborately designed layer, which can also be applied to other models suffering from mismatched features, and boost performance. Then these aligned features are fed into sequence labeling layers implemented with BiLSTM and CRF to predict the onsets. Due to the lack of existing public training and evaluation set, we experiment on a dataset constructed by ourselves based on professionally edited Music Videos (MVs), and the F1 score of our approach reaches 79.6.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10163](http://arxiv.org/abs/1901.10163)

##### PDF
[http://arxiv.org/pdf/1901.10163](http://arxiv.org/pdf/1901.10163)

