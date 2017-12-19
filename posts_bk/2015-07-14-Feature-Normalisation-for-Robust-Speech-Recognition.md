---
layout: post
title: "Feature Normalisation for Robust Speech Recognition"
date: 2015-07-14 20:34:16
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Relation Recognition
author: D. S. Pavan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
Speech recognition system performance degrades in noisy environments. If the acoustic models are built using features of clean utterances, the features of a noisy test utterance would be acoustically mismatched with the trained model. This gives poor likelihoods and poor recognition accuracy. Model adaptation and feature normalisation are two broad areas that address this problem. While the former often gives better performance, the latter involves estimation of lesser number of parameters, making the system feasible for practical implementations. This research focuses on the efficacies of various subspace, statistical and stereo based feature normalisation techniques. A subspace projection based method has been investigated as a standalone and adjunct technique involving reconstruction of noisy speech features from a precomputed set of clean speech building-blocks. The building blocks are learned using non-negative matrix factorisation (NMF) on log-Mel filter bank coefficients, which form a basis for the clean speech subspace. The work provides a detailed study on how the method can be incorporated into the extraction process of Mel-frequency cepstral coefficients. Experimental results show that the new features are robust to noise, and achieve better results when combined with the existing techniques. The work also proposes a modification to the training process of SPLICE algorithm for noise robust speech recognition. It is based on feature correlations, and enables this stereo-based algorithm to improve the performance in all noise conditions, especially in unseen cases. Further, the modified framework is extended to work for non-stereo datasets where clean and noisy training utterances, but not stereo counterparts, are required. An MLLR-based computationally efficient run-time noise adaptation method in SPLICE framework has been proposed.

##### Abstract (translated by Google)
语音识别系统在嘈杂的环境中性能下降。如果声学模型是使用干净的话语的特征建立的，那么嘈杂的测试话语的特征将与训练的模型在声学上不匹配。这给出了差的可能性和差的识别精度。模型适应和特征规范化是解决这个问题的两大领域。虽然前者通常会提供更好的性能，后者涉及估计更少的参数，使得系统在实际实施中可行。这项研究的重点是各种子空间，统计和基于立体声的功能归一化技术的功效。已经将基于子空间投影的方法作为独立和附属技术进行了研究，涉及从预先计算的一组干净的语音构建块中重构有噪声的语音特征。通过在log-Mel滤波器组系数上使用非负矩阵因式分解（NMF）来学习构建模块，这构成了干净语音子空间的基础。这项工作提供了一个详细的研究如何将这个方法结合到Mel频率倒谱系数的提取过程中。实验结果表明，新特征对噪声有较强的鲁棒性，并与现有技术相结合，取得了较好的效果。该工作还提出了对SPLICE算法进行噪声鲁棒语音识别的训练过程的修改。它基于特征相关性，并且使得这种基于立体的算法能够改善所有噪声条件下的性能，特别是在看不见的情况下。此外，修改后的框架被扩展用于非立体数据集，其中需要干净且有噪声的训练话语，但不需要立体声对话。已经提出了在SPLICE框架中基于MLLR的计算有效的运行时间噪声适应方法。

##### URL
[https://arxiv.org/abs/1507.04019](https://arxiv.org/abs/1507.04019)

##### PDF
[https://arxiv.org/pdf/1507.04019](https://arxiv.org/pdf/1507.04019)

