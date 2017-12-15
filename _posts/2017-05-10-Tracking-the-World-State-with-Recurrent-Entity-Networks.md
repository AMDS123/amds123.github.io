---
layout: post
title: "Tracking the World State with Recurrent Entity Networks"
date: 2017-05-10 16:52:56
categories: arXiv_CL
tags: arXiv_CL Tracking
author: Mikael Henaff, Jason Weston, Arthur Szlam, Antoine Bordes, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new model, the Recurrent Entity Network (EntNet). It is equipped with a dynamic long-term memory which allows it to maintain and update a representation of the state of the world as it receives new data. For language understanding tasks, it can reason on-the-fly as it reads text, not just when it is required to answer a question or respond as is the case for a Memory Network (Sukhbaatar et al., 2015). Like a Neural Turing Machine or Differentiable Neural Computer (Graves et al., 2014; 2016) it maintains a fixed size memory and can learn to perform location and content-based read and write operations. However, unlike those models it has a simple parallel architecture in which several memory locations can be updated simultaneously. The EntNet sets a new state-of-the-art on the bAbI tasks, and is the first method to solve all the tasks in the 10k training examples setting. We also demonstrate that it can solve a reasoning task which requires a large number of supporting facts, which other methods are not able to solve, and can generalize past its training horizon. It can also be practically used on large scale datasets such as Children's Book Test, where it obtains competitive performance, reading the story in a single pass.

##### Abstract (translated by Google)
我们引入一个新的模型，即经常性实体网络（EntNet）。它配备了一个动态的长期记忆，使其能够在接收新数据时保持和更新世界状态的表示。对于语言理解任务，它可以在读取文本时即时进行推理，而不仅仅是当需要回答问题或响应时，如存储网络（Sukhbaatar et al。，2015）。像神经图灵机或差分神经计算机一样（Graves et al。，2014; 2016），它保持一个固定大小的内存，可以学习执行位置和基于内容的读写操作。然而，与这些模型不同的是，它具有简单的并行架构，其中可以同时更新多个存储器位置。 EntNet在bAbI任务上设置了一个新的最新技术，并且是第一个解决10k训练示例设置中所有任务的方法。我们还证明它可以解决一个需要大量支持事实的推理任务，而其他方法无法解决，并且可以推广到其训练视野。它也可以实际应用于大型数据集，如儿童图书测试，获得竞争性表现，一次阅读故事。

##### URL
[https://arxiv.org/abs/1612.03969](https://arxiv.org/abs/1612.03969)

##### PDF
[https://arxiv.org/pdf/1612.03969](https://arxiv.org/pdf/1612.03969)

