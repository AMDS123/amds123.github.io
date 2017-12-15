---
layout: post
title: "Encoding Source Language with Convolutional Neural Network for Machine Translation"
date: 2015-06-08 09:04:14
categories: arXiv_CL
tags: arXiv_CL CNN Language_Model
author: Fandong Meng, Zhengdong Lu, Mingxuan Wang, Hang Li, Wenbin Jiang, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The recently proposed neural network joint model (NNJM) (Devlin et al., 2014) augments the n-gram target language model with a heuristically chosen source context window, achieving state-of-the-art performance in SMT. In this paper, we give a more systematic treatment by summarizing the relevant source information through a convolutional architecture guided by the target information. With different guiding signals during decoding, our specifically designed convolution+gating architectures can pinpoint the parts of a source sentence that are relevant to predicting a target word, and fuse them with the context of entire source sentence to form a unified representation. This representation, together with target language words, are fed to a deep neural network (DNN) to form a stronger NNJM. Experiments on two NIST Chinese-English translation tasks show that the proposed model can achieve significant improvements over the previous NNJM by up to +1.08 BLEU points on average

##### Abstract (translated by Google)
最近提出的神经网络联合模型（NNJM）（Devlin等，2014）利用启发式选择的源上下文窗口来增强n-gram目标语言模型，从而实现SMT中的最新性能。在本文中，我们通过以目标信息为导向的卷积结构来总结相关的源信息，从而给出更系统的处理。在译码过程中，通过不同的指导信号，我们专门设计的卷积+门控体系结构可以精确定位与预测目标单词相关的源语句的部分，并将它们与整个源句的语境融合，形成一个统一的表示。将这种表示与目标语言词汇一起输入到深度神经网络（DNN）中以形成更强的NNJM。对两个NIST中英文翻译任务的实验表明，所提出的模型相对于以前的NNJM，平均可以达到+1.08 BLEU点

##### URL
[https://arxiv.org/abs/1503.01838](https://arxiv.org/abs/1503.01838)

##### PDF
[https://arxiv.org/pdf/1503.01838](https://arxiv.org/pdf/1503.01838)

