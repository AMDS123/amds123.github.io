---
layout: post
title: 'Unsupervised Generative Adversarial Cross-modal Hashing'
date: 2017-12-06 00:57:45
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Jian Zhang, Yuxin Peng, Mingkuan Yuan
---

* content
{:toc}

##### Abstract
Cross-modal hashing aims to map heterogeneous multimedia data into a common Hamming space, which can realize fast and flexible retrieval across different modalities. Unsupervised cross-modal hashing is more flexible and applicable than supervised methods, since no intensive labeling work is involved. However, existing unsupervised methods learn hashing functions by preserving inter and intra correlations, while ignoring the underlying manifold structure across different modalities, which is extremely helpful to capture meaningful nearest neighbors of different modalities for cross-modal retrieval. To address the above problem, in this paper we propose an Unsupervised Generative Adversarial Cross-modal Hashing approach (UGACH), which makes full use of GAN's ability for unsupervised representation learning to exploit the underlying manifold structure of cross-modal data. The main contributions can be summarized as follows: (1) We propose a generative adversarial network to model cross-modal hashing in an unsupervised fashion. In the proposed UGACH, given a data of one modality, the generative model tries to fit the distribution over the manifold structure, and select informative data of another modality to challenge the discriminative model. The discriminative model learns to distinguish the generated data and the true positive data sampled from correlation graph to achieve better retrieval accuracy. These two models are trained in an adversarial way to improve each other and promote hashing function learning. (2) We propose a correlation graph based approach to capture the underlying manifold structure across different modalities, so that data of different modalities but within the same manifold can have smaller Hamming distance and promote retrieval accuracy. Extensive experiments compared with 6 state-of-the-art methods verify the effectiveness of our proposed approach.

##### Abstract (translated by Google)
跨模态散列的目的是将异构多媒体数据映射到一个共同的汉明空间，可以实现跨不同模式的快速和灵活的检索。无监督的交叉模式哈希比监督方法更灵活和适用，因为不涉及大量的标签工作。然而，现有的无监督方法通过保留帧间和帧内相关性来学习散列函数，而忽略不同模式下的基本流形结构，这对于捕获跨模态检索的不同模式的有意义的最近邻居非常有帮助。为解决上述问题，本文提出了一种无监督生成对抗的跨模态哈希方法（UGACH），该方法充分利用了GAN的无监督表示学习能力，开发了跨模态数据的底层流形结构。主要贡献可概括如下：（1）提出了一种生成对抗网络，以无监督的方式对交叉模式哈希进行建模。在所提出的UGACH中，给定一种模式的数据，生成模型试图拟合流形结构的分布，并选择另一种模式的信息数据来挑战判别模型。区分模型学习区分生成的数据和从相关图中采样的真正数据，以获得更好的检索精度。这两种模式都是以对抗的方式进行训练，相互促进，推动哈希函数的学习。 （2）提出了一种基于相关图的方法来捕捉不同模态下的基本流形结构，使得不同模态的数据在相同的流形中可以具有较小的汉明距离，提高检索的准确性。与6种最先进的方法相比，大量的实验验证了我们提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1712.00358](https://arxiv.org/abs/1712.00358)

