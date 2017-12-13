---
layout: post
title: "Optimizing Long Short-Term Memory Recurrent Neural Networks Using Ant Colony Optimization to Predict Turbine Engine Vibration"
date: 2017-10-10 14:09:22
categories: arXiv_CV
tags: arXiv_CV Face Optimization RNN Prediction
author: AbdElRahman ElSaid, Travis Desell, Fatima El Jamiy, James Higgins, Brandon Wild
mathjax: true
---

* content
{:toc}

##### Abstract
This article expands on research that has been done to develop a recurrent neural network (RNN) capable of predicting aircraft engine vibrations using long short-term memory (LSTM) neurons. LSTM RNNs can provide a more generalizable and robust method for prediction over analytical calculations of engine vibration, as analytical calculations must be solved iteratively based on specific empirical engine parameters, making this approach ungeneralizable across multiple engines. In initial work, multiple LSTM RNN architectures were proposed, evaluated and compared. This research improves the performance of the most effective LSTM network design proposed in the previous work by using a promising neuroevolution method based on ant colony optimization (ACO) to develop and enhance the LSTM cell structure of the network. A parallelized version of the ACO neuroevolution algorithm has been developed and the evolved LSTM RNNs were compared to the previously used fixed topology. The evolved networks were trained on a large database of flight data records obtained from an airline containing flights that suffered from excessive vibration. Results were obtained using MPI (Message Passing Interface) on a high performance computing (HPC) cluster, evolving 1000 different LSTM cell structures using 168 cores over 4 days. The new evolved LSTM cells showed an improvement of 1.35%, reducing prediction error from 5.51% to 4.17% when predicting excessive engine vibrations 10 seconds in the future, while at the same time dramatically reducing the number of weights from 21,170 to 11,810.

##### Abstract (translated by Google)
这篇文章扩展了研究已经做了开发一个循环神经网络（RNN）能够预测使用长期短期记忆（LSTM）神经元的飞机发动机振动。 LSTM RNNs可以提供一个更为一般化和鲁棒的方法来预测发动机振动的分析计算，因为分析计算必须基于特定的经验发动机参数迭代求解，使得这种方法在多个发动机之间是不可通用的。在最初的工作中，提出了多个LSTM RNN体系结构，进行评估和比较。本研究通过使用基于蚁群优化（ACO）的有前途的神经元演化方法来开发和增强网络的LSTM小区结构，提高了前面工作中提出的最有效的LSTM网络设计的性能。已经开发了ACO神经元演化算法的并行化版本，并将演进的LSTM RNN与先前使用的固定拓扑相比较。演变的网络是在从一家航空公司获得的飞行数据记录的大型数据库上进行训练的，该航空公司的航班中有过度的振动。使用高性能计算（HPC）群集上的MPI（消息传递接口）获得结果，在4天内使用168个内核演变出1000个不同的LSTM单元结构。新的进化LSTM单元显示了1.35％的改善，在预测未来10秒的过量发动机振动时将预测误差从5.51％降低到4.17％，同时将重量从21,170显着减少到11810。

##### URL
[https://arxiv.org/abs/1710.03753](https://arxiv.org/abs/1710.03753)

##### PDF
[https://arxiv.org/pdf/1710.03753](https://arxiv.org/pdf/1710.03753)

