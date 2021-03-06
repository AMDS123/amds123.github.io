---
layout: post
title: "Teach-Repeat-Replan: A Complete and Robust System for Aggressive Flight in Complex Environments"
date: 2019-07-01 02:59:08
categories: arXiv_RO
tags: arXiv_RO Drone
author: Fei Gao, Luqi Wang, Boyu Zhou, Luxin Han, Jie Pan, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a complete and robust motion planning system for the aggressive flight of autonomous quadrotors. The proposed method is built upon on a classical teach-and-repeat framework, which is widely adopted in infrastructure inspection, aerial transportation, and search-and-rescue. For these applications, human's intention is essential to decide the topological structure of the flight trajectory of the drone. However, poor teaching trajectories and changing environments prevent a simple teach-and-repeat system from being applied flexibly and robustly. In this paper, instead of commanding the drone to precisely follow a teaching trajectory, we propose a method to automatically convert a human-piloted trajectory, which can be arbitrarily jerky, to a topologically equivalent one. The generated trajectory is guaranteed to be smooth, safe, and kinodynamically feasible, with a human preferable aggressiveness. Also, to avoid unmapped or dynamic obstacles during flights, a sliding-windowed local perception and re-planning method are introduced to our system, to generate safe local trajectories onboard. We name our system as teach-repeat-replan. It can capture users' intention of a flight mission, convert an arbitrarily jerky teaching path to a smooth repeating trajectory, and generate safe local re-plans to avoid unmapped or moving obstacles. The proposed planning system is integrated into a complete autonomous quadrotor with global and local perception and localization sub-modules. Our system is validated by performing aggressive flights in challenging indoor/outdoor environments. We release all components in our quadrotor system as open-source ros-packages.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00520](http://arxiv.org/abs/1907.00520)

##### PDF
[http://arxiv.org/pdf/1907.00520](http://arxiv.org/pdf/1907.00520)

