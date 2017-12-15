---
layout: post
title: "Globally Variance-Constrained Sparse Representation for Image Set Compression"
date: 2016-08-17 09:34:51
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sparse Optimization
author: Xiang Zhang, Jiarui Sun, Siwei Ma, Zhouchen Lin, Jian Zhang, Shiqi Wang, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse representation presents an efficient approach to approximately recover a signal by the linear composition of a few bases from a learnt dictionary, based on which various successful applications have been observed. However, in the scenario of data compression, its efficiency and popularity are hindered due to the extra overhead for encoding the sparse coefficients. Therefore, how to establish an accurate rate model in sparse coding and dictionary learning becomes meaningful, which has been not fully exploited in the context of sparse representation. According to the Shannon entropy inequality, the variance of data source bounds its entropy, which can reflect the actual coding bits. Hence, in this work a Globally Variance-Constrained Sparse Representation (GVCSR) model is proposed, where a variance-constrained rate model is introduced in the optimization process. Specifically, we employ the Alternating Direction Method of Multipliers (ADMM) to solve the non-convex optimization problem for sparse coding and dictionary learning, both of which have shown state-of-the-art performance in image representation. Furthermore, we investigate the potential of GVCSR in practical image set compression, where a common dictionary is trained by several key images to represent the whole image set. Experimental results have demonstrated significant performance improvements against the most popular image codecs including JPEG and JPEG2000.

##### Abstract (translated by Google)
稀疏表示法提供了一种有效的方法来从学习的字典中通过几个碱基的线性组合来近似地恢复信号，基于其观察到各种成功的应用。然而，在数据压缩的情况下，由于编码稀疏系数的额外开销，其效率和普及性受到阻碍。因此，如何在稀疏编码和字典学习中建立准确率模型变得有意义，在稀疏表示的背景下还没有得到充分的发挥。根据香农熵不等式，数据源的方差限定了它的熵，它可以反映实际的编码比特。因此，本文提出了一个全局方差约束稀疏表示（GVCSR）模型，其中在优化过程中引入了方差约束率模型。具体来说，我们采用交替方向乘法器（ADMM）来解决稀疏编码和字典学习的非凸优化问题，两者在图像表示方面都表现出了最先进的性能。此外，我们研究了GVCSR在实际图像集压缩中的潜力，其中一个普通的字典是由几个关键图像训练来表示整个图像集。实验结果已经证明了对包括JPEG和JPEG2000在内的最流行的图像编解码器有显着的性能改进。

##### URL
[https://arxiv.org/abs/1608.04902](https://arxiv.org/abs/1608.04902)

##### PDF
[https://arxiv.org/pdf/1608.04902](https://arxiv.org/pdf/1608.04902)

