---
layout: post
title: "Planning Beyond the Sensing Horizon Using a Learned Context"
date: 2019-08-24 17:19:50
categories: arXiv_AI
tags: arXiv_AI Sparse Deep_Learning Relation
author: Michael Everett, Justin Miller, Jonathan P. How
mathjax: true
---

* content
{:toc}

##### Abstract
Last-mile delivery systems commonly propose the use of autonomous robotic vehicles to increase scalability and efficiency. The economic inefficiency of collecting accurate prior maps for navigation motivates the use of planning algorithms that operate in unmapped environments. However, these algorithms typically waste time exploring regions that are unlikely to contain the delivery destination. Context is key information about structured environments that could guide exploration toward the unknown goal location, but the abstract idea is difficult to quantify for use in a planning algorithm. Some approaches specifically consider contextual relationships between objects, but would perform poorly in object-sparse environments like outdoors. Recent deep learning-based approaches consider context too generally, making training/transferability difficult. Therefore, this work proposes a novel formulation of utilizing context for planning as an image-to-image translation problem, which is shown to extract terrain context from semantic gridmaps, into a metric that an exploration-based planner can use. The proposed framework has the benefit of training on a static dataset instead of requiring a time-consuming simulator. Across 42 test houses with layouts from satellite images, the trained algorithm enables a robot to reach its goal 189\% faster than with a context-unaware planner, and within 63\% of the optimal path computed with a prior map. The proposed algorithm is also implemented on a vehicle with a forward-facing camera in a high-fidelity, Unreal simulation of neighborhood houses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09171](http://arxiv.org/abs/1908.09171)

##### PDF
[http://arxiv.org/pdf/1908.09171](http://arxiv.org/pdf/1908.09171)

