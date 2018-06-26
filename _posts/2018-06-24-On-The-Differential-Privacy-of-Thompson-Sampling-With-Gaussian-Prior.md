---
layout: post
title: "On The Differential Privacy of Thompson Sampling With Gaussian Prior"
date: 2018-06-24 18:37:09
categories: arXiv_AI
tags: arXiv_AI
author: Aristide C. Y. Tossou, Christos Dimitrakakis
mathjax: true
---

* content
{:toc}

##### Abstract
We show that Thompson Sampling with Gaussian Prior as detailed by Algorithm 2 in (Agrawal &amp; Goyal, 2013) is already differentially private. Theorem 1 show that it enjoys a very competitive privacy loss of only $\mathcal{O}(\ln^2 T)$ after T rounds. Finally, Theorem 2 show that one can control the privacy loss to any desirable $\epsilon$ level by appropriately increasing the variance of the samples from the Gaussian posterior. And this increases the regret only by a term of $\mathcal{O}(\frac{\ln^2 T}{\epsilon})$. This compares favorably to the previous result for Thompson Sampling in the literature ((Mishra &amp; Thakurta, 2015)) which adds a term of $\mathcal{O}(\frac{K \ln^3 T}{\epsilon^2})$ to the regret in order to achieve the same privacy level. Furthermore, our result use the basic Thompson Sampling with few modifications whereas the result of (Mishra &amp; Thakurta, 2015) required sophisticated constructions.

##### Abstract (translated by Google)
我们证明，在（Agrawal＆amp; Goyal，2013）的算法2中详细描述的用高斯先验进行Thompson采样已经是有区别的私有的。定理1表明它在T轮之后享有非常有竞争力的隐私损失，只有$ \ mathcal {O}（\ ln ^ 2 T）$。最后，定理2表明，通过适当地增加高斯后验样本的方差，可以将隐私损失控制到任何理想的$ \ epsilon水平。而这只会增加后悔的一个期限$ \ mathcal {O}（\ frac {\ ln ^ 2 T} {\ epsilon}）$。这与文献（（Mishra＆amp; Thakurta，2015））中的Thompson Sampling的先前结果相比更加有利，其中添加了术语{\ mathcal {O}（\ frac {K \ ln ^ 3 T} {\ epsilon ^ 2 }）$为了达到相同的隐私级别而感到遗憾。此外，我们的结果使用了基本的汤普森抽样，而几乎没有修改，而（Mishra＆amp; Thakurta，2015）的结果需要复杂的结构。

##### URL
[http://arxiv.org/abs/1806.09192](http://arxiv.org/abs/1806.09192)

##### PDF
[http://arxiv.org/pdf/1806.09192](http://arxiv.org/pdf/1806.09192)

