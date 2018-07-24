---
layout: post
title: "Walking Control Based on Step Timing Adaptation"
date: 2018-07-23 14:34:55
categories: arXiv_RO
tags: arXiv_RO
author: Majid Khadiv, Alexander Herzog, S. Ali A. Moosavian, Ludovic Righetti
mathjax: true
---

* content
{:toc}

##### Abstract
Step adjustment for biped robots has been shown to improve gait robustness, however the adaptation of step timing is often neglected in control strategies because it gives rise to non-convex problems when optimized over several steps. In this paper, we argue that it is not necessary to optimize walking over several steps to guarantee stability and that it is sufficient to merely select the next step timing and location. From this insight, we propose a novel walking pattern generator with linear constraints that optimally selects step location and timing at every control cycle. The resulting controller is computationally simple, yet guarantees that any viable state will remain viable in the future. We propose a swing foot adaptation strategy and show how the approach can be used with an inverse dynamics controller without any explicit control of the center of mass or the foot center of pressure. This is particularly useful for biped robots with limited control authority on their foot center of pressure, such as robots with point feet and robots with passive ankles. Extensive simulations on a humanoid robot with passive ankles subject to external pushes and foot slippage demonstrate the capabilities of the approach in cases where the foot center of pressure cannot be controlled and emphasize the importance of step timing adaptation to stabilize walking.

##### Abstract (translated by Google)
已经表明，针对两足机器人的步进调整可以改善步态稳健性，但是在控制策略中经常忽略步长定时的调整，因为当在几个步骤上进行优化时它会引起非凸问题。在本文中，我们认为没有必要优化几步的步行以保证稳定性，仅仅选择下一步的时间和位置就足够了。根据这一见解，我们提出了一种具有线性约束的新型步行模式发生器，可在每个控制周期中最佳地选择步进位置和时间。由此产生的控制器计算简单，但保证任何可行的状态在未来仍然可行。我们提出了一种摆动脚适应策略，并展示了该方法如何与逆动力学控制器一起使用，而无需明确控制质心或压力中心。这对于在其足部压力中心具有有限控制权的双足机器人尤其有用，例如具有尖脚的机器人和具有被动脚踝的机器人。对受到外部推动和脚滑动的被动脚踝的人形机器人进行了广泛的模拟，证明了在无法控制压脚中心的情况下该方法的能力，并强调步进时间适应对稳定步行的重要性。

##### URL
[http://arxiv.org/abs/1704.01271](http://arxiv.org/abs/1704.01271)

##### PDF
[http://arxiv.org/pdf/1704.01271](http://arxiv.org/pdf/1704.01271)

