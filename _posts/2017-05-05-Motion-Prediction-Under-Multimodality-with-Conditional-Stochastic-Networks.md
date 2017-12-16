---
layout: post
title: "Motion Prediction Under Multimodality with Conditional Stochastic Networks"
date: 2017-05-05 04:19:40
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Quantitative
author: Katerina Fragkiadaki, Jonathan Huang, Alex Alemi, Sudheendra Vijayanarasimhan, Susanna Ricco, Rahul Sukthankar
mathjax: true
---

* content
{:toc}

##### Abstract
Given a visual history, multiple future outcomes for a video scene are equally probable, in other words, the distribution of future outcomes has multiple modes. Multimodality is notoriously hard to handle by standard regressors or classifiers: the former regress to the mean and the latter discretize a continuous high dimensional output space. In this work, we present stochastic neural network architectures that handle such multimodality through stochasticity: future trajectories of objects, body joints or frames are represented as deep, non-linear transformations of random (as opposed to deterministic) variables. Such random variables are sampled from simple Gaussian distributions whose means and variances are parametrized by the output of convolutional encoders over the visual history. We introduce novel convolutional architectures for predicting future body joint trajectories that outperform fully connected alternatives \cite{DBLP:journals/corr/WalkerDGH16}. We introduce stochastic spatial transformers through optical flow warping for predicting future frames, which outperform their deterministic equivalents \cite{DBLP:journals/corr/PatrauceanHC15}. Training stochastic networks involves an intractable marginalization over stochastic variables. We compare various training schemes that handle such marginalization through a) straightforward sampling from the prior, b) conditional variational autoencoders \cite{NIPS2015_5775,DBLP:journals/corr/WalkerDGH16}, and, c) a proposed K-best-sample loss that penalizes the best prediction under a fixed "prediction budget". We show experimental results on object trajectory prediction, human body joint trajectory prediction and video prediction under varying future uncertainty, validating quantitatively and qualitatively our architectural choices and training schemes.

##### Abstract (translated by Google)
考虑到视觉历史，视频场景的多个未来结果同样可能，换句话说，未来结果的分布具有多种模式。多样性是众所周知的难以处理的标准回归器或分类器：前者回归平均值，后者离散化持续的高维输出空间。在这项工作中，我们提出了通过随机性处理这种多模态的随机神经网络结构：对象，身体关节或框架的未来轨迹被表示为随机（而不是确定性）变量的深度非线性变换。这样的随机变量是从简单的高斯分布中采样的，其平均值和方差通过视觉历史上的卷积编码器的输出而被参数化。我们引入新的卷积体系结构来预测将来的身体关节轨迹，超越完全连接的选择\引用{DBLP：期刊/ corr / WalkerDGH16}。我们通过光流变形引入了随机空间变换器，用于预测未来的帧，其性能优于其确定性等价物\ cite {DBLP：journals / corr / PatrauceanHC15}。随机网络的训练涉及随机变量的难以处理的边缘化。我们比较了各种训练方案处理这种边缘化，通过a）直接采样从先前，b）有条件的变分自动编码器\ cite {NIPS2015_5775，DBLP：期刊/ corr / WalkerDGH16}，和c）提出的K-最佳样本损失在固定的“预测预算”下处罚最佳预测。我们展示了在不同的未来不确定性条件下对物体轨迹预测，人体关节轨迹预测和视频预测的实验结果，从数量和质量上验证了我们的建筑选择和训练方案。

##### URL
[https://arxiv.org/abs/1705.02082](https://arxiv.org/abs/1705.02082)

##### PDF
[https://arxiv.org/pdf/1705.02082](https://arxiv.org/pdf/1705.02082)

