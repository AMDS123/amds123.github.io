---
layout: post
title: "PredRNN++: Towards A Resolution of the Deep-in-Time Dilemma in Spatiotemporal Predictive Learning"
date: 2018-11-19 02:17:17
categories: arXiv_CV
tags: arXiv_CV GAN RNN Prediction
author: Yunbo Wang, Zhifeng Gao, Mingsheng Long, Jianmin Wang, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We present PredRNN++, an improved recurrent network for video predictive learning. In pursuit of a greater spatiotemporal modeling capability, our approach increases the transition depth between adjacent states by leveraging a novel recurrent unit, which is named Causal LSTM for re-organizing the spatial and temporal memories in a cascaded mechanism. However, there is still a dilemma in video predictive learning: increasingly deep-in-time models have been designed for capturing complex variations, while introducing more difficulties in the gradient back-propagation. To alleviate this undesirable effect, we propose a Gradient Highway architecture, which provides alternative shorter routes for gradient flows from outputs back to long-range inputs. This architecture works seamlessly with causal LSTMs, enabling PredRNN++ to capture short-term and long-term dependencies adaptively. We assess our model on both synthetic and real video datasets, showing its ability to ease the vanishing gradient problem and yield state-of-the-art prediction results even in a difficult objects occlusion scenario.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.06300](http://arxiv.org/abs/1804.06300)

##### PDF
[http://arxiv.org/pdf/1804.06300](http://arxiv.org/pdf/1804.06300)

