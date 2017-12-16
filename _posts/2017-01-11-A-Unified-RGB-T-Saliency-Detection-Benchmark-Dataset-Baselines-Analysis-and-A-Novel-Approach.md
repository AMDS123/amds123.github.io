---
layout: post
title: "A Unified RGB-T Saliency Detection Benchmark: Dataset, Baselines, Analysis and A Novel Approach"
date: 2017-01-11 02:38:23
categories: arXiv_CV
tags: arXiv_CV Salient Optimization Detection
author: Chenglong Li, Guizhao Wang, Yunpeng Ma, Aihua Zheng, Bin Luo, Jin Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant progress, image saliency detection still remains a challenging task in complex scenes and environments. Integrating multiple different but complementary cues, like RGB and Thermal (RGB-T), may be an effective way for boosting saliency detection performance. The current research in this direction, however, is limited by the lack of a comprehensive benchmark. This work contributes such a RGB-T image dataset, which includes 821 spatially aligned RGB-T image pairs and their ground truth annotations for saliency detection purpose. The image pairs are with high diversity recorded under different scenes and environmental conditions, and we annotate 11 challenges on these image pairs for performing the challenge-sensitive analysis for different saliency detection algorithms. We also implement 3 kinds of baseline methods with different modality inputs to provide a comprehensive comparison platform. With this benchmark, we propose a novel approach, multi-task manifold ranking with cross-modality consistency, for RGB-T saliency detection. In particular, we introduce a weight for each modality to describe the reliability, and integrate them into the graph-based manifold ranking algorithm to achieve adaptive fusion of different source data. Moreover, we incorporate the cross-modality consistent constraints to integrate different modalities collaboratively. For the optimization, we design an efficient algorithm to iteratively solve several subproblems with closed-form solutions. Extensive experiments against other baseline methods on the newly created benchmark demonstrate the effectiveness of the proposed approach, and we also provide basic insights and potential future research directions for RGB-T saliency detection.

##### Abstract (translated by Google)
尽管取得了重大进展，但在复杂的场景和环境中，图像显着性检测仍然是一项具有挑战性的任务集成多种不同但互补的线索，如RGB和热（RGB-T），可能是提高显着性检测性能的有效方法。但是，目前这方面的研究受到缺乏综合基准的限制。这项工作贡献了这样一个RGB-T图像数据集，其中包括821空间对齐的RGB-T图像对和他们的地面真实注释为显着性检测的目的。在不同的场景和环境条件下记录的图像对具有很高的差异性，我们在这些图像对上标注了11个挑战，对不同的显着性检测算法进行挑战敏感的分析。我们还实施3种不同形式输入的基线方法，提供一个综合的比较平台。通过这个基准，我们提出了一种新的方法，多模式一致性的多任务流形排序，用于RGB-T显着性检测。具体来说，我们引入一个权重来描述可靠性，并将其集成到基于图的流形排序算法中，以实现不同源数据的自适应融合。此外，我们将跨模式一致的约束纳入到不同的模式之中。为了优化，我们设计了一个高效的算法来迭代求解几个子问题的闭式解。在新创建的基准上针对其他基准方法进行的大量实验证明了所提出的方法的有效性，同时也为RGB-T显着性检测提供了基本的见解和潜在的未来研究方向。

##### URL
[https://arxiv.org/abs/1701.02829](https://arxiv.org/abs/1701.02829)

##### PDF
[https://arxiv.org/pdf/1701.02829](https://arxiv.org/pdf/1701.02829)

