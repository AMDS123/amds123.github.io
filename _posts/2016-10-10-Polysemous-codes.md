---
layout: post
title: "Polysemous codes"
date: 2016-10-10 23:00:00
categories: arXiv_CV
tags: arXiv_CV GAN
author: Matthijs Douze, Hervé Jégou, Florent Perronnin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the problem of approximate nearest neighbor search in the compressed domain. We introduce polysemous codes, which offer both the distance estimation quality of product quantization and the efficient comparison of binary codes with Hamming distance. Their design is inspired by algorithms introduced in the 90's to construct channel-optimized vector quantizers. At search time, this dual interpretation accelerates the search. Most of the indexed vectors are filtered out with Hamming distance, letting only a fraction of the vectors to be ranked with an asymmetric distance estimator. The method is complementary with a coarse partitioning of the feature space such as the inverted multi-index. This is shown by our experiments performed on several public benchmarks such as the BIGANN dataset comprising one billion vectors, for which we report state-of-the-art results for query times below 0.3\,millisecond per core. Last but not least, our approach allows the approximate computation of the k-NN graph associated with the Yahoo Flickr Creative Commons 100M, described by CNN image descriptors, in less than 8 hours on a single machine.

##### Abstract (translated by Google)
本文考虑了压缩域中近似最近邻搜索的问题。我们引入多义码，既提供产品量化的距离估计质量，又提供二进制码与汉明距离的有效比较。他们的设计灵感来自90年代推出的算法，以构建通道优化的矢量量化器。在搜索的时候，这种双重解释加速了搜索。大多数索引向量用海明距离过滤出来，只有一小部分向量用一个非对称距离估计器排序。该方法与特征空间的粗分割（如反向多指标）相辅相成。这通过我们在几个公共基准测试（例如包含十亿个载体的BIGANN数据集）上进行的实验得到了证明，为此，我们报告了针对低于每核0.3毫秒毫秒的查询时间的最新结果。最后但并非最不重要的是，我们的方法允许在单台机器上在不到8小时的时间内近似计算与CNN图像描述符所描述的Yahoo Flickr Creative Commons 100M相关联的k-NN图。

##### URL
[https://arxiv.org/abs/1609.01882](https://arxiv.org/abs/1609.01882)

##### PDF
[https://arxiv.org/pdf/1609.01882](https://arxiv.org/pdf/1609.01882)

