---
layout: post
title: "Randomized LU decomposition: An Algorithm for Dictionaries Construction"
date: 2015-02-17 08:18:00
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Detection
author: Aviv Rotbart, Gil Shabat, Yaniv Shmueli, Amir Averbuch
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, distinctive-dictionary construction has gained importance due to his usefulness in data processing. Usually, one or more dictionaries are constructed from a training data and then they are used to classify signals that did not participate in the training process. A new dictionary construction algorithm is introduced. It is based on a low-rank matrix factorization being achieved by the application of the randomized LU decomposition to a training data. This method is fast, scalable, parallelizable, consumes low memory, outperforms SVD in these categories and works also extremely well on large sparse matrices. In contrast to existing methods, the randomized LU decomposition constructs an under-complete dictionary, which simplifies both the construction and the classification processes of newly arrived signals. The dictionary construction is generic and general that fits different applications. We demonstrate the capabilities of this algorithm for file type identification, which is a fundamental task in digital security arena, performed nowadays for example by sandboxing mechanism, deep packet inspection, firewalls and anti-virus systems. We propose a content-based method that detects file types that neither depend on file extension nor on metadata. Such approach is harder to deceive and we show that only a few file fragments from a whole file are needed for a successful classification. Based on the constructed dictionaries, we show that the proposed method can effectively identify execution code fragments in PDF files. $\textbf{Keywords.}$ Dictionary construction, classification, LU decomposition, randomized LU decomposition, content-based file detection, computer security.

##### Abstract (translated by Google)
近年来，由于其在数据处理上的实用性，特色字典的建设变得越来越重要。通常，一个或多个字典是从训练数据中构造出来的，然后用来分类没有参与训练过程的信号。介绍一种新的字典构造算法。它基于通过将随机LU分解应用于训练数据而实现的低秩矩阵分解。这种方法是快速的，可扩展的，可并行化的，消耗较少的内存，在这些类别中胜过SVD，而且在大型稀疏矩阵中也能很好地工作。与现有方法相比，随机LU分解构造了一个不完整的字典，简化了新到信号的构造和分类过程。字典的结构是通用的，适用于不同的应用。我们演示了这种算法对于文件类型识别的能力，这是数字安全领域的一项基本任务，例如沙盒机制，深度包检测，防火墙和防病毒系统。我们提出了一种基于内容的方法，可以检测既不依赖于文件扩展名也不依赖元数据的文件类型。这种方法很难欺骗，我们表明，只需要从整个文件中分离出几个文件碎片就可以实现成功的分类。基于构建的字典，我们证明了所提出的方法可以有效识别PDF文件中的执行代码片段。 $ \ textbf {Keywords。} $字典构造，分类，LU分解，随机LU分解，基于内容的文件检测，计算机安全。

##### URL
[https://arxiv.org/abs/1502.04824](https://arxiv.org/abs/1502.04824)

##### PDF
[https://arxiv.org/pdf/1502.04824](https://arxiv.org/pdf/1502.04824)

