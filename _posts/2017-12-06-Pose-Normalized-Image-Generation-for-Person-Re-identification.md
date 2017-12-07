---
layout: post
title: "Pose-Normalized Image Generation for Person Re-identification"
date: 2017-12-06 15:18:53
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Xuelin Qian, Yanwei Fu, Wenxuan Wang, Tao Xiang, Yang Wu, Yu-Gang Jiang, Xiangyang Xue
mathjax: true
---

* content
{:toc}

##### Abstract
Person Re-identification (re-id) faces two major challenges: the lack of cross-view paired training data and learning discriminative identity-sensitive and view-invariant features in the presence of large pose variations. In this work, we address both problems by proposing a novel deep person image generation model for synthesizing realistic person images conditional on pose. The model is based on a generative adversarial network (GAN) and used specifically for pose normalization in re-id, thus termed pose-normalization GAN (PN-GAN). With the synthesized images, we can learn a new type of deep re-id feature free of the influence of pose variations. We show that this feature is strong on its own and highly complementary to features learned with the original images. Importantly, we now have a model that generalizes to any new re-id dataset without the need for collecting any training data for model fine-tuning, thus making a deep re-id model truly scalable. Extensive experiments on five benchmarks show that our model outperforms the state-of-the-art models, often significantly. In particular, the features learned on Market-1501 can achieve a Rank-1 accuracy of 68.67% on VIPeR without any model fine-tuning, beating almost all existing models fine-tuned on the dataset.

##### Abstract (translated by Google)
人重新识别（re-id）面临两大挑战：缺少交叉视角配对的训练数据，以及在大姿态变化的情况下学习识别性身份敏感和视图不变特征。在这项工作中，我们通过提出一种新颖的深度人物图像生成模型来处理这两个问题，以合成以姿势为条件的真实人物图像。该模型基于生成对抗网络（GAN），专门用于re-id中的姿态归一化，因此称为姿态归一化GAN（PN-GAN）。通过合成图像，我们可以学习到一种没有姿态变化影响的新型深度重建特征。我们表明，这个功能是强大的，并与原始图像学习功能高度互补。重要的是，我们现在有一个模型，可以推广到任何新的数据集，而不需要收集任何模型微调的训练数据，从而使得一个真正可扩展的深度数据模型。在五个基准上的大量实验表明，我们的模型经常显着优于最先进的模型。尤其是，在Market-1501上学到的特性可以在VIPeR上实现68.67％的Rank-1准确性，而无需进行任何模型微调，几乎击败了所有在数据集上进行微调的现有模型。

##### URL
[http://arxiv.org/abs/1712.02225](http://arxiv.org/abs/1712.02225)

##### PDF
[http://arxiv.org/pdf/1712.02225](http://arxiv.org/pdf/1712.02225)

