---
layout: post
title: "How Many Samples are Needed to Learn a Convolutional Neural Network?"
date: 2018-05-21 03:56:17
categories: arXiv_AI
tags: arXiv_AI CNN Prediction
author: Simon S. Du, Yining Wang, Xiyu Zhai, Sivaraman Balakrishnan, Ruslan Salakhutdinov, Aarti Singh
mathjax: true
---

* content
{:toc}

##### Abstract
A widespread folklore for explaining the success of convolutional neural network (CNN) is that CNN is a more compact representation than the fully connected neural network (FNN) and thus requires fewer samples for learning. We initiate the study of rigorously characterizing the sample complexity of learning convolutional neural networks. We show that for learning an $m$-dimensional convolutional filter with linear activation acting on a $d$-dimensional input, the sample complexity of achieving population prediction error of $\epsilon$ is $\widetilde{O} (m/\epsilon^2)$, whereas its FNN counterpart needs at least $\Omega(d/\epsilon^2)$ samples. Since $m \ll d$, this result demonstrates the advantage of using CNN. We further consider the sample complexity of learning a one-hidden-layer CNN with linear activation where both the $m$-dimensional convolutional filter and the $r$-dimensional output weights are unknown. For this model, we show the sample complexity is $\widetilde{O}\left((m+r)/\epsilon^2\right)$ when the ratio between the stride size and the filter size is a constant. For both models, we also present lower bounds showing our sample complexities are tight up to logarithmic factors. Our main tools for deriving these results are localized empirical process and a new lemma characterizing the convolutional structure. We believe these tools may inspire further developments in understanding CNN.

##### Abstract (translated by Google)
解释卷积神经网络（CNN）成功的一个普遍的民间传说是CNN比完全连接的神经网络（FNN）更紧凑的表示，因此需要更少的学习样本。我们开始严格描述学习卷积神经网络样本复杂性的研究。我们表明，为了学习一个$ m $维的卷积滤波器，其线性激活作用于一个$ d $维的输入，实现$ \ epsilon $的人口预测误差的样本复杂度为$ \ widetilde {O}（m / \ ε^ 2）$，而其FNN对应物至少需要$ \欧米茄（d /ε^ 2）$样本。由于$ m \ ll d $，这个结果证明了使用CNN的优点。我们进一步考虑用线性激活学习单隐层CNN的样本复杂性，其中$ m $维卷积滤波器和$ r $维的输出权重都是未知的。对于这个模型，当步幅大小和过滤器大小之间的比例是常数时，我们显示样本复杂度为$ \ widetilde {O} \ left（（m + r）/ \ epsilon ^ 2 \ right）$。对于这两种模型，我们还呈现出下限，表明我们的样本复杂性紧随对数因子。我们用于推导这些结果的主要工具是本地化的经验过程和表征卷积结构的新引理。我们相信这些工具可能会激发对理解CNN的进一步发展。

##### URL
[https://arxiv.org/abs/1805.07883](https://arxiv.org/abs/1805.07883)

##### PDF
[https://arxiv.org/pdf/1805.07883](https://arxiv.org/pdf/1805.07883)

