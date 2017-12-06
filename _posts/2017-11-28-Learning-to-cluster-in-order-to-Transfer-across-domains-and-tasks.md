---
layout: post
title: "Learning to cluster in order to Transfer across domains and tasks"
date: 2017-11-28 04:59:58
categories: arXiv_CV
tags: arXiv_CV
author: Yen-Chang Hsu, Zhaoyang Lv, Zsolt Kira
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel method to perform transfer learning across domains and tasks, formulating it as a problem of learning to cluster. The key insight is that, in addition to features, we can transfer similarity information and this is sufficient to learn a similarity function and clustering network to perform both domain adaptation and cross-task transfer learning. We begin by reducing categorical information to pairwise constraints, which only considers whether two instances belong to the same class or not. This similarity is category-agnostic and can be learned from data in the source domain using a similarity network. We then present two novel approaches for performing transfer learning using this similarity function. First, for unsupervised domain adaptation, we design a new loss function to regularize classification with a constrained clustering loss, hence learning a clustering network with the transferred similarity metric generating the training inputs. Second, for cross-task learning (i.e., unsupervised clustering with unseen categories), we propose a framework to reconstruct and estimate the number of semantic clusters, again using the clustering network. Since the similarity network is noisy, the key is to use a robust clustering algorithm, and we show that our formulation is more robust than the alternative constrained and unconstrained clustering approaches. Using this method, we first show state of the art results for the challenging cross-task problem, applied on Omniglot and ImageNet. Our results show that we can reconstruct semantic clusters with high accuracy. We then evaluate the performance of cross-domain transfer using images from the Office-31 and SVHN-MNIST tasks and present top accuracy on both datasets. Our approach doesn't explicitly deal with domain discrepancy. If we combine with a domain adaptation loss, it shows further improvement.

##### Abstract (translated by Google)
本文介绍了一种跨领域和任务进行转移学习的新方法，将其作为学习聚类的一个问题。关键的认识是，除了特征之外，我们可以传递相似性信息，这足以学习一个相似性函数和聚类网络来执行域适应和跨任务转移学习。我们首先将分类信息减少为成对约束，这只考虑两个实例是否属于同一个类。这种相似性是类别不可知的，可以使用相似性网络从源域中的数据中学习。然后，我们提出了两种使用这种相似性函数进行转换学习的新方法。首先，针对无监督域自适应，我们设计了一个新的损失函数，用约束聚类损失对分类进行正则化，从而学习一个转移相似性度量生成训练输入的聚类网络。其次，对于跨任务学习（即无监督聚类与看不见的类别），我们提出了一个框架来重建和估计语义聚类的数量，再次使用聚类网络。由于相似性网络是嘈杂的，关键是要使用一个强大的聚类算法，我们表明，我们的公式更强大比替代的约束和无约束聚类方法。使用这种方法，我们首先展示了在Omniglot和ImageNet上应用的具有挑战性的跨任务问题的最新成果。我们的结果表明，我们可以高精度地重构语义簇。然后，我们使用Office-31和SVHN-MNIST任务中的图像来评估跨域转移的性能，并在两个数据集上表现出最高的准确性。我们的方法没有明确地处理域的差异。如果我们结合一个领域适应损失，它显示进一步的改善。

##### URL
[https://arxiv.org/abs/1711.10125](https://arxiv.org/abs/1711.10125)

