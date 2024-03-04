---
layout: page
title: Argus-1
description: 1U Cubesat to demonstrate Visual-Inertial Navigation
img: assets/img/cubesat/ld_detection.png
importance: 1
category: work
related_publications: 
---


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/simplified_pipeline.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption"> Simplified Payload Pipeline  </div>


Argus-1 is a technology demonstration mission primarily for Visual-Inertial Attitude and Orbit Determination (A&OD) as a low-cost and efficient alternative to traditional methods (e.g. GPS, radio ranging, star trackers, ...) for small satellites. Its payload consists of 6 cameras placed on each face of the CubSat connected to NVIDIA Jetson Orin NX 16 Gb. A series of Neural Network-based region classifier and landmark detectors retrieves salient locations from Earth images (as directional vectors) and are passed down to the GNC stack where optimization-based algorithms perform the determination.




I lead the GNC team primarily with mission design, flight software, and GNC algorithm development and implementation.  

...

We passed our PDR. More updates coming soon.


<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0"></div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/argus_deploy.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0"></div>
</div>
<div class="caption"> Argus-1 in stowed (left) and deployed (right) configuration. </div>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/gnc_hw.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption"> GNC Hardware </div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img//cubesat/hl_fsw.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption"> High-level Flight Software Modules </div>



<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/sim.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/argus_tumbling.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Simulation
</div>