---
layout: post
title: "End-to-End Learning of Motion Representation for Video Understanding"
date: 2018-04-02 06:40:37
categories: arXiv_CV
tags: arXiv_CV Video_Caption Action_Recognition Optimization Recognition
author: Lijie Fan, Wenbing Huang, Chuang Gan, Stefano Ermon, Boqing Gong, Junzhou Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success of end-to-end learned representations, hand-crafted optical flow features are still widely used in video analysis tasks. To fill this gap, we propose TVNet, a novel end-to-end trainable neural network, to learn optical-flow-like features from data. TVNet subsumes a specific optical flow solver, the TV-L1 method, and is initialized by unfolding its optimization iterations as neural layers. TVNet can therefore be used directly without any extra learning. Moreover, it can be naturally concatenated with other task-specific networks to formulate an end-to-end architecture, thus making our method more efficient than current multi-stage approaches by avoiding the need to pre-compute and store features on disk. Finally, the parameters of the TVNet can be further fine-tuned by end-to-end training. This enables TVNet to learn richer and task-specific patterns beyond exact optical flow. Extensive experiments on two action recognition benchmarks verify the effectiveness of the proposed approach. Our TVNet achieves better accuracies than all compared methods, while being competitive with the fastest counterpart in terms of features extraction time.

##### Abstract (translated by Google)
尽管端到端学习代表最近取得了成功，但手工制作的光流特征仍广泛用于视频分析任务。为了填补这一空白，我们提出了一个新颖的端到端可训练神经网络TVNet，以从数据中学习类似光流的特征。 TVNet包含特定的光流解算器，即TV-L1方法，并且通过将其优化迭代展开为神经层来进行初始化。 TVNet因此可以直接使用，无需任何额外的学习。此外，它可以自然地与其他任务特定的网络串联起来，以制定端到端的体系结构，从而使我们的方法比当前的多阶段方法更有效，避免了在磁盘上预先计算和存储功能的需要。最后，TVNet的参数可以通过端到端培训进一步调整。这使得TVNet能够在精确的光学流程之外学习更丰富和特定任务的模式。在两个动作识别基准上的大量实验验证了所提出的方法的有效性。我们的TVNet比所有比较方法的准确度更高，同时在特征提取时间方面与最快的对手相比具有竞争力。

##### URL
[http://arxiv.org/abs/1804.00413](http://arxiv.org/abs/1804.00413)

##### PDF
[http://arxiv.org/pdf/1804.00413](http://arxiv.org/pdf/1804.00413)

