---
layout: post
title: "Kernel Approximation Methods for Speech Recognition"
date: 2017-01-13 07:24:18
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Relation Recognition
author: Avner May, Alireza Bagheri Garakani, Zhiyun Lu, Dong Guo, Kuan Liu, Aurélien Bellet, Linxi Fan, Michael Collins, Daniel Hsu, Brian Kingsbury, Michael Picheny, Fei Sha
mathjax: true
---

* content
{:toc}

##### Abstract
We study large-scale kernel methods for acoustic modeling in speech recognition and compare their performance to deep neural networks (DNNs). We perform experiments on four speech recognition datasets, including the TIMIT and Broadcast News benchmark tasks, and compare these two types of models on frame-level performance metrics (accuracy, cross-entropy), as well as on recognition metrics (word/character error rate). In order to scale kernel methods to these large datasets, we use the random Fourier feature method of Rahimi and Recht (2007). We propose two novel techniques for improving the performance of kernel acoustic models. First, in order to reduce the number of random features required by kernel models, we propose a simple but effective method for feature selection. The method is able to explore a large number of non-linear features while maintaining a compact model more efficiently than existing approaches. Second, we present a number of frame-level metrics which correlate very strongly with recognition performance when computed on the heldout set; we take advantage of these correlations by monitoring these metrics during training in order to decide when to stop learning. This technique can noticeably improve the recognition performance of both DNN and kernel models, while narrowing the gap between them. Additionally, we show that the linear bottleneck method of Sainath et al. (2013) improves the performance of our kernel models significantly, in addition to speeding up training and making the models more compact. Together, these three methods dramatically improve the performance of kernel acoustic models, making their performance comparable to DNNs on the tasks we explored.

##### Abstract (translated by Google)
我们研究语音识别中的声学建模的大规模核方法，并将其性能与深度神经网络（DNN）进行比较。我们在四个语音识别数据集（包括TIMIT和Broadcast News基准测试任务）上进行实验，并将这两种类型的模型在帧级性能指标（精度，交叉熵）以及识别指标（字/字符错误率）。为了将核方法扩展到这些大型数据集，我们使用Rahimi和Recht（2007）的随机傅里叶特征方法。我们提出了两个新的技术来提高核心声学模型的性能。首先，为了减少核模型所需的随机特征的数量，提出了一种简单而有效的特征选择方法。该方法能够探索大量的非线性特征，同时比现有方法更有效地维持紧凑模型。其次，我们提出了一些框架级别的度量标准，这些度量标准在持久集上进行计算时与识别性能非常强相关;我们通过在培训期间监控这些指标来利用这些相关性来决定何时停止学习。这种技术可以显着提高DNN和核模型的识别性能，同时缩小它们之间的差距。另外，我们展示了Sainath等人的线性瓶颈方法。 （2013）显着提高了我们的核心模型的性能，除了加快培训和使模型更紧凑。这三种方法共同极大地提高了内核声学模型的性能，使得它们的性能可以与我们探索的任务相媲美。

##### URL
[https://arxiv.org/abs/1701.03577](https://arxiv.org/abs/1701.03577)

##### PDF
[https://arxiv.org/pdf/1701.03577](https://arxiv.org/pdf/1701.03577)

