---
layout: page
title: Arduino-based Guitar Tuner
description: Guitar Tuner Built From Scratch Using Physics Principles
img: assets\img\tuner1.jpg
importance: 1
category: work
related_publications: true
---

In this project, I developed a guitar tuner using physics principles, Fourier transforms, and Python analysis. Utilizing a microphone and Arduino, the tuner accurately identifies guitar notes and tuning accuracy, though it slightly underestimates the low E note (82.4 Hz), leading to flat tunings. 

Python analysis showed higher strings have dominant frequencies beyond the expected one. The main constraints are the microphone's sensitivity range and the Arduino's limited computational capacity, affecting precision for certain notes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets\img\tuner2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets\img\tuner3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets\img\tuner4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
