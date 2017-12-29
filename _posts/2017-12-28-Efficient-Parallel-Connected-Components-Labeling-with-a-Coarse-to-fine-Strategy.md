---
layout: post
title: "Efficient Parallel Connected Components Labeling with a Coarse-to-fine Strategy"
date: 2017-12-28 08:50:22
categories: arXiv_CV
tags: arXiv_CV
author: Jun Chen, Keisuke Nonaka, Ryosuke Watanabe, Hiroshi Sankoh, Houari Sabirin, Sei Naito
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new parallel approach to solve connected components on a 2D binary image implemented with CUDA. We employ the following strategies to accelerate neighborhood exploration after dividing an input image into independent blocks. In the local labeling stage, a coarse-labeling algorithm, including row-column connection and label-equivalence list unification, is applied first to sort out the mess of initialized local label map; a refinement algorithm is introduced then to combine separated sub-regions from a single component. In the block merge stage, we scan the pixels located on the boundary of each block instead of solving the connectivity of all the pixels. With the proposed method, the length of label-equivalence lists is compressed, and the number of memory accesses is reduced. Thus, the efficiency of connected components labeling is improved.Experimental results show that our method outperforms the other approaches between $29\%$ and $80\%$ on average.

##### Abstract (translated by Google)
本文提出了一种新的并行方法来解决用CUDA实现的二维二值图像上的连通分量。在将输入图像划分为独立的块之后，我们采用以下策略来加速邻域探索。在本地标注阶段，首先应用包括行列连接和标签等价列表统一在内的粗标记算法，对初始化的局部标注图进行排序;引入细化算法，然后将单个分量的分离的子区域组合起来。在块合并阶段，我们扫描位于每个块的边界上的像素，而不是解决所有像素的连通性。使用所提出的方法，压缩标签对等列表的长度，并减少存储器访问次数。从而提高了连接元件标签的效率。实验结果表明，我们的方法平均优于其他方法，在29美元和80美元之间。

##### URL
[http://arxiv.org/abs/1712.09789](http://arxiv.org/abs/1712.09789)

##### PDF
[http://arxiv.org/pdf/1712.09789](http://arxiv.org/pdf/1712.09789)

