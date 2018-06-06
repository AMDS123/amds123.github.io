---
layout: post
title: "SoPhie: An Attentive GAN for Predicting Paths Compliant to Social and Physical Constraints"
date: 2018-06-05 03:49:46
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Attention GAN Prediction
author: Amir Sadeghian, Vineet Kosaraju, Ali Sadeghian, Noriaki Hirose, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
We are witnessing an increasing growth of autonomous platforms such as self-driving cars and social robots around us. These mobile machines need to navigate dynamic human environments safely and in a socially acceptable way. Hence, understanding the human behavior and the physical constraints of the environment is crucial. To address the task of path prediction for multiple interacting agents in a scene, we present SoPhie; an interpretable framework based on Generative Adversarial Network (GAN). Sophie leverages two sources of information: the past trajectory of all the agents in the scene and a wide top-view image of the navigation scene. Our approach combines a physical attention mechanism with a social attention mechanism. The physical attention component helps the model to learn where to look in a large scene and extract the most salient parts of the image relevant to the path. Whereas, the social attention component is able to aggregate information across different involved agents and extract the most important trajectory information from the surrounding agents, enabling our method to predict socially aware paths. SoPhie is able to capture the multi-modal nature of the future prediction: given the history of trajectories and a navigation scene, there can be multiple acceptable paths in the future. Through experiments on several trajectory forecasting benchmarks, we show that SoPhie outperforms prior work in terms of accuracy, while predicting physically appropriate paths. We also show that SoPhie is able to classify traversable vs non-traversable locations in a scene.

##### Abstract (translated by Google)
我们目睹了自主驾驶汽车和社交机器人等自主平台的增长。这些移动机器需要安全地以社会可接受的方式驾驶动态人类环境。因此，了解人类行为和环境的物理限制至关重要。为了解决场景中多个交互代理的路径预测任务，我们提出了SoPhie;基于生成敌对网络（GAN）的可解释框架。索菲利用两种信息来源：场景中所有代理的过去轨迹和导航场景的广角顶视图。我们的方法将身体关注机制与社会关注机制相结合。身体关注组件帮助模型学习在大场景中查看哪里以及提取与路径相关的图像中最显着的部分。而社交关注组件能够将信息聚合到不同的相关代理上，并从周围代理中提取最重要的轨迹信息，从而使我们的方法能够预测社交意识路径。 SoPhie能够捕捉未来预测的多模态特性：考虑到轨迹和导航场景的历史，未来可能有多条可接受的路径。通过对几个轨迹预测基准的实验，我们证明了SoPhie在精度方面胜过了之前的工作，同时预测了物理上合适的路径。我们还表明，SoPhie能够对场景中的可穿越位置和不可穿越位置进行分类。

##### URL
[http://arxiv.org/abs/1806.01482](http://arxiv.org/abs/1806.01482)

##### PDF
[http://arxiv.org/pdf/1806.01482](http://arxiv.org/pdf/1806.01482)

