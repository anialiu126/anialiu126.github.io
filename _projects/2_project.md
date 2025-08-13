---
layout: page
title: Can we distinguish millilensed GWs from precessing GW signals?
description: 
img: assets/img/precessing_millilensed_waveform.png
importance: 2
category: GW phenomenology
giscus_comments: false
related_publications: true
---

When gravitational waves are lensed by small mass objects (10<sup>2</sup> - 10<sup>6</sup> M<sub>⊙</sub>), multiple copies of the GW signal overlap on top of each other. 
The overlapping of individual millilensed signals would produce <b>frequency-dependent beating patterns</b> observed in the waveform shape. 
<b>Precessing binary black holes can mimic the same beat:</b> misaligned spins tilt the orbital plane over time, leaving amplitude and phase modulations that look deceptively similar to those produced by lensing.

<div class="row">
    <div class="col-md mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/precessing_millilensed_waveform.png" title="Comparison of millilensed and precessing GWs" class="img-fluid rounded z-depth-1" %}
    </div>
</div>



<b>So if we catch a waveform with a clear beat, what’s really behind it—lensing, spin-induced precession, or something else?</b>


<div class="row">
    <div class="col-md mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/precessing_millilensed_waveform.png" title="Comparison of millilensed and precessing GWs" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


In this project, <b>we explored how well we can tell apart two look-alike signals—millilensed and precessing binary black holes—</b>using simulated signals for the current LIGO–Virgo–KAGRA detector network. Our approach combined:

1. Signal-to-noise ratio (SNR) comparisons across different waveform templates.

2. Parameter estimation (PE) studies, where we injected various combinations of (un)lensed and (non)precessing signals into simulated LVK data and recovered them with different model assumptions. This covered a broad range of binary configurations and SNRs.

<b>What we found:</b> In most cases, we could recover lensing parameters even when the analysis model ignored precession.  
But when lensing was neglected, things got messy-—missing lensing effects could mimic extremal spins (up to ~0.9), far above the ~0.7 spins predicted for astrophysical black holes.

<b>Takeaway: If we see a gravitational wave that looks highly precessing, we can’t jump straight to “extreme spins.” It might be a sign that lensing physics is hiding in plain sight—and ignoring it could completely distort our astrophysical conclusions.</b>
If you want to find out more, check out our paper{% cite liu2024discernmillilensedgravitationalwavesignals %}!

