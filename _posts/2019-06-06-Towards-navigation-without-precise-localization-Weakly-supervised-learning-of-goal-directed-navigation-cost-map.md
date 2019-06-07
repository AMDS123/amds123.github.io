---
layout: post
title: "Towards navigation without precise localization: Weakly supervised learning of goal-directed navigation cost map"
date: 2019-06-06 08:16:31
categories: arXiv_RO
tags: arXiv_RO Adversarial Weakly_Supervised
author: Huifang Ma, Yue Wang, Li Tang, Sarath Kodagoda, Rong Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous navigation based on precise localization has been widely developed in both academic research and practical applications. The high demand for localization accuracy has been essential for safe robot planing and navigation while it makes the current geometric solutions less robust to environmental changes. Recent research on end-to-end methods handle raw sensory data with forms of navigation instructions and directly output the command for robot control. However, the lack of intermediate semantics makes the system more rigid and unstable for practical use. To explore these issues, this paper proposes an innovate navigation framework based on the GPS-level localization, which takes the raw perception data with publicly accessible navigation maps to produce an intermediate navigation cost map that allows subsequent flexible motion planning. A deterministic conditional adversarial network is adopted in our method to generate visual goal-directed paths under diverse navigation conditions. The adversarial loss avoids the pixel-level annotation and enables a weakly supervised training strategy to implicitly learn both of the traffic semantics in image perceptions and the planning intentions in navigation instructions. The navigation cost map is then rendered from the goal-directed path and the concurrently collected laser data, indicating the way towards the destination. Comprehensive experiments have been conducted with a real vehicle running in our campus and the results have verified the robustness to localization error of the proposed navigation system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02468](http://arxiv.org/abs/1906.02468)

##### PDF
[http://arxiv.org/pdf/1906.02468](http://arxiv.org/pdf/1906.02468)

