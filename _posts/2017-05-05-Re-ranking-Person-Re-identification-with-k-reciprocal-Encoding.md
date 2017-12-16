---
layout: post
title: "Re-ranking Person Re-identification with k-reciprocal Encoding"
date: 2017-05-05 02:46:47
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Zhun Zhong, Liang Zheng, Donglin Cao, Shaozi Li
mathjax: true
---

* content
{:toc}

##### Abstract
When considering person re-identification (re-ID) as a retrieval process, re-ranking is a critical step to improve its accuracy. Yet in the re-ID community, limited effort has been devoted to re-ranking, especially those fully automatic, unsupervised solutions. In this paper, we propose a k-reciprocal encoding method to re-rank the re-ID results. Our hypothesis is that if a gallery image is similar to the probe in the k-reciprocal nearest neighbors, it is more likely to be a true match. Specifically, given an image, a k-reciprocal feature is calculated by encoding its k-reciprocal nearest neighbors into a single vector, which is used for re-ranking under the Jaccard distance. The final distance is computed as the combination of the original distance and the Jaccard distance. Our re-ranking method does not require any human interaction or any labeled data, so it is applicable to large-scale datasets. Experiments on the large-scale Market-1501, CUHK03, MARS, and PRW datasets confirm the effectiveness of our method.

##### Abstract (translated by Google)
在考虑人员重新识别（re-ID）作为检索过程时，重新排序是提高其准确性的关键步骤。然而，在身份认证的社区，有限的努力已经用于重新排名，尤其是那些全自动的，无监督的解决方案。在本文中，我们提出了一个k-reciprocal编码方法来重新排列re-ID的结果。我们的假设是，如果一个画廊的图像类似于最近k邻近的探测器，那么它更可能是一个真正的匹配。具体而言，给定图像，通过将其k-互逆最近邻居编码成单个向量来计算k-互易特征，其用于在Jaccard距离下重新排序。最后的距离计算为原始距离和Jaccard距离的组合。我们的重新排序方法不需要任何人员交互或任何标记的数据，因此它适用于大型数据集。在大型Market-1501，CUHK03，MARS和PRW数据集上的实验证实了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1701.08398](https://arxiv.org/abs/1701.08398)

##### PDF
[https://arxiv.org/pdf/1701.08398](https://arxiv.org/pdf/1701.08398)

