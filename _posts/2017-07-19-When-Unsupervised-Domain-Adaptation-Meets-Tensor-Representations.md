---
layout: post
title: "When Unsupervised Domain Adaptation Meets Tensor Representations"
date: 2017-07-19 07:11:11
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Relation Recognition
author: Hao Lu, Lei Zhang, Zhiguo Cao, Wei Wei, Ke Xian, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaption (DA) allows machine learning methods trained on data sampled from one distribution to be applied to data sampled from another. It is thus of great practical importance to the application of such methods. Despite the fact that tensor representations are widely used in Computer Vision to capture multi-linear relationships that affect the data, most existing DA methods are applicable to vectors only. This renders them incapable of reflecting and preserving important structure in many problems. We thus propose here a learning-based method to adapt the source and target tensor representations directly, without vectorization. In particular, a set of alignment matrices is introduced to align the tensor representations from both domains into the invariant tensor subspace. These alignment matrices and the tensor subspace are modeled as a joint optimization problem and can be learned adaptively from the data using the proposed alternative minimization scheme. Extensive experiments show that our approach is capable of preserving the discriminative power of the source domain, of resisting the effects of label noise, and works effectively for small sample sizes, and even one-shot DA. We show that our method outperforms the state-of-the-art on the task of cross-domain visual recognition in both efficacy and efficiency, and particularly that it outperforms all comparators when applied to DA of the convolutional activations of deep convolutional networks.

##### Abstract (translated by Google)
域自适应（DA）允许对从一个分布采样的数据进行训练的机器学习方法应用于从另一个分布采样的数据。因此，这种方法的应用具有重要的实际意义。尽管计算机视觉中广泛使用张量表示来捕获影响数据的多线性关系，但大多数现有的DA方法仅适用于矢量。这使得他们无法在许多问题上反思和保留重要的结构。因此，我们在这里提出一种基于学习的方法来直接适应源张量表达和目标张量表示，而无需向量化。具体而言，引入一组对齐矩阵来将来自两个域的张量表示对齐到不变张量子空间中。这些对齐矩阵和张量子空间被建模为联合优化问题，并且可以使用所提出的替代最小化方案从数据中自适应学习。大量的实验表明，我们的方法能够保留源域的判别能力，抵抗标签噪声的影响，对于小样本量甚至一次性DA都能有效地工作。我们展示了我们的方法在效率和效率方面优于跨领域视觉识别任务，尤其是当它应用于深卷积网络的卷积激活的DA时，它的性能优于所有的比较器。

##### URL
[https://arxiv.org/abs/1707.05956](https://arxiv.org/abs/1707.05956)

##### PDF
[https://arxiv.org/pdf/1707.05956](https://arxiv.org/pdf/1707.05956)

