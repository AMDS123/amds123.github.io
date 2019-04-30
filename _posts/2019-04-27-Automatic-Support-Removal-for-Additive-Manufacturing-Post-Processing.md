---
layout: post
title: "Automatic Support Removal for Additive Manufacturing Post Processing"
date: 2019-04-27 06:45:42
categories: arXiv_RO
tags: arXiv_RO
author: Saigopal Nelaturi, Morad Behandish, Amir M. Mirzendehdel, Johan de Kleer
mathjax: true
---

* content
{:toc}

##### Abstract
An additive manufacturing (AM) process often produces a {\it near-net} shape that closely conforms to the intended design to be manufactured. It sometimes contains additional support structure (also called scaffolding), which has to be removed in post-processing. We describe an approach to automatically generate process plans for support removal using a multi-axis machining instrument. The goal is to fracture the contact regions between each support component and the part, and to do it in the most cost-effective order while avoiding collisions with evolving near-net shape, including the remaining support components. A recursive algorithm identifies a maximal collection of support components whose connection regions to the part are accessible as well as the orientations at which they can be removed at a given round. For every such region, the accessible orientations appear as a 'fiber' in the collision-free space of the evolving near-net shape and the tool assembly. To order the removal of accessible supports, the algorithm constructs a search graph whose edges are weighted by the Riemannian distance between the fibers. The least expensive process plan is obtained by solving a traveling salesman problem (TSP) over the search graph. The sequence of configurations obtained by solving TSP is used as the input to a motion planner that finds collision free paths to visit all accessible features. The resulting part without the support structure can then be finished using traditional machining to produce the intended design. The effectiveness of the method is demonstrated through benchmark examples in 3D.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12117](http://arxiv.org/abs/1904.12117)

##### PDF
[http://arxiv.org/pdf/1904.12117](http://arxiv.org/pdf/1904.12117)

