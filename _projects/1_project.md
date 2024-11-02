---
layout: page
title: Exploring the hidden Universe with GW millilensing
description: Phenomenological modelling of gravitational-wave millilensing
img: assets/img/waveform_shape.png
importance: 1
category: GW phenomenology
related_publications: true
---

### A novel phenomenological approach to model gravitational-wave millilensing using transdimensional sampling  

When gravitational waves (GWs) pass near massive objects, they become gravitationally lensed. 
Consequently, they travel on a different path, and the GW amplitude becomes magnified, phase shifted and arrival time - delayed. 
Moreover, multiple signals from the same source can arrive at the detectors. 

If the time delay between individual lensed GWs is short enough ($\mathcal{O}(10^{-3}-10^{-2})$ ms), they will overlap, leading to a single superposed GW arriving at the detector. 

There have been a number of efforts to date to study GW lensing. 
Even though lensing of GWs is predicted theoretically, there have been no confirmed detections up to date. 
Most of the widely used lensing studies assume a specific lens mass distribution (such as point mass or spherically distributed lens mass) and an isolated lens. 
However, this is physically not realistic, as we know that astrophysical objects reside in galaxies, and hence can gravitationally affect each other, potentially breaking any symmetries. 


<div class="row">   <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assests/img/strong_milli.png" title="strong milli setup" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example configuration of millilenses within a galaxy producing multiple millilensed GW signals (figure not to scale)
</div>
 

To solve this problem, together with collaborators, we developed a new, lens-model independent method to model GW lensing {% cite liu2023exploring %}.  
By parameterizing lensed gravitational-wave signals with lensing observables, we capture the imprints these observables leave on the signals. 
This method allows us to model arbitrary lensing configurations, as long as there is a single lens along the line of sight, without imposing model-specific restrictions. 
This results in a more physically realistic description of the lensing systems. 
The project involves transdimensional sampling, which we have implemented using the Bayesian inference library Bilby.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/waveform_shape.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        
    </div>
</div>
<div class="caption">
    
</div>


