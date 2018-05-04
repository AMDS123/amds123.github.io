---
layout: post
title: "Multi-Context Label Embedding"
date: 2018-05-03 10:08:51
categories: arXiv_CV
tags: arXiv_CV Embedding Image_Classification Classification
author: Yaxin Shi, Donna Xu, Yuangang Pan, Ivor W. Tsang
mathjax: true
---

* content
{:toc}

##### Abstract
Label embedding plays an important role in zero-shot learning. Side information such as attributes, semantic text representations, and label hierarchy are commonly used as the label embedding in zero-shot classification tasks. However, the label embedding used in former works considers either only one single context of the label, or multiple contexts without dependency. Therefore, different contexts of the label may not be well aligned in the embedding space to preserve the relatedness between labels, which will result in poor interpretability of the label embedding. In this paper, we propose a Multi-Context Label Embedding (MCLE) approach to incorporate multiple label contexts, e.g., label hierarchy and attributes, within a unified matrix factorization framework. To be specific, we model each single context by a matrix factorization formula and introduce a shared variable to capture the dependency among different contexts. Furthermore, we enforce sparsity constraint on our multi-context framework to strengthen the interpretability of the learned label embedding. Extensive experiments on two real-world datasets demonstrate the superiority of our MCLE in label description and zero-shot image classification.

##### Abstract (translated by Google)
标签嵌入在零点学习中起着重要作用。辅助信息（如属性，语义文本表示和标签层次结构）通常用作零点分类任务中的标签嵌入。但是，以前的作品中使用的标签嵌入只考虑标签的单个上下文，或者没有依赖性的多个上下文。因此，标签的不同上下文可能无法在嵌入空间中很好地对齐以保持标签之间的相关性，这将导致标签嵌入的可解释性差。在本文中，我们提出了一种多上下文标签嵌入（MCLE）方法，将多个标签上下文（例如，标签层次结构和属性）并入一个统一的矩阵分解框架中。具体而言，我们通过矩阵分解公式为每个单独的上下文建模，并引入一个共享变量来捕获不同上下文之间的依赖关系。此外，我们对我们的多语境框架实施稀疏约束，以加强学习标签嵌入的可解释性。在两个真实世界的数据集上的大量实验证明了我们的MCLE在标签描述和零镜头图像分类方面的优越性。

##### URL
[http://arxiv.org/abs/1805.01199](http://arxiv.org/abs/1805.01199)

##### PDF
[http://arxiv.org/pdf/1805.01199](http://arxiv.org/pdf/1805.01199)

