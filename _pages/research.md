---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I bet our interests overlap somehow; a source of my enthusiasm for research is finding shared interests with fellow researchers and practitioners is my source of joy in my job. While this has led to many interesting collaborations, my research efforts consistently fall into one of the following categories:

## Improving Model Delivery: My model's accurate, but why won't you use it?
### Prediction Timing
In time-sensitive settings (think intensive care unit), machine learning models are only useful when they give people enough time to react. We build models that learn to use as little data as possible to make accurate predictions. We've studied this problem in a variety of contexts:
* Time Series Classification (KDD'19)
* Multi-label Classification (KDD'20)
* Irregularly-sampled time series (KDD'22)
* Active Learning (NeurIPS'22)

### Explainability
It's hard to trust a machine's prediction when you don't know its reasoning. We've been studying methods for explaining machine predictions both through new explainability methods, and through human-computer interaction studies. We've recently covered a lot of ground:
* Time series (CIKM'21, KDD'22)
* Text classification (ACL'20)
* Shared-experience decision making (CHI'22)

### Fairness
Machine learned models are often unfair towards disadvantaged groups, perpetuating societal biases baked into their training data. We build methods for detecting and mitigating bias in many settings:
* Language Modeling (ACL'22)
* Surrogate models for explainability (FAccT'22)
* Active Learning (NeurIPS'22)

## Continuous Health: How do we monitor health between doctor's visits?
Most health data are collected at hospitals and clinics. But most people only go when they're already sick, so it's mysterious what in-the-wild health really looks like. We are building machine learning methods for learning from wearable device data to build broader definitions of health.

### Stress and Recovery (w/ University of Toronto, the Vector Institute, and 4YouAndMe)
Stress is pervasive and poorly understood. With a new approach to large-scale, in-the-wild wearable data collection, we seek new ways to quantify and qualify stress in people's daily lives:
* Identifying stress periods from wearables (Nature Medicine)
* Change Point Detection methods for digital health (NeurIPS'22)
* Relating subjective and objective measures of stress (ongoing)

### Pregnancy (w/ University of Toronto, the Vector Institute, and 4YouAndMe)
