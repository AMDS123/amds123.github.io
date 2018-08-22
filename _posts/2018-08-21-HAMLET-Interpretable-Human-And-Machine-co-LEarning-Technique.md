---
layout: post
title: "HAMLET: Interpretable Human And Machine co-LEarning Technique"
date: 2018-08-21 05:41:09
categories: arXiv_AI
tags: arXiv_AI Embedding Classification Deep_Learning
author: Olivier Deiss, Siddharth Biswal, Jing Jin, Haoqi Sun, M. Brandon Westover, Jimeng Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient label acquisition processes are key to obtaining robust classifiers. However, data labeling is often challenging and subject to high levels of label noise. This can arise even when classification targets are well defined, if instances to be labeled are more difficult than the prototypes used to define the class, leading to disagreements among the expert community. Here, we enable efficient training of deep neural networks. From low-confidence labels, we iteratively improve their quality by simultaneous learning of machines and experts. We call it Human And Machine co-LEarning Technique (HAMLET). Throughout the process, experts become more consistent, while the algorithm provides them with explainable feedback for confirmation. HAMLET uses a neural embedding function and a memory module filled with diverse reference embeddings from different classes. Its output includes classification labels and highly relevant reference embeddings as explanation. We took the study of brain monitoring at intensive care unit (ICU) as an application of HAMLET on continuous electroencephalography (cEEG) data. Although cEEG monitoring yields large volumes of data, labeling costs and difficulty make it hard to build a classifier. Additionally, while experts agree on the labels of clear-cut examples of cEEG patterns, labeling many real-world cEEG data can be extremely challenging. Thus, a large minority of sequences might be mislabeled. HAMLET has shown significant performance gain against deep learning and other baselines, increasing accuracy from 7.03% to 68.75% on challenging inputs. Besides improved performance, clinical experts confirmed the interpretability of those reference embeddings in helping explaining the classification results by HAMLET.

##### Abstract (translated by Google)
高效的标签获取过程是获得稳健分类器的关键。然而，数据标签通常具有挑战性并且受到高标签噪声的影响。即使分类目标定义明确，如果要标记的实例比用于定义类的原型更难，也会导致专家社区之间的分歧。在这里，我们实现了深度神经网络的有效训练。从低可靠性标签，我们通过同时学习机器和专家来迭代地提高其质量。我们称之为人与机器共同学习技术（HAMLET）。在整个过程中，专家变得更加一致，而算法为他们提供了可解释的反馈以供确认。 HAMLET使用神经嵌入函数和内存模块，其中填充了来自不同类的不同参考嵌入。其输出包括分类标签和高度相关的参考嵌入作为解释。我们将重症监护室（ICU）的脑监测研究作为HAMLET在连续脑电图（cEEG）数据上的应用。虽然cEEG监控会产生大量数据，但标签成本和难度使得构建分类器变得困难。此外，虽然专家们就清晰的cEEG模式示例的标签达成一致意见，但标记许多真实世界的cEEG数据可能极具挑战性。因此，大部分序列可能被错误标记。 HAMLET在深度学习和其他基线方面表现出显着的性能提升，在具有挑战性的输入上将准确率从7.03％提高到68.75％。除了提高性能外，临床专家还证实了这些参考嵌入的可解释性，有助于解释HAMLET的分类结果。

##### URL
[http://arxiv.org/abs/1803.09702](http://arxiv.org/abs/1803.09702)

##### PDF
[http://arxiv.org/pdf/1803.09702](http://arxiv.org/pdf/1803.09702)

