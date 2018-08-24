---
layout: post
title: "TreeGAN: Syntax-Aware Sequence Generation with Generative Adversarial Networks"
date: 2018-08-22 22:32:34
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Image_Generation RNN
author: Xinyue Liu, Xiangnan Kong, Lei Liu, Kuorong Chiang
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have shown great capacity on image generation, in which a discriminative model guides the training of a generative model to construct images that resemble real images. Recently, GANs have been extended from generating images to generating sequences (e.g., poems, music and codes). Existing GANs on sequence generation mainly focus on general sequences, which are grammar-free. In many real-world applications, however, we need to generate sequences in a formal language with the constraint of its corresponding grammar. For example, to test the performance of a database, one may want to generate a collection of SQL queries, which are not only similar to the queries of real users, but also follow the SQL syntax of the target database. Generating such sequences is highly challenging because both the generator and discriminator of GANs need to consider the structure of the sequences and the given grammar in the formal language. To address these issues, we study the problem of syntax-aware sequence generation with GANs, in which a collection of real sequences and a set of pre-defined grammatical rules are given to both discriminator and generator. We propose a novel GAN framework, namely TreeGAN, to incorporate a given Context-Free Grammar (CFG) into the sequence generation process. In TreeGAN, the generator employs a recurrent neural network (RNN) to construct a parse tree. Each generated parse tree can then be translated to a valid sequence of the given grammar. The discriminator uses a tree-structured RNN to distinguish the generated trees from real trees. We show that TreeGAN can generate sequences for any CFG and its generation fully conforms with the given syntax. Experiments on synthetic and real data sets demonstrated that TreeGAN significantly improves the quality of the sequence generation in context-free languages.

##### Abstract (translated by Google)
生成性对抗网络（GAN）已经显示出巨大的图像生成能力，其中判别模型指导生成模型的训练以构建类似于真实图像的图像。最近，GAN已经从生成图像扩展到生成序列（例如，诗歌，音乐和代码）。关于序列生成的现有GAN主要关注于无语法的一般序列。然而，在许多现实世界的应用程序中，我们需要使用其相应语法的约束以正式语言生成序列。例如，要测试数据库的性能，可能需要生成一组SQL查询，这些查询不仅类似于真实用户的查询，还遵循目标数据库的SQL语法。生成这样的序列是非常具有挑战性的，因为GAN的生成器和鉴别器需要在形式语言中考虑序列的结构和给定的语法。为了解决这些问题，我们研究了使用GAN进行语法感知序列生成的问题，其中将一组实际序列和一组预定义的语法规则给予鉴别器和生成器。我们提出了一种新颖的GAN框架，即TreeGAN，将给定的无上下文语法（CFG）合并到序列生成过程中。在TreeGAN中，生成器使用递归神经网络（RNN）来构造解析树。然后可以将每个生成的解析树转换为给定语法的有效序列。鉴别器使用树形结构的RNN来区分生成的树和真实的树。我们证明TreeGAN可以为任何CFG生成序列，并且它的生成完全符合给定的语法。对合成和实际数据集的实验表明，TreeGAN显着提高了无上下文语言中序列生成的质量。

##### URL
[http://arxiv.org/abs/1808.07582](http://arxiv.org/abs/1808.07582)

##### PDF
[http://arxiv.org/pdf/1808.07582](http://arxiv.org/pdf/1808.07582)

