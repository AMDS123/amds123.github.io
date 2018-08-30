---
layout: post
title: "Layer Trajectory LSTM"
date: 2018-08-28 20:13:18
categories: arXiv_CL
tags: arXiv_CL RNN Classification
author: Jinyu Li, Changliang Liu, Yifan Gong
mathjax: true
---

* content
{:toc}

##### Abstract
It is popular to stack LSTM layers to get better modeling power, especially when large amount of training data is available. However, an LSTM-RNN with too many vanilla LSTM layers is very hard to train and there still exists the gradient vanishing issue if the network goes too deep. This issue can be partially solved by adding skip connections between layers, such as residual LSTM. In this paper, we propose a layer trajectory LSTM (ltLSTM) which builds a layer-LSTM using all the layer outputs from a standard multi-layer time-LSTM. This layer-LSTM scans the outputs from time-LSTMs, and uses the summarized layer trajectory information for final senone classification. The forward-propagation of time-LSTM and layer-LSTM can be handled in two separate threads in parallel so that the network computation time is the same as the standard time-LSTM. With a layer-LSTM running through layers, a gated path is provided from the output layer to the bottom layer, alleviating the gradient vanishing issue. Trained with 30 thousand hours of EN-US Microsoft internal data, the proposed ltLSTM performed significantly better than the standard multi-layer LSTM and residual LSTM, with up to 9.0% relative word error rate reduction across different tasks.

##### Abstract (translated by Google)
堆叠LSTM层以获得更好的建模能力是很流行的，特别是当有大量训练数据可用时。然而，具有太多香草LSTM层的LSTM-RNN非常难以训练，并且如果网络太深，仍然存在梯度消失问题。通过在层之间添加跳过连接（例如残差LSTM）可以部分地解决此问题。在本文中，我们提出了一个层轨迹LSTM（ltLSTM），它使用标准多层时间LSTM的所有层输出构建一个层LSTM。该层-LSTM扫描来自时间LSTM的输出，并使用汇总的层轨迹信息进行最终的senone分类。时间-LSTM和层-LSTM的前向传播可以在两个单独的线程中并行处理，以便网络计算时间与标准时间-LSTM相同。通过层LSTM贯穿层，从输出层到底层提供门控路径，缓解了梯度消失问题。通过3万小时的EN-US Microsoft内部数据训练，所提出的ltLSTM表现明显优于标准多层LSTM和残余LSTM，在不同任务中相对字错误率降低高达9.0％。

##### URL
[http://arxiv.org/abs/1808.09522](http://arxiv.org/abs/1808.09522)

##### PDF
[http://arxiv.org/pdf/1808.09522](http://arxiv.org/pdf/1808.09522)

