---
layout: post
title: "An Implementation of a Non-monotonic Logic in an Embedded Computer for a Motor-glider"
date: 2019-07-31 04:48:56
categories: arXiv_AI
tags: arXiv_AI Face
author: Jos&#xe9; Luis Vilchis Medina, Pierre Siegel, Vincent Risch, Andrei Doncescu
mathjax: true
---

* content
{:toc}

##### Abstract
In this article we present an implementation of non-monotonic reasoning in an embedded system. As a part of an autonomous motor-glider, it simulates piloting decisions of an airplane. A real pilot must take care not only about the information arising from the cockpit (airspeed, altitude, variometer, compass...) but also from outside the cabin. Throughout a flight, a pilot is constantly in communication with the control tower to follow orders, because there is an airspace regulation to respect. In addition, if the control tower sends orders while the pilot has an emergency, he may have to violate these orders and airspace regulations to solve his problem (e.g. emergency landing). On the other hand, climate changes constantly (wind, snow, hail...) and can affect the sensors. All these cases easily lead to contradictions. Switching to reasoning under uncertainty, a pilot must make decisions to carry out a flight. The objective of this implementation is to validate a non-monotonic model which allows to solve the question of incomplete and contradictory information. We formalize the problem using default logic, a non-monotonic logic which allows to find fixed-points in the face of contradictions. For the implementation, the Prolog language is used in an embedded computer running at 1 GHz single core with 512 Mb of RAM and 0.8 watts of energy consumption.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13305](http://arxiv.org/abs/1907.13305)

##### PDF
[http://arxiv.org/pdf/1907.13305](http://arxiv.org/pdf/1907.13305)

