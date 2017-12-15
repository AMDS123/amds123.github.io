---
layout: post
title: "Dialogue Act Sequence Labeling using Hierarchical encoder with CRF"
date: 2017-09-14 13:49:10
categories: arXiv_CL
tags: arXiv_CL RNN Recognition
author: Harshit Kumar, Arvind Agarwal, Riddhiman Dasgupta, Sachindra Joshi, Arun Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
Dialogue Act recognition associate dialogue acts (i.e., semantic labels) to utterances in a conversation. The problem of associating semantic labels to utterances can be treated as a sequence labeling problem. In this work, we build a hierarchical recurrent neural network using bidirectional LSTM as a base unit and the conditional random field (CRF) as the top layer to classify each utterance into its corresponding dialogue act. The hierarchical network learns representations at multiple levels, i.e., word level, utterance level, and conversation level. The conversation level representations are input to the CRF layer, which takes into account not only all previous utterances but also their dialogue acts, thus modeling the dependency among both, labels and utterances, an important consideration of natural dialogue. We validate our approach on two different benchmark data sets, Switchboard and Meeting Recorder Dialogue Act, and show performance improvement over the state-of-the-art methods by $2.2\%$ and $4.1\%$ absolute points, respectively. It is worth noting that the inter-annotator agreement on Switchboard data set is $84\%$, and our method is able to achieve the accuracy of about $79\%$ despite being trained on the noisy data.

##### Abstract (translated by Google)
对话法识别对话中的话语行为（即语义标签）。将语义标签与话语相关联的问题可以被看作是序列标签问题。在这项工作中，我们建立一个层次递归神经网络，使用双向LSTM作为基本单位和条件随机场（CRF）作为最高层将每个话语分类成其相应的对话行为。分级网络学习多个级别的表示，即，单词级别，话语级别和会话级别。会话级别表示被输入到CRF层，其不仅考虑所有之前的话语，而且还考虑其对话行为，从而建立对两者，标签和话语之间的依赖关系的建模，这是自然对话的重要考虑。我们在两个不同的基准测试数据集“交换机”和“会议记录器对话法”中验证了我们的方法，并且分别比最先进的方法提高了2.2％和4.1％值得注意的是，交换机数据集之间的内部注释器协议是$ 84 \％$，我们的方法能够达到大约$ 79 \％$的准确性，尽管在嘈杂的数据训练。

##### URL
[https://arxiv.org/abs/1709.04250](https://arxiv.org/abs/1709.04250)

##### PDF
[https://arxiv.org/pdf/1709.04250](https://arxiv.org/pdf/1709.04250)

