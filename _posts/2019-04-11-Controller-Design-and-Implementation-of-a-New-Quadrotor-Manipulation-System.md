---
layout: post
title: "Controller Design and Implementation of a New Quadrotor Manipulation System"
date: 2019-04-11 14:10:59
categories: arXiv_RO
tags: arXiv_RO
author: Ahmed Khalifa
mathjax: true
---

* content
{:toc}

##### Abstract
The previously introduced aerial manipulation systems suffer from either limited end-effector DOF or small payload capacity. In this dissertation, a quadrotor with a 2-DOF manipulator is investigated that has a unique topology to enable the end-effector to track 6-DOF trajectory with the minimum possible number of actuators/links and hence, maximize the payload and/or mission time. The proposed system is designed, modeled, and constructed. An identification process is carried out to find the system parameters. An experimental setup is proposed with a 6-DOF state measurement and estimation scheme. The system feasibility is validated via numerical and experimental results. The inverse kinematics require a solution of complicated algebraic-differential equations. Therefore, an algorithm is developed to get an approximate solution of these equations. Furthermore, the motion control of this quadrotor manipulation system is quite challenging. The system has strong nonlinearities, fast dynamics and unstable dynamics that are very susceptible to parameters variations and external disturbances. Thus, a linear Disturbance Observer (DOb)-based robust controller is utilized to address these issues. A modified DOb loop is proposed and designed to use the direct measurements. A Model Predictive Control (MPC) is used in the external loop of the DOb to save power consumption that increases the mission time and to consider of the actuators constraints. The manipulation tasks require estimating (applying) certain force at the end-effector. However, the current developed techniques have limitations because they are model-based methods, based on ignoring some dynamics, or requiring an indicator of the environment contact. Hence, a robust sensorless force estimation and impedance control scheme is proposed to overcome these limitations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08498](http://arxiv.org/abs/1904.08498)

##### PDF
[http://arxiv.org/pdf/1904.08498](http://arxiv.org/pdf/1904.08498)

