---
layout: post
title: "Coordinate Descent with Bandit Sampling"
date: 2018-12-04 15:25:14
categories: arXiv_AI
tags: arXiv_AI
author: Farnood Salehi, Patrick Thiran, L. Elisa Celis
mathjax: true
---

* content
{:toc}

##### Abstract
Coordinate descent methods usually minimize a cost function by updating a random decision variable (corresponding to one coordinate) at a time. Ideally, we would update the decision variable that yields the largest decrease in the cost function. However, finding this coordinate would require checking all of them, which would effectively negate the improvement in computational tractability that coordinate descent is intended to afford. To address this, we propose a new adaptive method for selecting a coordinate. First, we find a lower bound on the amount the cost function decreases when a coordinate is updated. We then use a multi-armed bandit algorithm to learn which coordinates result in the largest lower bound by interleaving this learning with conventional coordinate descent updates except that the coordinate is selected proportionately to the expected decrease. We show that our approach improves the convergence of coordinate descent methods both theoretically and experimentally.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.03010](http://arxiv.org/abs/1712.03010)

##### PDF
[http://arxiv.org/pdf/1712.03010](http://arxiv.org/pdf/1712.03010)

