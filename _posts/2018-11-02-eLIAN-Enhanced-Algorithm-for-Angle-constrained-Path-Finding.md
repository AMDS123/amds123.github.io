---
layout: post
title: "eLIAN: Enhanced Algorithm for Angle-constrained Path Finding"
date: 2018-11-02 09:54:35
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Anton Andreychuk (1), Natalia Soboleva (2), Konstantin Yakovlev (2, 3, 4) ((1) Peoples&#x27; Friendship University of Russia, (2) National Research University Higher School of Economics, (3) Federal Research Center &#x27;&#x27;Computer Science and Control&#x27;&#x27; of Russian Academy of Sciences, (4) Moscow Institute of Physics and Technology )
mathjax: true
---

* content
{:toc}

##### Abstract
Problem of finding 2D paths of special shape, e.g. paths comprised of line segments having the property that the angle between any two consecutive segments does not exceed the predefined threshold, is considered in the paper. This problem is harder to solve than the one when shortest paths of any shape are sought, since the planer's search space is substantially bigger as multiple search nodes corresponding to the same location need to be considered. One way to reduce the search effort is to fix the length of the path's segment and to prune the nodes that violate the imposed constraint. This leads to incompleteness and to the sensitivity of the 's performance to chosen parameter value. In this work we introduce a novel technique that reduces this sensitivity by automatically adjusting the length of the path's segment on-the-fly, e.g. during the search. Embedding this technique into the known grid-based angle-constrained path finding algorithm - LIAN, leads to notable increase of the planner's effectiveness, e.g. success rate, while keeping efficiency, e.g. runtime, overhead at reasonable level. Experimental evaluation shows that LIAN with the suggested enhancements, dubbed eLIAN, solves up to 20\% of tasks more compared to the predecessor. Meanwhile, the solution quality of eLIAN is nearly the same as the one of LIAN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00797](http://arxiv.org/abs/1811.00797)

##### PDF
[http://arxiv.org/pdf/1811.00797](http://arxiv.org/pdf/1811.00797)

