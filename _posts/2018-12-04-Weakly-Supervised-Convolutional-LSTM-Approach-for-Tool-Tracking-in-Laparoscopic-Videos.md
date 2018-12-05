---
layout: post
title: "Weakly Supervised Convolutional LSTM Approach for Tool Tracking in Laparoscopic Videos"
date: 2018-12-04 12:21:13
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Tracking CNN RNN Deep_Learning Detection
author: Chinedu Innocent Nwoye, Didier Mutter, Jacques Marescaux, Nicolas Padoy
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Real-time surgical tool tracking is a core component of the future intelligent operating room (OR), because it is highly instrumental to analyze and understand the surgical activities. Current methods for surgical tool tracking in videos need to be trained on data in which the spatial position of the tools is manually annotated. Generating such training data is difficult and time-consuming. Instead, we propose to use solely binary presence annotations to train a tool tracker for laparoscopic videos. 
 Methods: The proposed approach is composed of a CNN + Convolutional LSTM (ConvLSTM) neural network trained end-to-end, but weakly supervised on tool binary presence labels only. We use the ConvLSTM to model the temporal dependencies in the motion of the surgical tools and leverage its spatio-temporal ability to smooth the class peak activations in the localization heat maps (Lh-maps). 
 Results: We build a baseline tracker on top of the CNN model and demonstrate that our approach based on the ConvLSTM outperforms the baseline in tool presence detection, spatial localization, and motion tracking by over 5.0%, 13.9%, and 12.6%, respectively. 
 Conclusions: In this paper, we demonstrate that binary presence labels are sufficient for training a deep learning tracking model using our proposed method. We also show that the ConvLSTM can leverage the spatio-temporal coherence of consecutive image frames across a surgical video to improve tool presence detection, spatial localization, and motion tracking.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01366](http://arxiv.org/abs/1812.01366)

##### PDF
[http://arxiv.org/pdf/1812.01366](http://arxiv.org/pdf/1812.01366)

