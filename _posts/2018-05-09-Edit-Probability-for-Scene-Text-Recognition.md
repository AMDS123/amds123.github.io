---
layout: post
title: "Edit Probability for Scene Text Recognition"
date: 2018-05-09 06:14:51
categories: arXiv_CV
tags: arXiv_CV Attention Recognition
author: Fan Bai, Zhanzhan Cheng, Yi Niu, Shiliang Pu, Shuigeng Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the scene text recognition problem under the attention-based encoder-decoder framework, which is the state of the art. The existing methods usually employ a frame-wise maximal likelihood loss to optimize the models. When we train the model, the misalignment between the ground truth strings and the attention's output sequences of probability distribution, which is caused by missing or superfluous characters, will confuse and mislead the training process, and consequently make the training costly and degrade the recognition accuracy. To handle this problem, we propose a novel method called edit probability (EP) for scene text recognition. EP tries to effectively estimate the probability of generating a string from the output sequence of probability distribution conditioned on the input image, while considering the possible occurrences of missing/superfluous characters. The advantage lies in that the training process can focus on the missing, superfluous and unrecognized characters, and thus the impact of the misalignment problem can be alleviated or even overcome. We conduct extensive experiments on standard benchmarks, including the IIIT-5K, Street View Text and ICDAR datasets. Experimental results show that the EP can substantially boost scene text recognition performance.

##### Abstract (translated by Google)
我们考虑了基于注意力的编码器 - 解码器框架下的场景文本识别问题，这是最先进的。现有方法通常采用逐帧最大似然损失来优化模型。在对模型进行训练时，由于缺失或多余的特征引起的地面真值串与注意输出的概率分布序列之间的错位会混淆误导训练过程，从而导致训练代价高昂，降低识别准确率。为了解决这个问题，我们提出了一种称为编辑概率（EP）的新方法，用于场景文本识别。 EP试图从输入图像的条件概率分布输出序列中有效地估计产生一个字符串的概率，同时考虑可能发生的缺失/多余字符。其优点在于训练过程可以集中在缺失，多余和未识别的角色上，从而可以缓解甚至克服错位问题的影响。我们对标准基准进行了广泛的实验，包括IIIT-5K，Street View Text和ICDAR数据集。实验结果表明，EP可以大幅提升场景文本识别性能。

##### URL
[http://arxiv.org/abs/1805.03384](http://arxiv.org/abs/1805.03384)

##### PDF
[http://arxiv.org/pdf/1805.03384](http://arxiv.org/pdf/1805.03384)

