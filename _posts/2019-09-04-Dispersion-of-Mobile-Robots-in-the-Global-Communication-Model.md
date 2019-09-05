---
layout: post
title: "Dispersion of Mobile Robots in the Global Communication Model"
date: 2019-09-04 17:33:09
categories: arXiv_RO
tags: arXiv_RO Relation
author: Ajay D. Kshemkalyani, Anisur Rahaman Molla, Gokarna Sharma
mathjax: true
---

* content
{:toc}

##### Abstract
The dispersion problem on graphs asks $k\leq n$ robots placed initially arbitrarily on the nodes of an $n$-node anonymous graph to reposition autonomously to reach a configuration in which each robot is on a distinct node of the graph. This problem is of significant interest due to its relationship to other fundamental robot coordination problems, such as exploration, scattering, load balancing etc. In this paper, we consider dispersion in the {\em global communication} model where a robot can communicate with any other robot in the graph (but the graph is unknown to robots). We provide three novel deterministic algorithms, two for arbitrary graphs and one for arbitrary trees, in a synchronous setting where all robots perform their actions in every time step. For arbitrary graphs, our first algorithm is based on a DFS traversal and guarantees $O(\min(m,k\Delta))$ steps runtime using $\Theta(\log (\max(k,\Delta)))$ bits at each robot, where $m$ is the number of edges and $\Delta$ is the maximum degree of the graph. The second algorithm for arbitrary graphs is based on a BFS traversal and guarantees $O( \max(D,k) \Delta (D+\Delta))$ steps runtime using $O(\max(D,\Delta \log k))$ bits at each robot, where $D$ is the diameter of the graph. The algorithm for arbitrary trees is also based on a BFS travesal and guarantees $O(D\max(D,k))$ steps runtime using $O(\max(D,\Delta \log k))$ bits at each robot. Our results are significant improvements compared to the existing results established in the {\em local communication} model where a robot can communication only with other robots present at the same node. Particularly, the DFS-based algorithm is optimal for both memory and time in constant-degree arbitrary graphs. The BFS-based algorithm for arbitrary trees is optimal with respect to runtime when $k\leq O(D)$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01957](http://arxiv.org/abs/1909.01957)

##### PDF
[http://arxiv.org/pdf/1909.01957](http://arxiv.org/pdf/1909.01957)

