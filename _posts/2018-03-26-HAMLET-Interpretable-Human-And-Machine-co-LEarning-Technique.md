---
layout: post
title: "HAMLET: Interpretable Human And Machine co-LEarning Technique"
date: 2018-03-26 16:29:03
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
有效的标签获取过程是获得健壮的分类器的关键。然而，数据标签通常是具有挑战性的，并且受到高水平标签噪音的影响。即使在分类目标明确定义的情况下，如果要标记的实例比用于定义类别的原型更难，导致专家群体之间的分歧，也会出现这种情况。在这里，我们实现了对深度神经网络的有效训练。从低信度标签，我们通过同时学习机器和专家来反复提高质量。我们称之为人机联合学习技术（HAMLET）。在整个过程中，专家们变得更加一致，而算法为他们提供可解释的反馈以供确认。 HAMLET使用一个神经嵌入函数和一个内存模块，内嵌来自不同类别的不同参考嵌入。其输出包括分类标签和高度相关的参考嵌入作为解释。我们将重症监护室（ICU）的脑监测研究作为HAMLET在连续脑电图（cEEG）数据中的应用。虽然cEEG监测产生大量数据，但标记成本和难度使得难以建立分类器。此外，尽管专家们对cEEG模式清晰标注的标签达成了一致，但为许多真实世界的cEEG数据添加标签可能非常具有挑战性。因此，大量的序列可能被错误标记。 HAMLET在深度学习和其他基线方面表现出显着的性能提升，将挑战性输入的准确性从7.03％提高到68.75％。除了改进的表现外，临床专家还确认了这些参考嵌入的解释性，帮助解释HAMLET的分类结果。

##### URL
[https://arxiv.org/abs/1803.09702](https://arxiv.org/abs/1803.09702)

##### PDF
[https://arxiv.org/pdf/1803.09702](https://arxiv.org/pdf/1803.09702)

