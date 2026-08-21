---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
description: Research on Bayesian methods, external controls, and real-world evidence for clinical trials.
---

<style>
  :root {
    --global-theme-color: #012169;
    --global-hover-color: #00539b;
  }

  .post-title {
    font-weight: 700;
  }

  .post-header .desc,
  .post h2 {
    font-size: 1.35rem;
    font-weight: 600;
  }
</style>

My research develops statistical methods that make better use of information within and beyond clinical trials. I focus on principled borrowing, clear treatment-effect estimands, and designs that remain robust when external and randomized data differ.

## Bayesian dynamic borrowing and hybrid controlled trials

<div class="row align-items-center mb-5">
  <div class="col-md-8">
    <p>I develop Bayesian adaptive methods for incorporating multiple external control sources into randomized controlled trials. This work studies how a trial can borrow information dynamically when external data are compatible with concurrent controls, while limiting borrowing when meaningful differences emerge.</p>
    <p>Current topics include robust prior construction, source-specific commensurability, sample-size re-estimation, and operating-characteristic evaluation for hybrid controlled trials.</p>
  </div>
  <div class="col-md-4">
    <img src="{{ '/assets/img/research/dynamic-borrowing.svg' | relative_url }}" alt="Diagram showing dynamic borrowing from multiple external controls into a randomized trial" class="img-fluid rounded">
  </div>
</div>

## External controls and causal inference

<div class="row align-items-center mb-5">
  <div class="col-md-8">
    <p>I study estimands and estimators for trials augmented by external control data. A central goal is to understand what treatment effect is being estimated when trial participants and external patients represent different populations.</p>
    <p>My work evaluates balancing weights and related causal methods for aligning populations, reducing measured confounding, and making assumptions transparent. Applications include early-phase and rare-disease settings where a conventional randomized control arm may be difficult to recruit.</p>
  </div>
  <div class="col-md-4">
    <img src="{{ '/assets/img/research/external-controls.svg' | relative_url }}" alt="Diagram showing population alignment between trial and external control data" class="img-fluid rounded">
  </div>
</div>

## Real-world evidence in clinical development

<div class="row align-items-center mb-5">
  <div class="col-md-8">
    <p>I investigate how real-world data can support clinical development and regulatory decision-making. This includes study design, data-quality assessment, endpoint construction, and statistical analysis for evidence generated from observational health data.</p>
    <p>My collaborative research applies these ideas in chronic lung allograft dysfunction, atrial fibrillation, and amyotrophic lateral sclerosis, connecting methodological development with practical clinical questions.</p>
  </div>
  <div class="col-md-4">
    <img src="{{ '/assets/img/research/real-world-evidence.svg' | relative_url }}" alt="Diagram connecting real-world clinical data to evidence and decisions" class="img-fluid rounded">
  </div>
</div>
