---
layout: post
title: "Progressive Joint Modeling in Unsupervised Single-channel Overlapped Speech Recognition"
date: 2017-10-20 03:06:23
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Transfer_Learning Recognition
author: Zhehuai Chen, Jasha Droppo, Jinyu Li, Wayne Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised single-channel overlapped speech recognition is one of the hardest problems in automatic speech recognition (ASR). Permutation invariant training (PIT) is a state of the art model-based approach, which applies a single neural network to solve this single-input, multiple-output modeling problem. We propose to advance the current state of the art by imposing a modular structure on the neural network, applying a progressive pretraining regimen, and improving the objective function with transfer learning and a discriminative training criterion. The modular structure splits the problem into three sub-tasks: frame-wise interpreting, utterance-level speaker tracing, and speech recognition. The pretraining regimen uses these modules to solve progressively harder tasks. Transfer learning leverages parallel clean speech to improve the training targets for the network. Our discriminative training formulation is a modification of standard formulations, that also penalizes competing outputs of the system. Experiments are conducted on the artificial overlapped Switchboard and hub5e-swb dataset. The proposed framework achieves over 30% relative improvement of WER over both a strong jointly trained system, PIT for ASR, and a separately optimized system, PIT for speech separation with clean speech ASR model. The improvement comes from better model generalization, training efficiency and the sequence level linguistic knowledge integration.

##### Abstract (translated by Google)
无监督单通道重叠语音识别是自动语音识别（ASR）中最难的问题之一。置换不变性训练（PIT）是一种基于模型的方法，它采用单个神经网络来解决单输入多输出建模问题。我们提出通过在神经网络上施加模块化结构来推进现有技术，采用渐进式训练方案，并利用转移学习和有区别的训练标准来改善目标函数。模块化结构将问题分解为三个子任务：逐帧解释，话语级别的说话者跟踪和语音识别。预训练方案使用这些模块来解决逐渐困难的任务。转移学习利用并行清理语音来改善网络的培训目标。我们的区别培训配方是对标准配方的修改，也会对系统的竞争产出进行惩罚。实验是在人工重叠的交换机和hub5e-swb数据集上进行的。所提出的框架相对于强大的联合训练系统，针对ASR的PIT以及单独优化的系统PIT（用于干净语音ASR模型的语音分离）实现了超过30％的WER的相对改进。改进来自更好的模型泛化，训练效率和序列层面的语言知识整合。

##### URL
[https://arxiv.org/abs/1707.07048](https://arxiv.org/abs/1707.07048)

##### PDF
[https://arxiv.org/pdf/1707.07048](https://arxiv.org/pdf/1707.07048)

