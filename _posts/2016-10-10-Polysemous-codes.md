---
layout: post
title: "Polysemous codes"
date: 2016-10-10 23:00:00
categories: arXiv_CV
tags: arXiv_CV GAN
author: Matthijs Douze, Herv&#xe9; J&#xe9;gou, Florent Perronnin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the problem of approximate nearest neighbor search in the compressed domain. We introduce polysemous codes, which offer both the distance estimation quality of product quantization and the efficient comparison of binary codes with Hamming distance. Their design is inspired by algorithms introduced in the 90's to construct channel-optimized vector quantizers. At search time, this dual interpretation accelerates the search. Most of the indexed vectors are filtered out with Hamming distance, letting only a fraction of the vectors to be ranked with an asymmetric distance estimator. 
 The method is complementary with a coarse partitioning of the feature space such as the inverted multi-index. This is shown by our experiments performed on several public benchmarks such as the BIGANN dataset comprising one billion vectors, for which we report state-of-the-art results for query times below 0.3\,millisecond per core. Last but not least, our approach allows the approximate computation of the k-NN graph associated with the Yahoo Flickr Creative Commons 100M, described by CNN image descriptors, in less than 8 hours on a single machine.

##### Abstract (translated by Google)
本文考虑了压缩域中近似最近邻搜索的问题。我们引入多义码，既提供产品量化的距离估计质量，又提供二进制码与汉明距离的有效比较。他们的设计灵感来自90年代推出的构建通道优化矢量量化器的算法。在搜索时，这种双重解释加速了搜索。大多数索引向量用Hamming距离过滤出来，让一小部分向量用非对称距离估计器排序。
 该方法与特征空间的粗分割（诸如倒排多索引）是互补的。我们在几个公共基准测试中进行的实验表明了这一点，例如包含10亿个载体的BIGANN数据集，为此我们报告了针对低于每核0.3毫秒毫秒的查询时间的最新结果。最后但并非最不重要的是，我们的方法允许在单台机器上在不到8小时内近似计算与CNN图像描述符描述的Yahoo Flickr Creative Commons 100M相关的k-NN图。

##### URL
[http://arxiv.org/abs/1609.01882](http://arxiv.org/abs/1609.01882)

##### PDF
[http://arxiv.org/pdf/1609.01882](http://arxiv.org/pdf/1609.01882)

