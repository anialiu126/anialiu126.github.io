---
layout: page
title: Systematic biases in tests of GR due to millilensing
description: Exploring systematic biases in parameterised tests of General Relativity 
img: assets/img/milli_ppE_system_configs.png
redirect: 
importance: 3
category: GW phenomenology
related_publications: true
---

In addition to precession investigated in Project 2, other factors can complicate GW signal interpretation, including deviations from GR.
So far, all GW observations have tested GR in the strong-field, dynamical regime, finding no deviations and placing constraints on possible non-GR theories. 
Parameterized tests, such as the parameterized post-Einsteinian (ppE) framework (Yunes, et al 2009), introduce deviations into waveform models to cover various modified theories.
However, these tests rely on accurate GW models which correctly describe the signals. 
A current challenge in GW inference is assessing how systematic errors could bias GR tests.
In this project {% cite liu2024millilensinginducedsystematicbiases %}, we conducted a Bayesian inference study to investigate the confusion of millilensing as false deviations from GR.
By simulating millilensed signals and analyzing them using unlensed GR and unlensed ppE models, we assessed millilensing's impact on GR tests.
Our findings indicate that biases depend on source mass (signal duration), lensing strength, SNR, and the post-Newtonian (PN) order of the recovered deviation. 

We developed a semi-analytical model for millilensed GWs to numerically fit lensed GW phase, allowing for direct comparisons between the two models.
By systematically exploring biases in ppE tests of GR, we quantified systematic and statistical errors, SNR loss, and Bayes factors between non-lensed ppE and GR analyses using linear signal and Laplace approximations.
This revealed clear trends in biases, with the semi-analytical framework indicating that biases are positive (negative) for negative (positive) PN orders and predicting which signals are most susceptible to these biases.

<div class="row justify-content-sm-center"> 
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/milli_ppE_system_configs.png" title="systems setup" class="img-fluid rounded z-depth-1" style="width:90%;" %}
    </div>
</div>
<div class="caption text-center">
    System configurations studied and corresponding waveforms in time domain.
</div>
