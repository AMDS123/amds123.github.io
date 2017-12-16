---
layout: post
title: "Hierarchical Multi-scale Attention Networks for Action Recognition"
date: 2017-08-28 05:23:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Action_Recognition RNN Detection Relation Recognition
author: Shiyang Yan, Jeremy S. Smith, Wenjin Lu, Bailing Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) have been widely used in natural language processing and computer vision. Among them, the Hierarchical Multi-scale RNN (HM-RNN), a kind of multi-scale hierarchical RNN proposed recently, can learn the hierarchical temporal structure from data automatically. In this paper, we extend the work to solve the computer vision task of action recognition. However, in sequence-to-sequence models like RNN, it is normally very hard to discover the relationships between inputs and outputs given static inputs. As a solution, attention mechanism could be applied to extract the relevant information from input thus facilitating the modeling of input-output relationships. Based on these considerations, we propose a novel attention network, namely Hierarchical Multi-scale Attention Network (HM-AN), by combining the HM-RNN and the attention mechanism and apply it to action recognition. A newly proposed gradient estimation method for stochastic neurons, namely Gumbel-softmax, is exploited to implement the temporal boundary detectors and the stochastic hard attention mechanism. To amealiate the negative effect of sensitive temperature of the Gumbel-softmax, an adaptive temperature training method is applied to better the system performance. The experimental results demonstrate the improved effect of HM-AN over LSTM with attention on the vision task. Through visualization of what have been learnt by the networks, it can be observed that both the attention regions of images and the hierarchical temporal structure can be captured by HM-AN.

##### Abstract (translated by Google)
递归神经网络（RNN）被广泛应用于自然语言处理和计算机视觉领域。其中，最近提出的一种多尺度分层RNN（Hierarchical Multi-scale RNN，HM-RNN）可以自动从数据中学习分层时间结构。在本文中，我们扩展了解决动作识别的计算机视觉任务的工作。然而，在像RNN这样的序列 - 序列模型中，通常很难发现给定静态输入的输入和输出之间的关系。作为解决方案，可以使用注意机制从输入中提取相关信息，从而便于输入输出关系建模。基于这些考虑，我们将HM-RNN和注意机制相结合，提出了一种新的关注网络，即分层多尺度注意网络（HM-AN），并将其应用于动作识别。提出了一种新的随机神经元梯度估计方法，即Gumbel-softmax，实现了时间边界检测器和随机硬注意机制。为了改善Gumbel-softmax敏感温度的不利影响，采用自适应温度训练方法来提高系统性能。实验结果表明HM-AN相对于LSTM的改善效果注重视觉任务。通过对网络所学知识的可视化，可以观察到，HM-AN可以捕获图像的关注区域和分层时间结构。

##### URL
[https://arxiv.org/abs/1708.07590](https://arxiv.org/abs/1708.07590)

##### PDF
[https://arxiv.org/pdf/1708.07590](https://arxiv.org/pdf/1708.07590)

