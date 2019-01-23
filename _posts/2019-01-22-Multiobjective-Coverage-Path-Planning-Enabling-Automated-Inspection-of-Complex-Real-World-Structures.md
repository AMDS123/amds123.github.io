---
layout: post
title: "Multiobjective Coverage Path Planning: Enabling Automated Inspection of Complex, Real-World Structures"
date: 2019-01-22 11:42:41
categories: arXiv_AI
tags: arXiv_AI
author: Kai Olav Ellefsen, Herman A. Lepikson, Jan C. Albiez
mathjax: true
---

* content
{:toc}

##### Abstract
An important open problem in robotic planning is the autonomous generation of 3D inspection paths -- that is, planning the best path to move a robot along in order to inspect a target structure. We recently suggested a new method for planning paths allowing the inspection of complex 3D structures, given a triangular mesh model of the structure. The method differs from previous approaches in its emphasis on generating and considering also plans that result in imperfect coverage of the inspection target. In many practical tasks, one would accept imperfections in coverage if this results in a substantially more energy efficient inspection path. The key idea is using a multiobjective evolutionary algorithm to optimize the energy usage and coverage of inspection plans simultaneously - and the result is a set of plans exploring the different ways to balance the two objectives. We here test our method on a set of inspection targets with large variation in size and complexity, and compare its performance with two state-of-the-art methods for complete coverage path planning. The results strengthen our confidence in the ability of our method to generate good inspection plans for different types of targets. The method's advantage is most clearly seen for real-world inspection targets, since traditional complete coverage methods have no good way of generating plans for structures with hidden parts. Multiobjective evolution, by optimizing energy usage and coverage together ensures a good balance between the two - both when 100% coverage is feasible, and when large parts of the object are hidden.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07272](http://arxiv.org/abs/1901.07272)

##### PDF
[http://arxiv.org/pdf/1901.07272](http://arxiv.org/pdf/1901.07272)

