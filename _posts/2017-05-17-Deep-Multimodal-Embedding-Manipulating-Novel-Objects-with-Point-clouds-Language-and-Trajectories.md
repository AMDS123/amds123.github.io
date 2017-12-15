---
layout: post
title: "Deep Multimodal Embedding: Manipulating Novel Objects with Point-clouds, Language and Trajectories"
date: 2017-05-17 15:12:33
categories: arXiv_CV
tags: arXiv_CV Embedding Inference
author: Jaeyong Sung, Ian Lenz, Ashutosh Saxena
mathjax: true
---

* content
{:toc}

##### Abstract
A robot operating in a real-world environment needs to perform reasoning over a variety of sensor modalities such as vision, language and motion trajectories. However, it is extremely challenging to manually design features relating such disparate modalities. In this work, we introduce an algorithm that learns to embed point-cloud, natural language, and manipulation trajectory data into a shared embedding space with a deep neural network. To learn semantically meaningful spaces throughout our network, we use a loss-based margin to bring embeddings of relevant pairs closer together while driving less-relevant cases from different modalities further apart. We use this both to pre-train its lower layers and fine-tune our final embedding space, leading to a more robust representation. We test our algorithm on the task of manipulating novel objects and appliances based on prior experience with other objects. On a large dataset, we achieve significant improvements in both accuracy and inference time over the previous state of the art. We also perform end-to-end experiments on a PR2 robot utilizing our learned embedding space.

##### Abstract (translated by Google)
在真实环境中操作的机器人需要对诸如视觉，语言和运动轨迹等各种传感器模态进行推理。但是，手动设计与这种不同模式有关的特征是非常具有挑战性的。在这项工作中，我们介绍一种算法，学习将点云，自然语言和操纵轨迹数据嵌入到具有深度神经网络的共享嵌入空间中。为了在我们的网络中学习语义上有意义的空间，我们使用基于损失的边界来将相关对的嵌入放在一起，同时将不相关的情况从不同的模式进一步分开。我们使用这两者来预先训练其较低层并微调我们的最终嵌入空间，导致更强健的表示。我们测试我们的算法，基于以前的经验与其他对象操纵新的对象和设备的任务。在一个大的数据集上，我们在精确度和推理时间方面取得了显着的改善。我们还利用我们学过的嵌入空间，对PR2机器人进行了端到端的实验。

##### URL
[https://arxiv.org/abs/1509.07831](https://arxiv.org/abs/1509.07831)

##### PDF
[https://arxiv.org/pdf/1509.07831](https://arxiv.org/pdf/1509.07831)

