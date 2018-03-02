---
layout: post
title: "Joint Training for Neural Machine Translation Models with Monolingual Data"
date: 2018-03-01 13:14:35
categories: arXiv_CL
tags: arXiv_CL Optimization NMT
author: Zhirui Zhang, Shujie Liu, Mu Li, Ming Zhou, Enhong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Monolingual data have been demonstrated to be helpful in improving translation quality of both statistical machine translation (SMT) systems and neural machine translation (NMT) systems, especially in resource-poor or domain adaptation tasks where parallel data are not rich enough. In this paper, we propose a novel approach to better leveraging monolingual data for neural machine translation by jointly learning source-to-target and target-to-source NMT models for a language pair with a joint EM optimization method. The training process starts with two initial NMT models pre-trained on parallel data for each direction, and these two models are iteratively updated by incrementally decreasing translation losses on training data. In each iteration step, both NMT models are first used to translate monolingual data from one language to the other, forming pseudo-training data of the other NMT model. Then two new NMT models are learnt from parallel data together with the pseudo training data. Both NMT models are expected to be improved and better pseudo-training data can be generated in next step. Experiment results on Chinese-English and English-German translation tasks show that our approach can simultaneously improve translation quality of source-to-target and target-to-source models, significantly outperforming strong baseline systems which are enhanced with monolingual data for model training including back-translation.

##### Abstract (translated by Google)
单语言数据已被证明有助于提高统计机器翻译（SMT）系统和神经机器翻译（NMT）系统的翻译质量，尤其是在资源匮乏或平行数据不够丰富的领域适应任务中。在本文中，我们提出了一种新的方法来更好地利用单语数据进行神经机器翻译，通过联合学习源到目标和目标到源NMT模型，用联合EM优化方法对语言对。训练过程从对每个方向的并行数据预先训练的两个初始NMT模型开始，并且这两个模型通过递减地减少训练数据上的平移损失而被迭代地更新。在每个迭代步骤中，两个NMT模型首先用于将单语言数据从一种语言翻译成另一种语言，形成另一种NMT模型的伪训练数据。然后从并行数据和伪训练数据中学习两个新的NMT模型。预计NMT模型都将得到改进，并且可以在下一步中生成更好的伪训练数据。中英文和英德翻译任务的实验结果表明，我们的方法可以同时提高源到目标和目标到源模型的翻译质量，明显优于强化基线系统，这些系统通过模型训练包括单语数据得到增强，包括回译。

##### URL
[https://arxiv.org/abs/1803.00353](https://arxiv.org/abs/1803.00353)

##### PDF
[https://arxiv.org/pdf/1803.00353](https://arxiv.org/pdf/1803.00353)

