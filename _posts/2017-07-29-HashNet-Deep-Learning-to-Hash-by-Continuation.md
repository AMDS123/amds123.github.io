---
layout: post
title: "HashNet: Deep Learning to Hash by Continuation"
date: 2017-07-29 17:55:50
categories: arXiv_CV
tags: arXiv_CV Attention Represenation_Learning Optimization Deep_Learning
author: Zhangjie Cao, Mingsheng Long, Jianmin Wang, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to hash has been widely applied to approximate nearest neighbor search for large-scale multimedia retrieval, due to its computation efficiency and retrieval quality. Deep learning to hash, which improves retrieval quality by end-to-end representation learning and hash encoding, has received increasing attention recently. Subject to the ill-posed gradient difficulty in the optimization with sign activations, existing deep learning to hash methods need to first learn continuous representations and then generate binary hash codes in a separated binarization step, which suffer from substantial loss of retrieval quality. This work presents HashNet, a novel deep architecture for deep learning to hash by continuation method with convergence guarantees, which learns exactly binary hash codes from imbalanced similarity data. The key idea is to attack the ill-posed gradient problem in optimizing deep networks with non-smooth binary activations by continuation method, in which we begin from learning an easier network with smoothed activation function and let it evolve during the training, until it eventually goes back to being the original, difficult to optimize, deep network with the sign activation function. Comprehensive empirical evidence shows that HashNet can generate exactly binary hash codes and yield state-of-the-art multimedia retrieval performance on standard benchmarks.

##### Abstract (translated by Google)
哈希学习算法由于其计算效率和检索质量，已被广泛应用于大规模多媒体检索的近似最近邻搜索。深度学习哈希，通过端到端表示学习和哈希编码提高检索质量，近来越来越受到关注。受到符号激活优化中的不适定梯度困难的影响，现有的对哈希方法的深度学习需要先学习连续表示，然后在分离的二值化步骤中产生二进制哈希码，其遭受检索质量的显着损失。本文提出了一种新的深度学习的深度学习HashNet，采用具有收敛性保证的连续方法进行散列学习，从不平衡相似性数据中准确学习二进制散列码。关键的思想是通过连续方法攻击非光滑二元激活优化深度网络中的不适定梯度问题，其中我们从学习一个更加容易的平滑激活函数网络开始，让它在训练过程中进化，直到它最终回归原来的，难以优化的，具有标志激活功能的深层网络。全面的经验证据表明，HashNet可以生成准确的二进制散列码，并在标准基准测试中获得最先进的多媒体检索性能。

##### URL
[https://arxiv.org/abs/1702.00758](https://arxiv.org/abs/1702.00758)

##### PDF
[https://arxiv.org/pdf/1702.00758](https://arxiv.org/pdf/1702.00758)

