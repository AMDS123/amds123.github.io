---
layout: post
title: "MPC for Humanoid Gait Generation: Stability and Feasibility"
date: 2019-01-24 17:02:08
categories: arXiv_RO
tags: arXiv_RO Review Prediction
author: Nicola Scianca, Daniele De Simone, Leonardo Lanari, Giuseppe Oriolo
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel MPC framework for humanoid gait generation which incorporates an explicit stability constraint in the formulation. The proposed method uses as prediction model a dynamically extended LIP where ZMP velocities are the control inputs, producing in real time a gait (including footsteps with the associated timing) that realizes omnidirectional motion commands coming from an external source. The stability constraint links the future ZMP velocities to the current system state so as to guarantee the essential requirement that the generated CoM trajectory is bounded with respect to the ZMP trajectory. Since the control horizon of the MPC algorithm is finite, only part of the future ZMP velocities are decision variables of the MPC problem; the remaining part, called tail, must be either conjectured or anticipated using preview information on the reference motion. Several possible options for the tail are discussed, and each of them is shown to correspond to a specific terminal constraint. The stability and feasibility of the proposed method are analyzed in detail: in particular, a theoretical analysis of the feasibility of the generic MPC iteration is developed and used to obtain sufficient conditions for recursive feasibility and stability. Simulation and experimental results on the NAO and the HRP-4 humanoids are presented to illustrate the performance of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08505](http://arxiv.org/abs/1901.08505)

##### PDF
[http://arxiv.org/pdf/1901.08505](http://arxiv.org/pdf/1901.08505)

