---
layout: post
title: "Learning to Prune Deep Neural Networks via Layer-wise Optimal Brain Surgeon"
date: 2017-11-09 23:50:55
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Xin Dong, Shangyu Chen, Sinno Jialin Pan
mathjax: true
---

* content
{:toc}

##### Abstract
How to develop slim and accurate deep neural networks has become crucial for real- world applications, especially for those employed in embedded systems. Though previous work along this research line has shown some promising results, most existing methods either fail to significantly compress a well-trained deep network or require a heavy retraining process for the pruned deep network to re-boost its prediction performance. In this paper, we propose a new layer-wise pruning method for deep neural networks. In our proposed method, parameters of each individual layer are pruned independently based on second order derivatives of a layer-wise error function with respect to the corresponding parameters. We prove that the final prediction performance drop after pruning is bounded by a linear combination of the reconstructed errors caused at each layer. Therefore, there is a guarantee that one only needs to perform a light retraining process on the pruned network to resume its original prediction performance. We conduct extensive experiments on benchmark datasets to demonstrate the effectiveness of our pruning method compared with several state-of-the-art baseline methods.

##### Abstract (translated by Google)
如何开发精简而精确的深度神经网络已经成为现实应用的关键，尤其是对于那些在嵌入式系统中使用的应用。虽然以前在这个研究线上的工作已经显示出一些有希望的结果，但是大多数现有的方法要么不能显着地压缩训练有素的深度网络，要么需要重新训练过程来修剪深度网络以重新提高其预测性能。在本文中，我们提出了一种新的深层神经网络分层修剪方法。在我们提出的方法中，每个单独层的参数是根据相对于相应参数的分层误差函数的二阶导数独立地修剪的。我们证明了修剪后的最终预测性能下降是由每层造成的重建误差的线性组合所限制的。因此，保证在修剪网络上只需要进行轻微的再训练就可以恢复原来的预测性能。我们对基准数据集进行了广泛的实验，以证明我们的修剪方法与几种最先进的基线方法相比的有效性。

##### URL
[https://arxiv.org/abs/1705.07565](https://arxiv.org/abs/1705.07565)

##### PDF
[https://arxiv.org/pdf/1705.07565](https://arxiv.org/pdf/1705.07565)

