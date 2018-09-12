---
layout: post
title: "Learning Named Entity Tagger using Domain-Specific Dictionary"
date: 2018-09-10 21:15:30
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Jingbo Shang, Liyuan Liu, Xiang Ren, Xiaotao Gu, Teng Ren, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep neural models allow us to build reliable named entity recognition (NER) systems without handcrafting features. However, such methods require large amounts of manually-labeled training data. There have been efforts on replacing human annotations with distant supervision (in conjunction with external dictionaries), but the generated noisy labels pose significant challenges on learning effective neural models. Here we propose two neural models to suit noisy distant supervision from the dictionary. First, under the traditional sequence labeling framework, we propose a revised fuzzy CRF layer to handle tokens with multiple possible labels. After identifying the nature of noisy labels in distant supervision, we go beyond the traditional framework and propose a novel, more effective neural model AutoNER with a new Tie or Break scheme. In addition, we discuss how to refine distant supervision for better NER performance. Extensive experiments on three benchmark datasets demonstrate that AutoNER achieves the best performance when only using dictionaries with no additional human effort, and delivers competitive results with state-of-the-art supervised benchmarks.

##### Abstract (translated by Google)
深度神经模型的最新进展使我们能够构建可靠的命名实体识别（NER）系统而无需手工制作功能。然而，这些方法需要大量手动标记的训练数据。已经努力用远程监督（与外部词典结合）替换人类注释，但是生成的噪声标签对学习有效的神经模型提出了重大挑战。在这里，我们提出了两种神经模型，以适应字典中的嘈杂远程监督。首先，在传统的序列标签框架下，我们提出了一个修正的模糊CRF层来处理具有多个可能标签的令牌。在远程监督中识别出嘈杂标签的性质后，我们超越了传统的框架，并提出了一种新的，更有效的神经模型AutoNER，并采用了新的Tie或Break方案。此外，我们还讨论如何改进远程监督以获得更好的NER性能。对三个基准数据集进行的大量实验表明，只使用字典而无需额外的人力工作，AutoNER可实现最佳性能，并通过最先进的监督基准测试提供有竞争力的结果。

##### URL
[http://arxiv.org/abs/1809.03599](http://arxiv.org/abs/1809.03599)

##### PDF
[http://arxiv.org/pdf/1809.03599](http://arxiv.org/pdf/1809.03599)

