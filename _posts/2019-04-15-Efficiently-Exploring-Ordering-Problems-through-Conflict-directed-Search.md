---
layout: post
title: "Efficiently Exploring Ordering Problems through Conflict-directed Search"
date: 2019-04-15 23:47:21
categories: arXiv_AI
tags: arXiv_AI Relation
author: Jingkai Chen, Cheng Fang, David Wang, Andrew Wang, Brian Williams
mathjax: true
---

* content
{:toc}

##### Abstract
In planning and scheduling, solving problems with both state and temporal constraints is hard since these constraints may be highly coupled. Judicious orderings of events enable solvers to efficiently make decisions over sequences of actions to satisfy complex hybrid specifications. The ordering problem is thus fundamental to planning. Promising recent works have explored the ordering problem as search, incorporating a special tree structure for efficiency. However, such approaches only reason over partial order specifications. Having observed that an ordering is inconsistent with respect to underlying constraints, prior works do not exploit the tree structure to efficiently generate orderings that resolve the inconsistency. In this paper, we present Conflict-directed Incremental Total Ordering (CDITO), a conflict-directed search method to incrementally and systematically generate event total orders given ordering relations and conflicts returned by sub-solvers. Due to its ability to reason over conflicts, CDITO is much more efficient than Incremental Total Ordering. We demonstrate this by benchmarking on temporal network configuration problems that involve routing network flows and allocating bandwidth resources over time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07366](http://arxiv.org/abs/1904.07366)

##### PDF
[http://arxiv.org/pdf/1904.07366](http://arxiv.org/pdf/1904.07366)

