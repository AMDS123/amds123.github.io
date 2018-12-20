---
layout: post
title: "Contextual Explanation Networks"
date: 2018-12-18 22:33:40
categories: arXiv_AI
tags: arXiv_AI Text_Classification Classification Prediction
author: Maruan Al-Shedivat, Avinava Dubey, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Modern learning algorithms excel at producing accurate but complex models of the data. However, deploying such models in the real-world requires extra care: we must ensure their reliability, robustness, and absence of undesired biases. This motivates the development of models that are equally accurate but can be also easily inspected and assessed beyond their predictive performance. To this end, we introduce contextual explanation networks (CENs)---a class of architectures that learn to predict by generating and utilizing intermediate, simplified probabilistic models. Specifically, CENs generate parameters for intermediate graphical models which are further used for prediction and play the role of explanations. Contrary to the existing post-hoc model-explanation tools, CENs learn to predict and to explain jointly. Our approach offers two major advantages: (i) for each prediction, valid, instance-specific explanations are generated with no computational overhead and (ii) prediction via explanation acts as a regularizer and boosts performance in low-resource settings. We analyze the proposed framework theoretically and experimentally. Our results on image and text classification and survival analysis tasks demonstrate that CENs are not only competitive with the state-of-the-art methods but also offer additional insights behind each prediction, that are valuable for decision support. We also show that while post-hoc methods may produce misleading explanations in certain cases, CENs are always consistent and allow to detect such cases systematically.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.10301](http://arxiv.org/abs/1705.10301)

##### PDF
[http://arxiv.org/pdf/1705.10301](http://arxiv.org/pdf/1705.10301)

