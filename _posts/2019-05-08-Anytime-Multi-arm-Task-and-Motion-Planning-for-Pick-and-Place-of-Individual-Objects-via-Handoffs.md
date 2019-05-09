---
layout: post
title: "Anytime Multi-arm Task and Motion Planning for Pick-and-Place of Individual Objects via Handoffs"
date: 2019-05-08 16:07:56
categories: arXiv_RO
tags: arXiv_RO
author: Rahul Shome, Kostas E. Bekris
mathjax: true
---

* content
{:toc}

##### Abstract
Automation applications are pushing the deployment of many high DoF manipulators in warehouse and manufacturing environments. This has motivated many efforts on optimizing manipulation tasks involving a single arm. Coordinating multiple arms for manipulation, however, introduces additional computational challenges arising from the increased DoFs, as well as the combinatorial increase in the available operations that many manipulators can perform, including handoffs between arms. The focus here is on the case of pick-and-place tasks, which require a sequence of handoffs to be executed, so as to achieve computational efficiency, asymptotic optimality and practical anytime performance. The paper leverages recent advances in multi-robot motion planning for high DoF systems to propose a novel multi-modal extension of the dRRT* algorithm. The key insight is that, instead of naively solving a sequence of motion planning problems, it is computationally advantageous to directly explore the composite space of the integrated multi-arm task and motion planning problem, given input sets of possible pick and handoff configurations. Asymptotic optimality guarantees are possible by sampling additional picks and handoffs over time. The evaluation shows that the approach finds initial solutions fast and improves their quality over time. It also succeeds in finding solutions to harder problem instances relative to alternatives and can scale effectively as the number of robots increases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03179](http://arxiv.org/abs/1905.03179)

##### PDF
[http://arxiv.org/pdf/1905.03179](http://arxiv.org/pdf/1905.03179)

