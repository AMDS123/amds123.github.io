---
layout: post
title: "Parsimonious Labeling"
date: 2015-07-05 11:59:43
categories: arXiv_CV
tags: arXiv_CV
author: Puneet K. Dokania, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new family of discrete energy minimization problems, which we call parsimonious labeling. Specifically, our energy functional consists of unary potentials and high-order clique potentials. While the unary potentials are arbitrary, the clique potentials are proportional to the {\em diversity} of set of the unique labels assigned to the clique. Intuitively, our energy functional encourages the labeling to be parsimonious, that is, use as few labels as possible. This in turn allows us to capture useful cues for important computer vision applications such as stereo correspondence and image denoising. Furthermore, we propose an efficient graph-cuts based algorithm for the parsimonious labeling problem that provides strong theoretical guarantees on the quality of the solution. Our algorithm consists of three steps. First, we approximate a given diversity using a mixture of a novel hierarchical $P^n$ Potts model. Second, we use a divide-and-conquer approach for each mixture component, where each subproblem is solved using an effficient $\alpha$-expansion algorithm. This provides us with a small number of putative labelings, one for each mixture component. Third, we choose the best putative labeling in terms of the energy value. Using both sythetic and standard real datasets, we show that our algorithm significantly outperforms other graph-cuts based approaches.

##### Abstract (translated by Google)
我们提出了一个新的离散能量最小化问题族，我们称之为吝啬的标记。具体而言，我们的能量函数由一元势能和高阶团的潜力组成。虽然一元的潜力是任意的，但是集体潜能与分配给集团的独特标签集合的集合成正比。直观地说，我们的能量功能鼓励标签是节省的，即尽可能少地使用标签。这反过来使我们能够捕获重要的计算机视觉应用的有用线索，例如立体对应和图像去噪。此外，我们提出了一种高效的基于图割的算法来解决标签问题，为解决方案的质量提供了强有力的理论保证。我们的算法由三个步骤组成。首先，我们使用一个新的分层$ P ^ n $ Potts模型的混合来近似给定的多样性。其次，我们对每个混合分量使用分而治之的方法，其中每个子问题使用有效的$ \ alpha $扩展算法来解决。这为我们提供了一小部分假定的标签，每个混合部分都有一个标签。第三，我们从能源价值的角度出发，选择最好的假定标签。使用合成和标准真实数据集，我们显示，我们的算法显着优于其他基于图形切割的方法。

##### URL
[https://arxiv.org/abs/1507.01208](https://arxiv.org/abs/1507.01208)

##### PDF
[https://arxiv.org/pdf/1507.01208](https://arxiv.org/pdf/1507.01208)

