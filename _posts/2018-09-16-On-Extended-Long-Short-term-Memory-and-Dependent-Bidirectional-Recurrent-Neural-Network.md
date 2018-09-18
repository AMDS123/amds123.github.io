---
layout: post
title: "On Extended Long Short-term Memory and Dependent Bidirectional Recurrent Neural Network"
date: 2018-09-16 05:43:49
categories: arXiv_CL
tags: arXiv_CL Attention CNN RNN Prediction
author: Yuanhang Su, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we analyze how memory forms in recurrent neural networks (RNN) and, based on the analysis, how to increase their memory capabilities in a mathematical rigorous way. Here, we define memory as a function that maps previous elements in a sequence to the current output. Our investigation concludes that the three RNN cells: simple RNN (SRN), long short-term memory (LSTM) and gated recurrent unit (GRU) all suffer memory decay as a function of the distance between the output to the input. To overcome this limitation by design, we introduce trainable scaling factors which act like an attention mechanism to increase the memory response to the semantic inputs if there is a memory decay and to decrease the response if memory decay of the noises is not fast enough. We call the new design extended LSTM (ELSTM). Next, we present a dependent bidirectional recurrent neural network (DBRNN), which is more robust to previous erroneous predictions. Extensive experiments are carried out on different language tasks to demonstrate the superiority of our proposed ELSTM and DBRNN solutions. In dependency parsing (DP), our proposed ELTSM has achieved up to 30% increase of labeled attachment score (LAS) as compared to LSTM and GRU. Our proposed models also outperformed other state-of-the-art models such as bi-attention and convolutional sequence to sequence (convseq2seq) by close to 10% LAS.

##### Abstract (translated by Google)
在这项工作中，我们分析了记忆如何在递归神经网络（RNN）中形成，并且基于分析，如何以数学严谨的方式增加记忆能力。在这里，我们将内存定义为将序列中的前一个元素映射到当前输出的函数。我们的调查得出结论，三个RNN单元：简单RNN（SRN），长短期记忆（LSTM）和门控循环单元（GRU）都遭受记忆衰减作为输出到输入之间距离的函数。为了通过设计克服这种限制，我们引入了可训练的缩放因子，其作用是注意机制，以在存在存储器衰减时增加对语义输入的存储器响应，并且如果噪声的存储器衰减不够快则减小响应。我们将新设计称为扩展LSTM（ELSTM）。接下来，我们提出了一个依赖的双向递归神经网络（DBRNN），它对以前的错误预测更加健壮。对不同的语言任务进行了广泛的实验，以证明我们提出的ELSTM和DBRNN解决方案的优越性。在依赖性解析（DP）中，与LSTM和GRU相比，我们提出的ELTSM已经实现了标记附着得分（LAS）增加高达30％。我们提出的模型也优于其他最先进的模型，如双重注意和卷积序列到序列（convseq2seq）接近10％的LAS。

##### URL
[http://arxiv.org/abs/1803.01686](http://arxiv.org/abs/1803.01686)

##### PDF
[http://arxiv.org/pdf/1803.01686](http://arxiv.org/pdf/1803.01686)

