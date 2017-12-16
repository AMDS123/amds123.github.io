---
layout: post
title: "CM-GANs: Cross-modal Generative Adversarial Networks for Common Representation Learning"
date: 2017-10-14 00:15:56
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN CNN Represenation_Learning Relation
author: Yuxin Peng, Jinwei Qi, Yuxin Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
It is known that the inconsistent distribution and representation of different modalities, such as image and text, cause the heterogeneity gap that makes it challenging to correlate such heterogeneous data. Generative adversarial networks (GANs) have shown its strong ability of modeling data distribution and learning discriminative representation, existing GANs-based works mainly focus on generative problem to generate new data. We have different goal, aim to correlate heterogeneous data, by utilizing the power of GANs to model cross-modal joint distribution. Thus, we propose Cross-modal GANs to learn discriminative common representation for bridging heterogeneity gap. The main contributions are: (1) Cross-modal GANs architecture is proposed to model joint distribution over data of different modalities. The inter-modality and intra-modality correlation can be explored simultaneously in generative and discriminative models. Both of them beat each other to promote cross-modal correlation learning. (2) Cross-modal convolutional autoencoders with weight-sharing constraint are proposed to form generative model. They can not only exploit cross-modal correlation for learning common representation, but also preserve reconstruction information for capturing semantic consistency within each modality. (3) Cross-modal adversarial mechanism is proposed, which utilizes two kinds of discriminative models to simultaneously conduct intra-modality and inter-modality discrimination. They can mutually boost to make common representation more discriminative by adversarial training process. To the best of our knowledge, our proposed CM-GANs approach is the first to utilize GANs to perform cross-modal common representation learning. Experiments are conducted to verify the performance of our proposed approach on cross-modal retrieval paradigm, compared with 10 methods on 3 cross-modal datasets.

##### Abstract (translated by Google)
众所周知，不同形式（如图像和文本）的不一致的分布和表示会导致异质性差距，这使得将这种异构数据关联起来具有挑战性。生成对抗网络（GANs）表现出强大的数据分布建模能力和学习判别表征能力，现有的基于GANs的工作主要集中在生成问题上来生成新的数据。我们有不同的目标，旨在关联异构数据，利用GAN的功能来模拟跨模式联合分布。因此，我们提出跨模态GAN来学习桥接异质性差距的歧视性共同表示。主要贡献有：（1）提出了跨模态GAN体系结构来模拟不同模态数据的联合分布。在生成模式和区分模式中可以同时探索模态间和模态内的相关性。他们两人互相推cross，以促进跨模式的相关学习。 （2）提出了具有权重共享约束的跨模态卷积自编码器，形成生成模型。他们不仅可以利用跨模态关联学习共同表示，而且还可以保存重构信息以捕获每种模式中的语义一致性。 （3）提出了跨模态对抗机制，利用两种判别模式同时进行模态间和模态间的判别。他们可以相互促进，使敌对的训练过程中的共同表示更具歧视性。据我们所知，我们提出的CM-GANs方法是第一个利用GAN进行跨模态的通用表示学习。实验进行验证我们提出的方法在跨模态检索范式的性能，相比之下，在3个跨模态数据集上的10个方法。

##### URL
[https://arxiv.org/abs/1710.05106](https://arxiv.org/abs/1710.05106)

##### PDF
[https://arxiv.org/pdf/1710.05106](https://arxiv.org/pdf/1710.05106)

