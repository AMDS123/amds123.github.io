---
layout: post
title: "Active Long Term Memory Networks"
date: 2016-06-07 23:43:42
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Inference Deep_Learning Memory_Networks Recognition
author: Tommaso Furlanello, Jiaping Zhao, Andrew M. Saxe, Laurent Itti, Bosco S. Tjan
mathjax: true
---

* content
{:toc}

##### Abstract
Continual Learning in artificial neural networks suffers from interference and forgetting when different tasks are learned sequentially. This paper introduces the Active Long Term Memory Networks (A-LTM), a model of sequential multi-task deep learning that is able to maintain previously learned association between sensory input and behavioral output while acquiring knew knowledge. A-LTM exploits the non-convex nature of deep neural networks and actively maintains knowledge of previously learned, inactive tasks using a distillation loss. Distortions of the learned input-output map are penalized but hidden layers are free to transverse towards new local optima that are more favorable for the multi-task objective. We re-frame the McClelland's seminal Hippocampal theory with respect to Catastrophic Inference (CI) behavior exhibited by modern deep architectures trained with back-propagation and inhomogeneous sampling of latent factors across epochs. We present empirical results of non-trivial CI during continual learning in Deep Linear Networks trained on the same task, in Convolutional Neural Networks when the task shifts from predicting semantic to graphical factors and during domain adaptation from simple to complex environments. We present results of the A-LTM model's ability to maintain viewpoint recognition learned in the highly controlled iLab-20M dataset with 10 object categories and 88 camera viewpoints, while adapting to the unstructured domain of Imagenet with 1,000 object categories.

##### Abstract (translated by Google)
人工神经网络中的连续学习在顺序学习不同任务时受到干扰和遗忘。本文介绍了主动式长期记忆网络（A-LTM），它是一种连续的多任务深度学习模式，能够在获取知识的同时保持之前学习的感官输入与行为输出之间的关联。 A-LTM利用深度神经网络的非凸性质，并利用蒸馏损失主动地保持以前学习的非活动任务的知识。学习到的输入输出图的变形是受到惩罚的，但是隐藏层可以自由地转向新的局部最优点，这对于多任务目标更有利。我们重新塑造麦克莱兰的开创性的海马理论，就现代深层结构展示的灾难性推理（CI）行为进行反向传播和跨时代潜在因子不均匀采样训练。在卷积神经网络中，当任务从预测语义转变为图形因素时，以及在从简单到复杂的环境的领域适应过程中，我们给出了在同一任务训练的深度线性网络中连续学习期间非平凡CI的实证结果。我们给出了在具有10个对象类别和88个相机视点的高度控制的iLab-20M数据集中学习的A-LTM模型保持视点识别的能​​力的结果，同时适应1000个对象类别的Imagenet的非结构化域。

##### URL
[https://arxiv.org/abs/1606.02355](https://arxiv.org/abs/1606.02355)

##### PDF
[https://arxiv.org/pdf/1606.02355](https://arxiv.org/pdf/1606.02355)

