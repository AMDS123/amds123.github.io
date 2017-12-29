---
layout: post
title: "The information bottleneck and geometric clustering"
date: 2017-12-27 19:04:49
categories: arXiv_AI
tags: arXiv_AI
author: D J Strouse, David J Schwab
mathjax: true
---

* content
{:toc}

##### Abstract
The information bottleneck (IB) approach to clustering takes a joint distribution $P\!\left(X,Y\right)$ and maps the data $X$ to cluster labels $T$ which retain maximal information about $Y$ (Tishby et al., 1999). This objective results in an algorithm that clusters data points based upon the similarity of their conditional distributions $P\!\left(Y\mid X\right)$. This is in contrast to classic "geometric clustering" algorithms such as $k$-means and gaussian mixture models (GMMs) which take a set of observed data points $\left\{ \mathbf{x}_{i}\right\}_{i=1:N}$ and cluster them based upon their geometric (typically Euclidean) distance from one another. Here, we show how to use the deterministic information bottleneck (DIB) (Strouse and Schwab, 2017), a variant of IB, to perform geometric clustering, by choosing cluster labels that preserve information about data point location on a smoothed dataset. We also introduce a novel intuitive method to choose the number of clusters, via kinks in the information curve. We apply this approach to a variety of simple clustering problems, showing that DIB with our model selection procedure recovers the generative cluster labels. We also show that, for one simple case, DIB interpolates between the cluster boundaries of GMMs and $k$-means in the large data limit. Thus, our IB approach to clustering also provides an information-theoretic perspective on these classic algorithms.

##### Abstract (translated by Google)
聚类的信息瓶颈（IB）方法采用联合分布（X，Y \ right）$并将数据$ X $映射到集群标签$ T $，其保留关于$ Y $的最大信息（Tishby等人，1999）。这个目标的结果是一个算法，根据它们的条件分布的相似性对数据点进行聚类，得到左（Y \ mid X \ right）$。这与经典的“几何聚类”算法（如$ k $ -means和高斯混合模型（GMMs））相反，后者采用一组观察数据点$ \ left \ {\ mathbf {x} _ {i} \ right \ } _ {i = 1：N} $，并根据它们之间的几何（通常是欧几里得）距离对它们进行聚类。在这里，我们展示了如何使用确定性信息瓶颈（DIB）（Strouse和Schwab，2017）（一种IB的变体）来执行几何聚类，通过选择聚类标签来保存关于平滑数据集上数据点位置的信息。我们还介绍了一种新颖直观的方法，通过信息曲线中的扭结来选择聚类数量。我们将这种方法应用于各种简单的聚类问题，表明DIB与我们的模型选择程序恢复了生成聚类标签。我们还表明，对于一个简单的情况，DIB在大数据限制中在GMM的群集边界和$ k $ -means之间进行插值。因此，我们IB的聚类方法也为这些经典算法提供了一个信息论的观点。

##### URL
[http://arxiv.org/abs/1712.09657](http://arxiv.org/abs/1712.09657)

##### PDF
[http://arxiv.org/pdf/1712.09657](http://arxiv.org/pdf/1712.09657)

