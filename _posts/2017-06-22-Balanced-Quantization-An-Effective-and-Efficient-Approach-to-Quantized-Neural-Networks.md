---
layout: post
title: "Balanced Quantization: An Effective and Efficient Approach to Quantized Neural Networks"
date: 2017-06-22 01:25:37
categories: arXiv_CV
tags: arXiv_CV CNN Inference RNN Prediction
author: Shuchang Zhou, Yuzhi Wang, He Wen, Qinyao He, Yuheng Zou
mathjax: true
---

* content
{:toc}

##### Abstract
Quantized Neural Networks (QNNs), which use low bitwidth numbers for representing parameters and performing computations, have been proposed to reduce the computation complexity, storage size and memory usage. In QNNs, parameters and activations are uniformly quantized, such that the multiplications and additions can be accelerated by bitwise operations. However, distributions of parameters in Neural Networks are often imbalanced, such that the uniform quantization determined from extremal values may under utilize available bitwidth. In this paper, we propose a novel quantization method that can ensure the balance of distributions of quantized values. Our method first recursively partitions the parameters by percentiles into balanced bins, and then applies uniform quantization. We also introduce computationally cheaper approximations of percentiles to reduce the computation overhead introduced. Overall, our method improves the prediction accuracies of QNNs without introducing extra computation during inference, has negligible impact on training speed, and is applicable to both Convolutional Neural Networks and Recurrent Neural Networks. Experiments on standard datasets including ImageNet and Penn Treebank confirm the effectiveness of our method. On ImageNet, the top-5 error rate of our 4-bit quantized GoogLeNet model is 12.7\%, which is superior to the state-of-the-arts of QNNs.

##### Abstract (translated by Google)
已经提出了使用低位数来表示参数和执行计算的量化的神经网络（QNN），以减少计算复杂度，存储大小和存储器使用量。在QNN中，参数和激活被统一量化，使得乘法和加法可以通过按位操作来加速。然而，神经网络中的参数分布通常是不平衡的，使得由极值确定的均匀量化可能利用可用的位宽。在本文中，我们提出了一种新的量化方法，可以保证量化值分布的平衡。我们的方法首先递归地将参数按百分比划分成平衡箱，然后应用均匀量化。我们还引入计算更便宜的百分比近似值来减少引入的计算开销。总的来说，我们的方法提高了QNNs的预测精度，不需要在推理过程中引入额外的计算，对训练速度的影响可以忽略不计，适用于卷积神经网络和递归神经网络。包括ImageNet和Penn Treebank在内的标准数据集的实验证实了我们方法的有效性。在ImageNet上，我们的4位量化GoogLeNet模型的前5位错误率是12.7％，这比QNN的先进水平要好。

##### URL
[https://arxiv.org/abs/1706.07145](https://arxiv.org/abs/1706.07145)

##### PDF
[https://arxiv.org/pdf/1706.07145](https://arxiv.org/pdf/1706.07145)

