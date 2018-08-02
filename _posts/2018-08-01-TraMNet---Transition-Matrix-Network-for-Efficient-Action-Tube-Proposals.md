---
layout: post
title: "TraMNet - Transition Matrix Network for Efficient Action Tube Proposals"
date: 2018-08-01 12:33:57
categories: arXiv_CV
tags: arXiv_CV Sparse Detection
author: Gurkirt Singh, Suman Saha, Fabio Cuzzolin
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art methods solve spatiotemporal action localisation by extending 2D anchors to 3D-cuboid proposals on stacks of frames, to generate sets of temporally connected bounding boxes called \textit{action micro-tubes}. However, they fail to consider that the underlying anchor proposal hypotheses should also move (transition) from frame to frame, as the actor or the camera does. Assuming we evaluate $n$ 2D anchors in each frame, then the number of possible transitions from each 2D anchor to the next, for a sequence of $f$ consecutive frames, is in the order of $O(n^f)$, expensive even for small values of $f$. To avoid this problem, we introduce a Transition-Matrix-based Network (TraMNet) which relies on computing transition probabilities between anchor proposals while maximising their overlap with ground truth bounding boxes across frames, and enforcing sparsity via a transition threshold. As the resulting transition matrix is sparse and stochastic, this reduces the proposal hypothesis search space from $O(n^f)$ to the cardinality of the thresholded matrix. At training time, transitions are specific to cell locations of the feature maps, so that a sparse (efficient) transition matrix is used to train the network. At test time, a denser transition matrix can be obtained either by decreasing the threshold or by adding to it all the relative transitions originating from any cell location, allowing the network to handle transitions in the test data that might not have been present in the training data, and making detection translation-invariant. Finally, we show that our network can handle sparse annotations such as those available in the DALY dataset. We report extensive experiments on the DALY, UCF101-24 and Transformed-UCF101-24 datasets to support our claims.

##### Abstract (translated by Google)
当前最先进的方法通过将2D锚点扩展到帧堆栈上的3D立方体建议来解决时空动作定位，以生成称为\ textit {动作微管}的时间上连接的边界框的集合。然而，他们没有考虑到底层锚定建议假设也应该像演员或摄像机那样在帧之间移动（转换）。假设我们在每个帧中评估$ n $ 2D锚点，那么对于$ f $连续帧的序列，从每个2D锚点到下一个锚点的可能转换的数量是$ O（n ^ f）$，即使是$ f $的小值也很贵。为了避免这个问题，我们引入了一个基于过渡矩阵的网络（TraMNet），它依赖于计算锚定建议之间的转移概率，同时最大化它们与帧间地面真实边界框的重叠，并通过转换阈值强制实现稀疏性。由于得到的转移矩阵是稀疏和随机的，这将提议假设搜索空间从$ O（n ^ f）$减少到阈值矩阵的基数。在训练时，转换特定于特征映射的单元位置，因此使用稀疏（有效）转换矩阵来训练网络。在测试时，可以通过降低阈值或通过向其添加源自任何单元位置的所有相对转换来获得更密集的转换矩阵，从而允许网络处理可能不存在于训练中的测试数据中的转换。数据，并使检测翻译不变。最后，我们展示了我们的网络可以处理稀疏注释，例如DALY数据集中可用的注释。我们在DALY，UCF101-24和Transformed-UCF101-24数据集上报告了大量实验，以支持我们的声明。

##### URL
[https://arxiv.org/abs/1808.00297](https://arxiv.org/abs/1808.00297)

##### PDF
[https://arxiv.org/pdf/1808.00297](https://arxiv.org/pdf/1808.00297)

