---
layout: post
title: "Determining Majority in Networks with Local Interactions and very Small Local Memory"
date: 2014-04-30 10:29:46
categories: arXiv_CV
tags: arXiv_CV
author: George B. Mertzios, Sotiris E. Nikoletseas, Christoforos L. Raptopoulos, Paul G. Spirakis
mathjax: true
---

* content
{:toc}

##### Abstract
We study here the problem of determining the majority type in an arbitrary connected network, each vertex of which has initially two possible types. The vertices may have a few additional possible states and can interact in pairs only if they share an edge. Any (population) protocol is required to stabilize in the initial majority. We first present and analyze a protocol with 4 states per vertex that always computes the initial majority value, under any fair scheduler. As we prove, this protocol is optimal, in the sense that there is no population protocol that always computes majority with fewer than 4 states per vertex. However this does not rule out the existence of a protocol with 3 states per vertex that is correct with high probability. To this end, we examine a very natural majority protocol with 3 states per vertex, introduced in [Angluin et al. 2008] where its performance has been analyzed for the clique graph. We study the performance of this protocol in arbitrary networks. We prove that, when the two initial states are put uniformly at random on the vertices, this protocol converges to the initial majority with probability higher than the probability of converging to the initial minority. In contrast, we present an infinite family of graphs, on which the protocol can fail whp, even when the difference between the initial majority and the initial minority is $n - \Theta(\ln{n})$. We also present another infinite family of graphs in which the protocol of Angluin et al. takes an expected exponential time to converge. These two negative results build upon a very positive result concerning the robustness of the protocol on the clique. Surprisingly, the resistance of the clique to failure causes the failure in general graphs. Our techniques use new domination and coupling arguments for suitably defined processes whose dynamics capture the antagonism between the states involved.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1404.7671](https://arxiv.org/abs/1404.7671)

##### PDF
[https://arxiv.org/pdf/1404.7671](https://arxiv.org/pdf/1404.7671)

