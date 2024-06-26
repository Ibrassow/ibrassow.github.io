---
layout: page
title: Argus-1
description: 1U Cubesat Development for Visual-Inertial Navigation demonstration
img: assets/img/cubesat/argus_flatsat3.jpg
importance: 1
category: work
related_publications: 
---

Argus-1 is a technology demonstration mission primarily for Visual-Inertial Attitude and Orbit Determination (A&OD) as a low-cost and efficient alternative to traditional methods (e.g. GPS, radio ranging, star trackers, ...) for small satellites. Its payload consists of cameras placed on faces of the CubSat and a NVIDIA Jetson. A series of Neural Network-based region classifier and landmark detectors retrieves salient locations from Earth images (as directional vectors) and are passed down to optimization-based algorithms to perform the determination. I lead the team primarily with system design, flight software, GNC, communications, and payload development. I was also a TA for a related class [Spacecraft Design-Build-Fly](https://github.com/cmu-spacecraft-design-build-fly-2023), taught by Pr. Zachary Machester and Pr. Brandon Lucia at CMU.


<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/argus_flatsat1.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/argus_flatsat2.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    V1 Flatsat
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/ld_detection.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption"> Landmark Detection </div>

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/simplified_pipeline.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption"> Simplified Payload Pipeline  </div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0"></div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cubesat/argus_deploy.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0"></div>
</div>
<div class="caption"> Argus-1 in stowed (left) and deployed (right) configuration. </div>
