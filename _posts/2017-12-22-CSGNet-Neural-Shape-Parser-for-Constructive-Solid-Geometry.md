---
layout: post
title: "CSGNet: Neural Shape Parser for Constructive Solid Geometry"
date: 2017-12-22 03:18:57
categories: arXiv_AI
tags: arXiv_AI Detection
author: Gopal Sharma, Rishabh Goyal, Difan Liu, Evangelos Kalogerakis, Subhransu Maji
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural architecture that takes as input a 2D or 3D shape and induces a program to generate it. The in- structions in our program are based on constructive solid geometry principles, i.e., a set of boolean operations on shape primitives defined recursively. Bottom-up techniques for this task that rely on primitive detection are inherently slow since the search space over possible primitive combi- nations is large. In contrast, our model uses a recurrent neural network conditioned on the input shape to produce a sequence of instructions in a top-down manner and is sig- nificantly faster. It is also more effective as a shape detec- tor than existing state-of-the-art detection techniques. We also demonstrate that our network can be trained on novel datasets without ground-truth program annotations through policy gradient techniques.

##### Abstract (translated by Google)
我们提出了一个神经的体系结构，需要输入一个2D或3D形状，并诱导一个程序来生成它。我们的程序中的指令基于建设性的立体几何原则，即递归定义的形状基元上的一组布尔运算。由于对可能原始组合的搜索空间很大，因此依靠原始检测的这个任务的自下而上技术本质上是缓慢的。相反，我们的模型使用一个以输入形状为条件的递归神经网络，以自顶向下的方式产生一系列指令，并且速度明显加快。它比现有的最先进的检测技术更有效的形状检测器。我们还证明，我们的网络可以通过策略梯度技术在没有地面实况节目注释的新颖数据集上进行训练。

##### URL
[https://arxiv.org/abs/1712.08290](https://arxiv.org/abs/1712.08290)

##### PDF
[https://arxiv.org/pdf/1712.08290](https://arxiv.org/pdf/1712.08290)

