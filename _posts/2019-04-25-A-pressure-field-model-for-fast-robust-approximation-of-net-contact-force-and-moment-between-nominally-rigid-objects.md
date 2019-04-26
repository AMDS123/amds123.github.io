---
layout: post
title: "A pressure field model for fast, robust approximation of net contact force and moment between nominally rigid objects"
date: 2019-04-25 16:14:52
categories: arXiv_RO
tags: arXiv_RO Face
author: Ryan Elandt, Evan Drumwright, Michael Sherman, Andy Ruina
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an approximate model for predicting the net contact wrench between nominally rigid objects for use in simulation, control, and state estimation. The model combines and generalizes two ideas: a bed of springs (an "elastic foundation") and hydrostatic pressure. In this model, continuous pressure fields are computed offline for the interior of each nominally rigid object. Unlike hydrostatics or elastic foundations, the pressure fields need not satisfy mechanical equilibrium conditions. When two objects nominally overlap, a contact surface is defined where the two pressure fields are equal. This static pressure is supplemented with a dissipative rate-dependent pressure and friction to determine tractions on the contact surface. The contact wrench between pairs of objects is an integral of traction contributions over this surface. The model evaluates much faster than elasticity-theory models, while showing the essential trends of force, moment, and stiffness increase with contact load. It yields continuous wrenches even for non-convex objects and coarse meshes. The method shows promise as sufficiently fast, accurate, and robust for design-in-simulation of robot controllers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11433](http://arxiv.org/abs/1904.11433)

##### PDF
[http://arxiv.org/pdf/1904.11433](http://arxiv.org/pdf/1904.11433)

