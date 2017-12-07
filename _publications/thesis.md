---
title: "Uncertainty Adaptation in Robot Perception and Learning"
collection: publications
permalink: /publication/master-thesis
excerpt: 'Master Thesis.'
date: 2017-12-11
venue: 'Computer Science Department, Carnegie Mellon University'
paperurl: 'http://pengjujin.github.io/files/thesis.pdf'
citation: 'Pengju Jin (2017). &quot; Uncertainty Adaptation in Robot Perception and Learning.&quot;'
---

Dealing with uncertainty is a fundamental challenge for building any practicalrobot platform.  In fact, the ability to adapt and react to uncertain scenarios is anessential sign of an intelligent agent.  Furthermore, uncertainty can arise from ev-ery component of a robotic system.  Inaccurate motion models, sensory noises, andeven human factors are all common sources of the unexpected.  From an algorith-mic perspective, handling uncertainty in robotics introduces a new layer of difficultybecause the algorithm not only needs to be accurate in a single scenario but alsoneed to adapt to the changes in uncertainties as the environment shifts. This thesis presents methods for adapting to uncertainties in two tasks:  object pose estimationand assistive navigation. 

For  object  pose  estimation,  we  present  a  sensor  fusion  method  that  is  highlyrobust in estimating the pose of fiducial tags.  The method leverages the differentstructural and sensory advantages of RGB and Depth sensors to joint-optimize thePerspective-N-Point problem and obtains the pose. The key insight being adaptivelybounding the optimization region by testing the pose solution uncertainty.

For assistive navigation, we wish to tackle the problem of using active signalingto avoid pedestrians while it is minimally invasive to other people. We formulate theproblem as a bandit with expert advice problem with reinforcement learning poli-cies as the experts. We present an online learning algorithm which can continuouslyadapt to new and uncertain pedestrian types by using an online policy search tech-nique and the Dirichlet Process.

[Download paper here](http://pengjujin.github.io/files/thesis.pdf)
