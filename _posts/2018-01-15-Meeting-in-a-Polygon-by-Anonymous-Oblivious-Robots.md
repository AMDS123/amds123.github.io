---
layout: post
title: "Meeting in a Polygon by Anonymous Oblivious Robots"
date: 2018-01-15 18:03:35
categories: arXiv_RO
tags: arXiv_RO
author: Giuseppe A. Di Luna, Paola Flocchini, Nicola Santoro, Giovanni Viglietta, Masafumi Yamashita
mathjax: true
---

* content
{:toc}

##### Abstract
The Meeting problem for $k\geq 2$ searchers in a polygon $P$ (possibly with holes) consists in making the searchers move within $P$, according to a distributed algorithm, in such a way that at least two of them eventually come to see each other, regardless of their initial positions. The polygon is initially unknown to the searchers, and its edges obstruct both movement and vision. Depending on the shape of $P$, we minimize the number of searchers $k$ for which the Meeting problem is solvable. Specifically, if $P$ has a rotational symmetry of order $\sigma$ (where $\sigma=1$ corresponds to no rotational symmetry), we prove that $k=\sigma+1$ searchers are sufficient, and the bound is tight. Furthermore, we give an improved algorithm that optimally solves the Meeting problem with $k=2$ searchers in all polygons whose barycenter is not in a hole (which includes the polygons with no holes). Our algorithms can be implemented in a variety of standard models of mobile robots operating in Look-Compute-Move cycles. For instance, if the searchers have memory but are anonymous, asynchronous, and have no agreement on a coordinate system or a notion of clockwise direction, then our algorithms work even if the initial memory contents of the searchers are arbitrary and possibly misleading. Moreover, oblivious searchers can execute our algorithms as well, encoding information by carefully positioning themselves within the polygon. This code is computable with basic arithmetic operations, and each searcher can geometrically construct its own destination point at each cycle using only a compass. We stress that such memoryless searchers may be located anywhere in the polygon when the execution begins, and hence the information they initially encode is arbitrary. Our algorithms use a self-stabilizing map construction subroutine which is of independent interest.

##### Abstract (translated by Google)
在$ P $（可能带有空洞）中的$ k \ geq 2 $ searchers的会议问题在于使搜索者在$ P $内移动，根据分布式算法，以至少其中两个最终来看看对方，不管他们的初始位置。多边形最初对于搜索者是未知的，其边缘阻碍了运动和视觉。根据$ P $的形状，我们最小化会议问题可以解决的搜索者$ k $的数量。具体而言，如果$ P $具有$ \ sigma $（其中$ \ sigma = 1 $对应于没有旋转对称）的旋转对称性，我们证明$ k = \ sigma + 1 $ searchers足够了，紧。此外，我们给出了一个改进的算法，在重心不在洞的所有多边形（包括没有洞的多边形）中用$ k = 2 $ searchers优化地解决了Meeting问题。我们的算法可以在运行Look-Compute-Move周期的各种移动机器人的标准模型中实现。例如，如果搜索者具有记忆但是匿名的，异步的，并且在坐标系或顺时针方向的概念上没有一致性，那么即使搜索者的初始记忆内容是任意的并且可能具有误导性，我们的算法仍然工作。而且，不经意的搜索者也可以执行我们的算法，通过在多边形内仔细定位自己来编码信息。这个代码可以用基本的算术运算进行计算，每个搜索者只需要一个指南针就可以在每个周期中几何构建自己的目标点。我们强调这种无记忆的搜索者在执行开始时可能位于多边形的任何地方，因此他们最初编码的信息是任意的。我们的算法使用独立感兴趣的自稳定图构造子程序。

##### URL
[http://arxiv.org/abs/1705.00324](http://arxiv.org/abs/1705.00324)

##### PDF
[http://arxiv.org/pdf/1705.00324](http://arxiv.org/pdf/1705.00324)

