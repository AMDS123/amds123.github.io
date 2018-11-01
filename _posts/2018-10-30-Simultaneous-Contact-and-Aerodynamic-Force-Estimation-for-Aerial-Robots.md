---
layout: post
title: "Simultaneous Contact and Aerodynamic Force Estimation for Aerial Robots"
date: 2018-10-30 10:32:51
categories: arXiv_RO
tags: arXiv_RO
author: Teodor Tomi&#x107; (1 and 2 and 3), Philipp Lutz (2), Korbinian Schmid (1 and 4), Andrew Mathers (5), Sami Haddadin (3) ((1) Skydio, (2) German Aerospace Center (DLR), (3) Technical University Munich (TUM), (4) Roboception GmbH, (5) Transportation Research Center)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of multirotor flying robots physically interacting with the environment under wind influence. The result are the first algorithms for simultaneous online estimation of contact and aerodynamic wrenches acting on the robot based on real-world data, without the need for dedicated sensors. For this purpose, we investigate two model-based techniques for discriminating between aerodynamic and interaction forces. The first technique is based on aerodynamic and contact torque models, and uses the external force to estimate wind speed. Contacts are then detected based on the residual between estimated external torque and expected (modeled) aerodynamic torque. Upon detecting contact, wind speed is assumed to change very slowly. From the estimated interaction wrench, we are also able to determine the contact location. This is embedded into a particle filter framework to further improve contact location estimation. The second algorithm uses the propeller aerodynamic power and angular speed as measured by the speed controllers to obtain an estimate of the airspeed. An aerodynamics model is then used to determine the aerodynamic wrench. Both methods rely on accurate aerodynamics models. Therefore, we evaluate data-driven and physics based models as well as offline system identification for flying robots. For obtaining ground truth data we performed autonomous flights in a 3D wind tunnel. Using this data, aerodynamic model selection, parameter identification, and discrimination between aerodynamic and contact forces could be done. Finally, the developed methods could serve as useful estimators for interaction control schemes with simultaneous compensation of wind disturbances.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12908](http://arxiv.org/abs/1810.12908)

##### PDF
[http://arxiv.org/pdf/1810.12908](http://arxiv.org/pdf/1810.12908)

