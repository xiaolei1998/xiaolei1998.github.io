---
layout: page
title: Meta Office
description: with background image
img: assets/img/metaOffice/arm.png
importance: 1
category: work
related_publications: true
---

Based on the concept of metaverse, the prototype design of the intelligent office scene is carried out. The system integrates the multi-sensor data collected in real time and projects it into the virtual 3D world. The prototype realizes the interaction between the real user and the virtual world through the IMU sensor and realizes the projection of the real scene to the virtual space scene through the CV module.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/metaOffice/arm.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    This photo shows the user interface of virtual office, camera can scan work desktop environment and the system can project the detectected item into the virtual space. 
    User's arm movement is tracked by an IMU sensor, samely, detected motion will be tracked and projected into the virtual space.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/metaOffice/pipeline.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Above figure shows the data processing pipeline for the system. Virutal environment is moduled by Unity 3D.


