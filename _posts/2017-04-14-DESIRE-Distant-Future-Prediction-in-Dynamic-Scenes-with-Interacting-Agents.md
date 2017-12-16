---
layout: post
title: "DESIRE: Distant Future Prediction in Dynamic Scenes with Interacting Agents"
date: 2017-04-14 11:15:44
categories: arXiv_CV
tags: arXiv_CV Drone RNN Prediction
author: Namhoon Lee, Wongun Choi, Paul Vernaza, Christopher B. Choy, Philip H. S. Torr, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a Deep Stochastic IOC RNN Encoderdecoder framework, DESIRE, for the task of future predictions of multiple interacting agents in dynamic scenes. DESIRE effectively predicts future locations of objects in multiple scenes by 1) accounting for the multi-modal nature of the future prediction (i.e., given the same context, future may vary), 2) foreseeing the potential future outcomes and make a strategic prediction based on that, and 3) reasoning not only from the past motion history, but also from the scene context as well as the interactions among the agents. DESIRE achieves these in a single end-to-end trainable neural network model, while being computationally efficient. The model first obtains a diverse set of hypothetical future prediction samples employing a conditional variational autoencoder, which are ranked and refined by the following RNN scoring-regression module. Samples are scored by accounting for accumulated future rewards, which enables better long-term strategic decisions similar to IOC frameworks. An RNN scene context fusion module jointly captures past motion histories, the semantic scene context and interactions among multiple agents. A feedback mechanism iterates over the ranking and refinement to further boost the prediction accuracy. We evaluate our model on two publicly available datasets: KITTI and Stanford Drone Dataset. Our experiments show that the proposed model significantly improves the prediction accuracy compared to other baseline methods.

##### Abstract (translated by Google)
我们引入了深度随机IOC RNN编码器解码器框架DESIRE，用于未来在动态场景中预测多个交互代理的任务。 DESIRE通过以下方式有效地预测了多个场景中物体的未来位置：1）考虑到未来预测的多模态特性（即，给定相同的上下文，未来可能会有所不同），2）预测潜在的未来结果，并做出基于策略的预测3）不仅从过去的运动历史，而且从场景的背景和代理人之间的相互作用推理。 DESIRE在一个单一的端到端可训练神经网络模型中实现了这些，同时在计算上是有效的。该模型首先使用条件变分自动编码器获得一组不同的假设未来预测样本，这些预测样本通过以下RNN评分回归模块进行分级和细化。通过考虑累积的未来奖励来对样本进行评分，从而实现类似于国际奥委会框架的更好的长期战略决策。 RNN场景上下文融合模块共同捕获过去的运动历史，语义场景上下文以及多个代理之间的交互。反馈机制对排序和细化进行迭代，以进一步提高预测精度。我们在两个公开可用的数据集上评估我们的模型：KITTI和Stanford Drone Dataset。我们的实验表明，与其他基线方法相比，所提出的模型显着提高了预测精度。

##### URL
[https://arxiv.org/abs/1704.04394](https://arxiv.org/abs/1704.04394)

##### PDF
[https://arxiv.org/pdf/1704.04394](https://arxiv.org/pdf/1704.04394)

