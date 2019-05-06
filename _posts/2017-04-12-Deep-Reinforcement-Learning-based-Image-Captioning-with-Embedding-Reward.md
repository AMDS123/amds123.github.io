---
layout: post
title: "Deep Reinforcement Learning-based Image Captioning with Embedding Reward"
date: 2017-04-12 18:55:03
categories: arXiv_CV
tags: arXiv_CV Image_Caption Reinforcement_Learning Caption Embedding Prediction
author: Zhou Ren, Xiaoyu Wang, Ning Zhang, Xutao Lv, Li-Jia Li
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning is a challenging problem owing to the complexity in understanding the image content and diverse ways of describing it in natural language. Recent advances in deep neural networks have substantially improved the performance of this task. Most state-of-the-art approaches follow an encoder-decoder framework, which generates captions using a sequential recurrent prediction model. However, in this paper, we introduce a novel decision-making framework for image captioning. We utilize a "policy network" and a "value network" to collaboratively generate captions. The policy network serves as a local guidance by providing the confidence of predicting the next word according to the current state. Additionally, the value network serves as a global and lookahead guidance by evaluating all possible extensions of the current state. In essence, it adjusts the goal of predicting the correct words towards the goal of generating captions similar to the ground truth captions. We train both networks using an actor-critic reinforcement learning model, with a novel reward defined by visual-semantic embedding. Extensive experiments and analyses on the Microsoft COCO dataset show that the proposed framework outperforms state-of-the-art approaches across different evaluation metrics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.03899](https://arxiv.org/abs/1704.03899)

##### PDF
[https://arxiv.org/pdf/1704.03899](https://arxiv.org/pdf/1704.03899)

