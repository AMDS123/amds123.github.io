---
layout: post
title: "KBGAN: Adversarial Learning for Knowledge Graph Embeddings"
date: 2018-02-20 01:31:45
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge_Graph Knowledge GAN Embedding Prediction
author: Liwei Cai, William Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce KBGAN, an adversarial learning framework to improve the performances of a wide range of existing knowledge graph embedding models. Because knowledge graphs typically only contain positive facts, sampling useful negative training examples is a non-trivial task. Replacing the head or tail entity of a fact with a uniformly randomly selected entity is a conventional method for generating negative facts, but the majority of the generated negative facts can be easily discriminated from positive facts, and will contribute little towards the training. Inspired by generative adversarial networks (GANs), we use one knowledge graph embedding model as a negative sample generator to assist the training of our desired model, which acts as the discriminator in GANs. This framework is independent of the concrete form of generator and discriminator, and therefore can utilize a wide variety of knowledge graph embedding models as its building blocks. In experiments, we adversarially train two translation-based models, TransE and TransD, each with assistance from one of the two probability-based models, DistMult and ComplEx. We evaluate the performances of KBGAN on the link prediction task, using three knowledge base completion datasets: FB15k-237, WN18 and WN18RR. Experimental results show that adversarial training substantially improves the performances of target embedding models under various settings.

##### Abstract (translated by Google)
我们介绍KBGAN，这是一种敌对学习框架，用于改善现有知识图嵌入模型的性能。由于知识图通常只包含积极的事实，因此抽样有用的负面训练示例是一项不重要的任务。用统一随机选择的实体来替换事实的头部或尾部实体是产生负面事实的常规方法，但是大部分生成的负面事实可以容易地与积极事实区分开来，并且对于培训没有多大贡献。受到生成对抗网络（GAN）的启发，我们使用一个知识图嵌入模型作为负样本生成器来协助训练我们所需的模型，该模型充当GAN中的鉴别器。该框架独立于发生器和鉴别器的具体形式，因此可以利用各种各样的知识图嵌入模型作为其构建块。在实验中，我们对两种基于翻译的模型TransE和TransD进行对抗训练，每种模型都得到两种基于概率模型DistMult和ComplEx之一的帮助。我们使用三个知识库完成数据集：FB15k-237，WN18和WN18RR评估KBGAN在链接预测任务上的表现。实验结果表明，敌对训练可以显着提高不同场景下目标嵌入模型的性能。

##### URL
[http://arxiv.org/abs/1711.04071](http://arxiv.org/abs/1711.04071)

##### PDF
[http://arxiv.org/pdf/1711.04071](http://arxiv.org/pdf/1711.04071)

