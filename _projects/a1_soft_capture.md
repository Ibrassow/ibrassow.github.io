---
layout: page
title: Soft Capture of Tumbling Spacecraft
description: A convex formulation for trajectory optimization
img: assets/img/soft_capture/approach_wide.gif
importance: 1
category: work
related_publications: ibrahima2024
---

<div class="row">
    <div class="col-sm">
        {% include figure.html path="assets/img/soft_capture/first_pager_frame.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A Soft capture maneuver requires 4 phases: 1. the chaser (beige) approaches the target (pink) while maintaining its line of sight 2. impulsive
burns avoid collision with the client (thrust vector in red) 3. corrective burns
align capture end-effector with the target capture frame 4. chaser is within
the capture ball and activates its end-effector.
</div>


**Abstract**:
We present a fast trajectory optimization algorithm for the soft capture of non-cooperative tumbling space objects. Our algorithm generates safe, dynamically feasible, and minimum-fuel trajectories for a six-degree-of-freedom servicing spacecraft to achieve soft capture (near-zero relative velocity at contact) between predefined locations on the servicer spacecraft and target body. We solve a convex problem by enforcing a convex relaxation of the field-of-view constraint, followed by a sequential convex program correcting the trajectory for collision avoidance. The optimization problems can be solved with a standard second-order cone programming solver, making the algorithm both fast and practical for implementation in flight software. We demonstrate the performance and robustness of our algorithm in simulation over a range of object tumble rates up to 10 °/s.


<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0"></div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/soft_capture/tumbling.gif" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0"></div>
</div>
<div class="caption"> It all comes down to capturing this safely... (accelerated) </div>
    
