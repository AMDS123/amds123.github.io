---
layout: post
title: "Approximate Distribution Matching for Sequence-to-Sequence Learning"
date: 2018-08-24 05:00:17
categories: arXiv_AI
tags: arXiv_AI Image_Caption Summarization Caption Optimization RNN Prediction
author: Wenhu Chen, Guanlin Li, Shujie Liu, Zhirui Zhang, Mu Li, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-Sequence models were introduced to tackle many real-life problems like machine translation, summarization, image captioning, etc. The standard optimization algorithms are mainly based on example-to-example matching like maximum likelihood estimation, which is known to suffer from data sparsity problem. Here we present an alternate view to explain sequence-to-sequence learning as a distribution matching problem, where each source or target example is viewed to represent a local latent distribution in the source or target domain. Then, we interpret sequence-to-sequence learning as learning a transductive model to transform the source local latent distributions to match their corresponding target distributions. In our framework, we approximate both the source and target latent distributions with recurrent neural networks (augmenter). During training, the parallel augmenters learn to better approximate the local latent distributions, while the sequence prediction model learns to minimize the KL-divergence of the transformed source distributions and the approximated target distributions. This algorithm can alleviate the data sparsity issues in sequence learning by locally augmenting more unseen data pairs and increasing the model's robustness. Experiments conducted on machine translation and image captioning consistently demonstrate the superiority of our proposed algorithm over the other competing algorithms.

##### Abstract (translated by Google)
引入序列到序列模型来解决许多现实问题，如机器翻译，摘要，图像字幕等。标准优化算法主要基于像最大似然估计这样的示例到示例匹配，已知会受到影响从数据稀疏性问题。在这里，我们提供了另一种视图来解释序列到序列学习作为分布匹配问题，其中每个源或目标示例被视为表示源或目标域中的本地潜在分布。然后，我们将序列到序列学习解释为学习转换模型以转换源局部潜在分布以匹配其对应的目标分布。在我们的框架中，我们使用递归神经网络（增强器）来近似源和目标潜在分布。在训练期间，并行增强器学习更好地近似局部潜在分布，而序列预测模型学习以最小化变换的源分布和近似目标分布的KL-发散。该算法可以通过局部增加更多看不见的数据对并提高模型的鲁棒性来减轻序列学习中的数据稀疏性问题。在机器翻译和图像字幕上进行的实验一致地证明了我们提出的算法优于其他竞争算法的优越性。

##### URL
[http://arxiv.org/abs/1808.08003](http://arxiv.org/abs/1808.08003)

##### PDF
[http://arxiv.org/pdf/1808.08003](http://arxiv.org/pdf/1808.08003)

