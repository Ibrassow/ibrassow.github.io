---
layout: page
title: On-Orbit Small-Satellite Localization
description: Autonomous Range-Only Navigation for Satellite Formations
img: assets/img/relative_ranging/py4_diag.jpeg
importance: 1
category: work
related_publications: py4_paper, ibrahima2025
---

PY4 is a constellation of four 1.5U CubeSats launched on SpaceX Transporter 10 on March 4, 2024, in a collaboration between Carnegie Mellon University and NASA Ames Research Center. I personally contributed to the GNC stack of the mission, primarily responsible for the successful demonstration of range-only orbit determination between 2 of our 4 satellites.


<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/relative_ranging/PY4_ready.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The four PY4 satellites, a collaboration between Carnegie Mellon University and NASA Ames Research Center,
    were launched on March 4, 2024 on the SpaceX Transporter 10 mission and deployed on a sun-synchronous orbit. The 1.5U
    satellites demonstrated a suite of novel navigation and control algorithms for low-cost platforms.
</div>

**Abstract**:
The availability of low-cost small satellites and commercial launch services has enabled a proliferation of distributed small satellite missions. However, these missions require precise relative navigation, traditionally provided by expensive GNSS receivers that are limited to operation in low-Earth orbit. In this paper, we introduce a novel, scalable, cost-effective navigation method for both absolute and relative orbit determination that is suitable for resource-constrained small-satellite formations. Our approach combines inter-satellite ranging, a single "anchor" satellite with global measurements, and a highly accurate dynamics model in a nonlinear least-squares estimator. We demonstrate that our estimator can resolve the full orbital states of all spacecraft in a formation despite the inherent ambiguities of range-only navigation. We evaluated our method through numerical experiments with varied network topologies and an on-orbit demonstration during the PY4 satellite mission, achieving absolute positioning accuracy of 0.21m for the anchor satellite and 0.33m for the non-anchor satellite.


