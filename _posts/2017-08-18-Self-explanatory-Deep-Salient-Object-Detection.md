---
layout: post
title: "Self-explanatory Deep Salient Object Detection"
date: 2017-08-18 13:19:01
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Deep_Learning Prediction Detection
author: Huaxin Xiao, Jiashi Feng, Yunchao Wei, Maojun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Salient object detection has seen remarkable progress driven by deep learning techniques. However, most of deep learning based salient object detection methods are black-box in nature and lacking in interpretability. This paper proposes the first self-explanatory saliency detection network that explicitly exploits low- and high-level features for salient object detection. We demonstrate that such supportive clues not only significantly enhances performance of salient object detection but also gives better justified detection results. More specifically, we develop a multi-stage saliency encoder to extract multi-scale features which contain both low- and high-level saliency context. Dense short- and long-range connections are introduced to reuse these features iteratively. Benefiting from the direct access to low- and high-level features, the proposed saliency encoder can not only model the object context but also preserve the boundary. Furthermore, a self-explanatory generator is proposed to interpret how the proposed saliency encoder or other deep saliency models making decisions. The generator simulates the absence of interesting features by preventing these features from contributing to the saliency classifier and estimates the corresponding saliency prediction without these features. A comparison function, saliency explanation, is defined to measure the prediction changes between deep saliency models and corresponding generator. Through visualizing the differences, we can interpret the capability of different deep neural networks based saliency detection models and demonstrate that our proposed model indeed uses more reasonable structure for salient object detection. Extensive experiments on five popular benchmark datasets and the visualized saliency explanation demonstrate that the proposed method provides new state-of-the-art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.05595](https://arxiv.org/abs/1708.05595)

##### PDF
[https://arxiv.org/pdf/1708.05595](https://arxiv.org/pdf/1708.05595)

