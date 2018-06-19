---
layout: post
title: "Towards an efficient deep learning model for musical onset detection"
date: 2018-06-18 15:30:35
categories: arXiv_SD
tags: arXiv_SD Review Transfer_Learning Deep_Learning Detection
author: Rong Gong, Xavier Serra
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an efficient and reproducible deep learning model for musical onset detection (MOD). We first review the state-of-the-art deep learning models for MOD, and identify their shortcomings and challenges: (i) the lack of hyper-parameter tuning details, (ii) the non-availability of code for training models on other datasets, and (iii) ignoring the network capability when comparing different architectures. Taking the above issues into account, we experiment with seven deep learning architectures. The most efficient one achieves equivalent performance to our implementation of the state-of-the-art architecture. However, it has only 28.3\% of the total number of trainable parameters compared to the state-of-the-art. Our experiments are conducted using two different datasets: one mainly consists of instrumental music excerpts, and another developed by ourselves includes only solo singing voice excerpts. Further, inter-dataset transfer learning experiments are conducted. The results show that the model pre-trained on one dataset fails to detect onsets on another dataset, which denotes the importance of providing the implementation code to enable re-training the model for a different dataset. Datasets, code and a Jupyter notebook running on Google Colab are publicly available to make this research understandable and easy to reproduce.

##### Abstract (translated by Google)
在本文中，我们提出了一种有效和可重现的音乐起始检测（MOD）的深度学习模型。我们首先回顾了MOD的最新深度学习模型，并确定了它们的缺点和挑战：（i）缺少超参数调整细节，（ii）其他模型的训练模型的代码不可用数据集，以及（iii）在比较不同架构时忽略网络能力。考虑到上述问题，我们尝试了七种深度学习架构。最高效的实现与我们实施最先进的体系结构相当的性能。然而，与最先进的技术相比，它只有可训练参数总数的28.3％。我们的实验使用两个不同的数据集进行：一个主要由器乐音乐片段组成，另一个由我们自己开发，仅包含独唱歌曲片段。此外，进行数据集间转移学习实验。结果表明，在一个数据集上预先训练的模型未能检测到另一个数据集上的起点，这表示提供实现代码以便为不同数据集重新训练模型的重要性。在Google Colab上运行的数据集，代码和Jupyter笔记本可公开发布，以便使此研究易于理解并易于重现。

##### URL
[http://arxiv.org/abs/1806.06773](http://arxiv.org/abs/1806.06773)

##### PDF
[http://arxiv.org/pdf/1806.06773](http://arxiv.org/pdf/1806.06773)

