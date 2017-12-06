---
layout: post
title: "Ask, Attend and Answer: Exploring Question-Guided Spatial Attention for Visual Question Answering"
date: 2016-03-19 03:06:58
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN RNN Memory_Networks VQA
author: Huijuan Xu, Kate Saenko
---

* content
{:toc}

##### Abstract
We address the problem of Visual Question Answering (VQA), which requires joint image and language understanding to answer a question about a given photograph. Recent approaches have applied deep image captioning methods based on convolutional-recurrent networks to this problem, but have failed to model spatial inference. To remedy this, we propose a model we call the Spatial Memory Network and apply it to the VQA task. Memory networks are recurrent neural networks with an explicit attention mechanism that selects certain parts of the information stored in memory. Our Spatial Memory Network stores neuron activations from different spatial regions of the image in its memory, and uses the question to choose relevant regions for computing the answer, a process of which constitutes a single "hop" in the network. We propose a novel spatial attention architecture that aligns words with image patches in the first hop, and obtain improved results by adding a second attention hop which considers the whole question to choose visual evidence based on the results of the first hop. To better understand the inference process learned by the network, we design synthetic questions that specifically require spatial inference and visualize the attention weights. We evaluate our model on two published visual question answering datasets, DAQUAR [1] and VQA [2], and obtain improved results compared to a strong deep baseline model (iBOWIMG) which concatenates image and question features to predict the answer [3].

##### Abstract (translated by Google)
我们解决视觉问答（VQA）的问题，这需要联合图像和语言理解来回答关于给定照片的问题。最近的方法已经应用了基于卷积循环网络的深度图像字幕方法来解决这个问题，但是没有对空间推理进行建模。为了解决这个问题，我们提出了一个我们称之为空间内存网络的模型，并将其应用于VQA任务。记忆网络是具有明确注意机制的循环神经网络，用于选择存储在内存中的信息的某些部分。我们的空间记忆网络在其记忆中存储来自图像的不同空间区域的神经元激活，并且使用该问题来选择用于计算答案的相关区域，其过程在网络中构成单个“跳跃”。我们提出了一种新颖的空间注意结构，它将第一跳中的图像块与单词对齐，并且通过增加第二注意点来获得改善的结果，其中第二注意点将整个问题视为基于第一跳结果选择视觉证据。为了更好地理解网络学习的推理过程，我们设计了专门需要空间推理和可视化注意权重的综合问题。我们在两个已发表的视觉问题解答数据集DAQUAR [1]和VQA [2]上评估我们的模型，并且获得改善的结果，与连接图像和问题特征以预测答案的强基础深度模型（iBOWIMG）相比[3]。

##### URL
[https://arxiv.org/abs/1511.05234](https://arxiv.org/abs/1511.05234)

