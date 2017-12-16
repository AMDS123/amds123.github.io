---
layout: post
title: "Deep Local Video Feature for Action Recognition"
date: 2017-01-28 13:50:09
categories: arXiv_CV
tags: arXiv_CV Sparse Action_Recognition RNN Recognition
author: Zhenzhong Lan, Yi Zhu, Alexander G. Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of representing an entire video using CNN features for human action recognition. Currently, limited by GPU memory, we have not been able to feed a whole video into CNN/RNNs for end-to-end learning. A common practice is to use sampled frames as inputs and video labels as supervision. One major problem of this popular approach is that the local samples may not contain the information indicated by global labels. To deal with this problem, we propose to treat the deep networks trained on local inputs as local feature extractors. After extracting local features, we aggregate them into global features and train another mapping function on the same training data to map the global features into global labels. We study a set of problems regarding this new type of local features such as how to aggregate them into global features. Experimental results on HMDB51 and UCF101 datasets show that, for these new local features, a simple maximum pooling on the sparsely sampled features lead to significant performance improvement.

##### Abstract (translated by Google)
我们调查使用CNN特征来表示整个视频的人类行为识别问题。目前，由于GPU内存的限制，我们无法将整个视频输入CNN / RNN进行端到端的学习。通常的做法是使用采样帧作为输入和视频标签作为监督。这种流行方法的一个主要问题是本地样本可能不包含全球标签所指示的信息。为了解决这个问题，我们建议将本地输入训练的深度网络作为局部特征提取器。在提取局部特征之后，我们将它们聚合成全局特征，并在相同的训练数据上训练另一个映射函数，以将全局特征映射到全局标签。我们研究了一系列有关这种新型局部特征的问题，例如如何将它们聚合成全局特征。 HMDB51和UCF101数据集上的实验结果表明，对于这些新的局部特征，简单的最大化共享稀疏采样特征导致显着的性能改进。

##### URL
[https://arxiv.org/abs/1701.07368](https://arxiv.org/abs/1701.07368)

##### PDF
[https://arxiv.org/pdf/1701.07368](https://arxiv.org/pdf/1701.07368)

