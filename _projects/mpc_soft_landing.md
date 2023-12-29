---
layout: page
title: Convex Model-Predictive Control for Rocket Landing
description: Convex MPC for the Soft Landing Problem under force disturbances 
img: assets/img/starship_mars_landing.jpg
importance: 1
category: work
related_publications: 
---

This initial project was done as part of my [Optimal Control & Reinforcement Learning](https://github.com/Optimal-Control-16-745/) class project, taught by Zac Manchester.

[Github Repository](https://github.com/Ibrassow/soft_landing_mpc)

This project reproduces the Powered-Descent Guidance algorithm used to solve the classical soft landing problem and run them using a Model Predictive Controller while we introduce force disturbances. There is still a lot of work to be done before we have robust Powered Descent Guidance algorithms, which means there are many areas for improvement!


More descriptions and videos coming soon..

...

I'm also working on a low-level thrust vector control (TVC) system taking in the desired linear accelerations (this work) and output the thrust magnitude, pitch, and yaw angles. This TVC reasons independently about the attitude.