---
layout: post
title: "Timeline-based planning: Expressiveness and Complexity"
date: 2019-02-16 16:45:03
categories: arXiv_AI
tags: arXiv_AI
author: Nicola Gigante
mathjax: true
---

* content
{:toc}

##### Abstract
Timeline-based planning is an approach originally developed in the context of space mission planning and scheduling, where problem domains are modelled as systems made of a number of independent but interacting components, whose behaviour over time, the timelines, is governed by a set of temporal constraints. This approach is different from the action-based perspective of common PDDL-like planning languages. Timeline-based systems have been successfully deployed in a number of space missions and other domains. However, despite this practical success, a thorough theoretical understanding of the paradigm was missing. 
 This thesis fills this gap, providing the first detailed account of formal and computational properties of the timeline-based approach to planning. In particular, we show that a particularly restricted variant of the formalism is already expressive enough to compactly capture action-based temporal planning problems. Then, finding a solution plan for a timeline-based planning problem is proved to be EXPSPACE-complete. 
 Then, we study the problem of timeline-based planning with uncertainty, that include external components whose behaviour is not under the control of the planned system. We identify a few issues in the state-of-the-art approach based on flexible plans, proposing timeline-based games, a more general game-theoretic formulation of the problem, that addresses those issues. We show that winning strategies for such games can be found in doubly-exponential time. 
 Then, we study the expressiveness of the formalism from a logic point of view, showing that (most of) timeline-based planning problems can be captured by Bounded TPTL with Past, a fragment of TPTL+P that, unlike the latter, keeps an EXPSPACE satisfiability problem. The logic is introduced and its satisfiabilty problem is solved by extending a recent one-pass tree-shaped tableau method for LTL.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06123](http://arxiv.org/abs/1902.06123)

##### PDF
[http://arxiv.org/pdf/1902.06123](http://arxiv.org/pdf/1902.06123)

