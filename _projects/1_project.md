---
layout: page
title: La Jolla Render
description: assignments for CSE272, a C++ path tracer featured with Disney bsdf, volumetric path tracing and ReSTIR DI.
img: assets/img/1.jpg
importance: 1
category: work
related_publications: false
---

This page includes some of miscellaneous path tracing implementation results written in 2023 ~ 2024. They are course assignments of 
[CSE 272](https://cseweb.ucsd.edu/~tzli/cse272/wi2024/) instructed by Professor 
[Tzu-Mao Li](https://cseweb.ucsd.edu/~tzli/).

The project use a custom physically-based renderer called [lajolla](https://github.com/BachiLi/lajolla_public) and more results are on [my own implemention](https://github.com/dongzhanghan/cse272-restir). 


## 1. Disney Principled BSDF

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/disney_bsdf.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Disney principled BSDF
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/disney_teapot.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A metal teapot
</div>

## 2. Volumetric Path Tracing
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vol_fog.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Heterogeneous Colored 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vol_cornell.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Volumetric Cornell Box  
</div>


## 3. ReSTIR DI

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spatial_reuse.png" title="Spatial Reuse Comparison" class="img-fluid rounded z-depth-1" %}
    <div class="caption">
    Spatial Reuse Comparison  
    </div>
    </div>
    
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bias.png" title="Spatial Reuse Comparison" class="img-fluid rounded z-depth-1" %}
    <div class="caption">
    Biased/Unbiased Comparison  
    </div>
    </div>
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/room.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    lovely room  
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cyberpenk.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Cyberpenk  
</div>
