---
layout: post
title: "Fast Approximate Clearance Evaluation for Rovers with Articulated Suspension Systems"
date: 2019-07-01 02:53:36
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Kyohei Otsu, Guillaume Matheron, Sourish Ghosh, Olivier Toupet, Masahiro Ono
mathjax: true
---

* content
{:toc}

##### Abstract
We present a light-weight body-terrain clearance evaluation algorithm for the automated path planning of NASA's Mars 2020 rover. Extraterrestrial path planning is challenging due to the combination of terrain roughness and severe limitation in computational resources. Path planning on cluttered and/or uneven terrains requires repeated safety checks on all the candidate paths at a small interval. Predicting the future rover state requires simulating the vehicle settling on the terrain, which involves an inverse-kinematics problem with iterative nonlinear optimization under geometric constraints. However, such expensive computation is intractable for slow spacecraft computers, such as RAD750, which is used by the Curiosity Mars rover and upcoming Mars 2020 rover. We propose the Approximate Clearance Evaluation (ACE) algorithm, which obtains conservative bounds on vehicle clearance, attitude, and suspension angles without iterative computation. It obtains those bounds by estimating the lowest and highest heights that each wheel may reach given the underlying terrain, and calculating the worst-case vehicle configuration associated with those extreme wheel heights. The bounds are guaranteed to be conservative, hence ensuring vehicle safety during autonomous navigation. ACE is planned to be used as part of the new onboard path planner of the Mars 2020 rover. This paper describes the algorithm in detail and validates our claim of conservatism and fast computation through experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.00031](http://arxiv.org/abs/1808.00031)

##### PDF
[http://arxiv.org/pdf/1808.00031](http://arxiv.org/pdf/1808.00031)

