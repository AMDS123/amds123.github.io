---
layout: post
title: "Optimizing affinity-based binary hashing using auxiliary coordinates"
date: 2016-02-05 01:25:26
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Optimization
author: Ramin Raziperchikolaei, Miguel Á. Carreira-Perpiñán
mathjax: true
---

* content
{:toc}

##### Abstract
In supervised binary hashing, one wants to learn a function that maps a high-dimensional feature vector to a vector of binary codes, for application to fast image retrieval. This typically results in a difficult optimization problem, nonconvex and nonsmooth, because of the discrete variables involved. Much work has simply relaxed the problem during training, solving a continuous optimization, and truncating the codes a posteriori. This gives reasonable results but is quite suboptimal. Recent work has tried to optimize the objective directly over the binary codes and achieved better results, but the hash function was still learned a posteriori, which remains suboptimal. We propose a general framework for learning hash functions using affinity-based loss functions that uses auxiliary coordinates. This closes the loop and optimizes jointly over the hash functions and the binary codes so that they gradually match each other. The resulting algorithm can be seen as a corrected, iterated version of the procedure of optimizing first over the codes and then learning the hash function. Compared to this, our optimization is guaranteed to obtain better hash functions while being not much slower, as demonstrated experimentally in various supervised datasets. In addition, our framework facilitates the design of optimization algorithms for arbitrary types of loss and hash functions.

##### Abstract (translated by Google)
在受监督的二进制散列中，人们想要学习将高维特征向量映射到二进制代码向量的函数，以用于快速图像检索。由于涉及的离散变量，这通常导致难以优化的问题，非凸和非平滑。在训练过程中，许多工作只是放松了问题，解决了连续的优化问题，并且后面的代码被截断了。这给出了合理的结果，但相当不理想。最近的工作试图直接在二进制代码上优化目标，并取得了较好的结果，但哈希函数仍然是后天学习的，这仍然是不理想的。我们提出了一个使用基于亲和力的损失函数来学习使用辅助坐标的散列函数的通用框架。这将关闭循环并在散列函数和二进制代码上进行联合优化，以使它们逐渐匹配。所得到的算法可以被看作是对代码进行优化然后学习哈希函数的过程的校正的迭代版本。相比之下，我们的优化是保证获得更好的哈希函数，而不是太慢，如在各种监督数据集实验证明。此外，我们的框架有助于设计任意类型的损失和散列函数的优化算法。

##### URL
[https://arxiv.org/abs/1501.05352](https://arxiv.org/abs/1501.05352)

##### PDF
[https://arxiv.org/pdf/1501.05352](https://arxiv.org/pdf/1501.05352)

